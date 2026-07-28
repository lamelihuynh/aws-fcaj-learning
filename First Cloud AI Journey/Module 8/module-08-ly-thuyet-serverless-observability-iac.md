# Module 08 - Serverless, observability và Infrastructure as Code

## Mình học phần này để làm gì

Phần này hỗ trợ phần xử lý report và vận hành: Lambda, API Gateway, S3 trigger, CloudWatch Logs/Metrics/Alarms/Dashboard, X-Ray, CloudFormation và runbook xử lý sự cố.

## Ý mình cần nhớ

- Dùng Lambda cho tác vụ event-driven như tổng hợp file report khi S3 phát sinh object mới.
- Đưa log ứng dụng, log Lambda và metric container về CloudWatch để điều tra theo thời gian.
- Dùng CloudWatch Alarm/Budgets để phát hiện lỗi hoặc chi phí vượt ngưỡng sớm.
- Dùng CloudFormation để mô tả tài nguyên lặp lại và hỗ trợ kiểm tra drift.

## Dùng lại trong báo cáo

- Dùng trong Week 5 khi thiết kế Lambda aggregator.
- Dùng trong Week 7 khi thiết kế dashboard, log query, alarm và cost guardrail.

## Workshop mình tham khảo

- [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)
- [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)
- [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/)
- [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)
- [000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/)

## Tài liệu AWS

- AWS Lambda Developer Guide: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html
- Amazon CloudWatch User Guide: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html

## Tự nhắc

- Khi đưa vào báo cáo, mình cần gắn khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Nếu nhắc tới dịch vụ này, mình nên nói thêm một rủi ro hoặc lỗi cấu hình dễ gặp.
