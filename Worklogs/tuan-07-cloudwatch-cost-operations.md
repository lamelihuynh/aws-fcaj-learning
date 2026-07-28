# Tuần 07 - CloudWatch, cost guardrail và vận hành

## Mình tập trung vào

Tuần này mình ghi lại các phần đã học, lab đã xem và link workshop cần mở lại khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 27/07/2026 | Bật tư duy CloudWatch Container Insights cho ECS/Fargate và log driver awslogs. | [Module 8](../First%20Cloud%20AI%20Journey/Module%208/module-08-ly-thuyet-serverless-observability-iac.md)<br>[Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)<br>[000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 3 | 28/07/2026 | Thiết kế Log Group naming, retention và Logs Insights query cho lỗi HTTP/app/security scan. | [Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md)<br>[Lab 85 Monitoring](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-85-serverless-monitoring-xray.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)<br>[000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/) |
| Thứ 4 | 29/07/2026 | Lập dashboard CPU, memory, task count, target health, deployment event và VPC/network signal. | [Lab 74 Flow Logs](../First%20Cloud%20AI%20Journey/Module%202/Hands-on%20Labs/lab-74-vpc-flow-logs.md)<br>[Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md) | [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)<br>[000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/) |
| Thứ 5 | 30/07/2026 | Tạo ghi chú cost guardrail bằng AWS Budgets, threshold notification và cleanup cadence. | [Lab 01 Free Tier](../First%20Cloud%20AI%20Journey/Module%201/Hands-on%20Labs/lab-01-free-tier-budget-guardrail.md) | [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/) |
| Thứ 6 | 31/07/2026 | Viết incident drill: phát hiện lỗi, xem deployment, đọc log, kiểm tra target health và rollback/scale down. | [Lab 31 SSM](../First%20Cloud%20AI%20Journey/Module%203/Hands-on%20Labs/lab-31-systems-manager-run-command.md)<br>[Lab 98 GuardDuty](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-98-guardduty-finding-practice.md) | [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)<br>[000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) |

## Ghi chú cuối tuần

- CloudWatch phải được chuẩn bị trước khi lỗi xảy ra: log group, query, metric và alarm cần có từ đầu.
- Cost guardrail là một phần vận hành, nhất là với NAT Gateway, ALB, RDS hoặc log giữ quá lâu.
