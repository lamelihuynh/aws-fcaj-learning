# Module 08 - Serverless, observability và Infrastructure as Code

## Vai trò trong lộ trình

Module này hỗ trợ phần xử lý report và vận hành: Lambda, API Gateway, S3 trigger, CloudWatch Logs/Metrics/Alarms/Dashboard, X-Ray, CloudFormation và runbook xử lý sự cố.

## Quy ước file trong module

- File bắt đầu bằng `module-` là ghi chú lý thuyết, dùng để giải thích khái niệm và cách áp dụng vào báo cáo.
- File trong thư mục `Hands-on Labs/` bắt đầu bằng `lab-` là minh chứng thực hành, bám theo workshop cộng đồng AWS Study Group nhưng được viết lại theo luồng học cá nhân.

## Nội dung chính

- [Ghi chú lý thuyết](module-08-ly-thuyet-serverless-observability-iac.md)

## Hands-on Labs

| Lab | Workshop gốc | Mục tiêu cá nhân |
| --- | --- | --- |
| [Lab 08 - CloudWatch Logs, Metrics, Alarms và Dashboards](Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/) | Thiết lập quan sát cơ bản cho workload bằng CloudWatch metric, log, alarm và dashboard. |
| [Lab 37 - CloudFormation baseline và drift awareness](Hands-on%20Labs/lab-37-cloudformation-baseline.md) | [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/) | Làm quen Infrastructure as Code bằng CloudFormation template và hiểu drift detection ở mức cơ bản. |
| [Lab 66 - Lambda, API Gateway và SAM](Hands-on%20Labs/lab-66-lambda-api-gateway-sam.md) | [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/) | Hiểu serverless backend với Lambda, API Gateway, S3/DynamoDB/Cognito theo mô hình workshop serverless. |
| [Lab 85 - Monitoring serverless với CloudWatch và X-Ray](Hands-on%20Labs/lab-85-serverless-monitoring-xray.md) | [000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/) | Theo dõi ứng dụng serverless bằng CloudWatch metric/log và X-Ray trace. |

## Liên kết với Worklog

Module này được dùng chính trong **Tuần 5-7**, và được tái sử dụng ở các tuần sau khi kiến trúc cần cùng nền tảng dịch vụ.
