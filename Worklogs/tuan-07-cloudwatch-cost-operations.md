# Tuần 07 - CloudWatch, cost guardrail và vận hành

## Mục tiêu tuần

Tuần này ghi lại phần học và thực hành theo lộ trình AWS FCAJ. Reference được tách thành hai lớp: file minh chứng trong repo này và workshop cộng đồng AWS Study Group để người đọc biết chính xác nội dung học dựa trên nguồn nào.

## Bảng tham chiếu theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 27/07/2026 | Bật tư duy CloudWatch Container Insights cho ECS/Fargate và log driver awslogs. | [Module 8](../First%20Cloud%20AI%20Journey/Module%208/module-08-ly-thuyet-serverless-observability-iac.md)<br>[Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)<br>[000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 3 | 28/07/2026 | Thiết kế Log Group naming, retention và Logs Insights query cho lỗi HTTP/app/security scan. | [Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md)<br>[Lab 85 Monitoring](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-85-serverless-monitoring-xray.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)<br>[000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/) |
| Thứ 4 | 29/07/2026 | Lập dashboard CPU, memory, task count, target health, deployment event và VPC/network signal. | [Lab 74 Flow Logs](../First%20Cloud%20AI%20Journey/Module%202/Hands-on%20Labs/lab-74-vpc-flow-logs.md)<br>[Lab 08 CloudWatch](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-08-cloudwatch-logs-metrics-alarms.md) | [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)<br>[000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/) |
| Thứ 5 | 30/07/2026 | Tạo ghi chú cost guardrail bằng AWS Budgets, threshold notification và cleanup cadence. | [Lab 01 Free Tier](../First%20Cloud%20AI%20Journey/Module%201/Hands-on%20Labs/lab-01-free-tier-budget-guardrail.md) | [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/) |
| Thứ 6 | 31/07/2026 | Viết incident drill: phát hiện lỗi, xem deployment, đọc log, kiểm tra target health và rollback/scale down. | [Lab 31 SSM](../First%20Cloud%20AI%20Journey/Module%203/Hands-on%20Labs/lab-31-systems-manager-run-command.md)<br>[Lab 98 GuardDuty](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-98-guardduty-finding-practice.md) | [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)<br>[000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) |

## Kết quả rút ra

- Nội dung trong tuần đã được viết lại bằng tiếng Việt theo góc nhìn cá nhân, không giữ nguyên cấu trúc câu của workshop gốc.
- Mỗi ngày có ít nhất một minh chứng nội bộ hoặc workshop liên quan để khi đưa vào Hugo Worklog không bị trỏ sai module/lab.
- Các lab có cleanup hoặc cảnh báo chi phí để phù hợp với môi trường thực tập và tài khoản cá nhân.
