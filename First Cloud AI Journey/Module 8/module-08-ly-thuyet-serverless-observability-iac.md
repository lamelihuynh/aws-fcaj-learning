# Module 08 - Serverless, observability và Infrastructure as Code

## Mục đích

Module này hỗ trợ phần xử lý report và vận hành: Lambda, API Gateway, S3 trigger, CloudWatch Logs/Metrics/Alarms/Dashboard, X-Ray, CloudFormation và runbook xử lý sự cố.

## Ghi chú lý thuyết chính

- Dùng Lambda cho tác vụ event-driven như tổng hợp file report khi S3 phát sinh object mới.
- Đưa log ứng dụng, log Lambda và metric container về CloudWatch để điều tra theo thời gian.
- Dùng CloudWatch Alarm/Budgets để phát hiện lỗi hoặc chi phí vượt ngưỡng sớm.
- Dùng CloudFormation để mô tả tài nguyên lặp lại và hỗ trợ kiểm tra drift.

## Cách dùng trong báo cáo

- Dùng trong Week 5 khi thiết kế Lambda aggregator.
- Dùng trong Week 7 khi thiết kế dashboard, log query, alarm và cost guardrail.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)
- [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)
- [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/)
- [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)
- [000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- AWS Lambda Developer Guide: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html
- Amazon CloudWatch User Guide: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
