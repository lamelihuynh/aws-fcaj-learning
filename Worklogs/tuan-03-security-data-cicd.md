# Tuần 03 - Security, dữ liệu và CI/CD nền tảng

## Trọng tâm

Tuần này ghi lại các nội dung đã học, lab đã tham khảo và workshop cần đối chiếu khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 29/06/2026 | Ôn Shared Responsibility, IAM policy, role, boundary và Service Control Policy ở mức khái niệm. | [Module 5](../First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md)<br>[Lab 02 IAM](../First%20Cloud%20AI%20Journey/Module%202/Hands-on%20Labs/lab-02-iam-user-role-baseline.md) | [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/) |
| Thứ 3 | 30/06/2026 | Thực hành permission boundary, trust policy condition và EC2 instance profile thay cho access key. | [Module 5](../First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md)<br>[Lab 30 Boundary](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-30-permission-boundary.md)<br>[Lab 44 Role Condition](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-44-iam-role-condition.md)<br>[Lab 48 Instance Profile](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-48-ec2-instance-profile.md) | [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/)<br>[000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/)<br>[000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/) |
| Thứ 4 | 01/07/2026 | Ghi chú KMS, S3 encryption, CloudTrail audit, Security Hub và GuardDuty finding. | [Module 5](../First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md)<br>[Lab 33 KMS](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-33-kms-s3-cloudtrail-athena.md)<br>[Lab 18 Security Hub](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-18-security-hub-baseline.md)<br>[Lab 98 GuardDuty](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-98-guardduty-finding-practice.md) | [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)<br>[000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/)<br>[000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) |
| Thứ 5 | 02/07/2026 | So sánh RDS, Aurora, DynamoDB, Redshift, S3 data lake và ElastiCache theo workload. | [Module 6](../First%20Cloud%20AI%20Journey/Module%206/module-06-ly-thuyet-rds-cache-data-services.md)<br>[Lab 05 RDS](../First%20Cloud%20AI%20Journey/Module%206/Hands-on%20Labs/lab-05-rds-application-backup.md)<br>[Lab 61 Redis](../First%20Cloud%20AI%20Journey/Module%206/Hands-on%20Labs/lab-61-elasticache-redis.md) | [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/)<br>[000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/) |
| Thứ 6 | 03/07/2026 | Đọc luồng CI/CD container để chuẩn bị cho ECR/ECS ở các tuần sau. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md)<br>[Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |

## Kết quả chính

- IAM nâng cao, KMS, Security Hub và GuardDuty là nền tảng cho security gate trong workshop cuối kỳ.
- Lựa chọn database cần dựa trên workload: transaction, analytics, cache hoặc object/data lake.
