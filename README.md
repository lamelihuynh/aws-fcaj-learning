# AWS FCAJ Learning - Kho minh chứng cá nhân

Repo này lưu ghi chú học tập, module lý thuyết, lab thực hành và worklog cho báo cáo AWS First Cloud AI Journey. Nội dung được viết bằng tiếng Việt để dùng trực tiếp với bản báo cáo, đồng thời các link reference trỏ về đúng workshop AWS Study Group hoặc tài liệu AWS chính thức.

## Quy ước phân biệt module và lab

- `module-xx-ly-thuyet-...md`: ghi chú lý thuyết, dùng để giải thích khái niệm, quyết định kiến trúc và cách áp dụng vào báo cáo.
- `Hands-on Labs/lab-xx-...md`: bài thực hành bám theo workshop cộng đồng, có mục tiêu cá nhân, luồng kiểm chứng, lỗi cần tránh và cleanup.
- `Worklogs/tuan-xx-...md`: nhật ký học theo tuần, dùng để liên kết từng ngày trong Hugo Worklog với đúng module/lab.

Cách đặt tên này cố ý khác với bản mẫu cũ, nhưng vẫn giữ mã lab `12`, `57`, `98`... để truy vết được workshop gốc.

## Cấu trúc repo

```text
aws-fcaj-learning/
├── First Cloud AI Journey/
│   ├── Module 1/ ... Module 9/
│   └── mỗi module có README, file module lý thuyết và Hands-on Labs
├── Worklogs/
│   └── tuan-01-...md đến tuan-09-...md
└── Blog-Proofs/
```

## Module và nguồn học chính

| Module | Chủ đề | Ghi chú | Workshop tiêu biểu |
| --- | --- | --- | --- |
| Module 1 | Nền tảng cloud, tài khoản AWS và định danh | [Ghi chú](First%20Cloud%20AI%20Journey/Module%201/module-01-ly-thuyet-cloud-account-identity.md) | [000001 - AWS Free Tier 2025](https://000001.awsstudygroup.com/vi/), [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/), [000012 - AWS IAM Identity Center](https://000012.awsstudygroup.com/vi/) |
| Module 2 | Amazon VPC, routing và bảo mật mạng | [Ghi chú](First%20Cloud%20AI%20Journey/Module%202/module-02-ly-thuyet-vpc-networking-security.md) | [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/), [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/) |
| Module 3 | Amazon EC2, EBS, AMI và Auto Scaling | [Ghi chú](First%20Cloud%20AI%20Journey/Module%203/module-03-ly-thuyet-ec2-ebs-auto-scaling.md) | [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/), [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/), [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/) |
| Module 4 | Amazon S3, hybrid storage, backup và DR | [Ghi chú](First%20Cloud%20AI%20Journey/Module%204/module-04-ly-thuyet-s3-storage-backup-dr.md) | [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/), [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/), [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/) |
| Module 5 | Security, IAM nâng cao, KMS và detection | [Ghi chú](First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md) | [000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/), [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/), [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) |
| Module 6 | RDS, cache và lựa chọn dịch vụ dữ liệu | [Ghi chú](First%20Cloud%20AI%20Journey/Module%206/module-06-ly-thuyet-rds-cache-data-services.md) | [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/), [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/), [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/) |
| Module 7 | Containers, Amazon ECR, ECS Fargate và CI/CD | [Ghi chú](First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/), [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/), [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Module 8 | Serverless, observability và Infrastructure as Code | [Ghi chú](First%20Cloud%20AI%20Journey/Module%208/module-08-ly-thuyet-serverless-observability-iac.md) | [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/), [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/), [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/) |
| Module 9 | Kiến trúc DevSecOps, workshop và báo cáo cuối kỳ | [Ghi chú](First%20Cloud%20AI%20Journey/Module%209/module-09-ly-thuyet-architecture-devsecops-report.md) | [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/), [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/), [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/) |

## Worklog 9 tuần

- [Tuần 01 - Nền tảng cloud, IAM Identity Center và VPC](Worklogs/tuan-01-nen-tang-cloud-iam-vpc.md)
- [Tuần 02 - EC2, storage, backup và DR](Worklogs/tuan-02-compute-storage-dr.md)
- [Tuần 03 - Security, dữ liệu và CI/CD nền tảng](Worklogs/tuan-03-security-data-cicd.md)
- [Tuần 04 - Amazon ECR, image tag và image security](Worklogs/tuan-04-ecr-container-image-security.md)
- [Tuần 05 - ECS Fargate, S3 report bucket và Lambda aggregator](Worklogs/tuan-05-ecs-fargate-s3-lambda.md)
- [Tuần 06 - GitOps, release control và rollback](Worklogs/tuan-06-gitops-release-control.md)
- [Tuần 07 - CloudWatch, cost guardrail và vận hành](Worklogs/tuan-07-cloudwatch-cost-operations.md)
- [Tuần 08 - Kiến trúc DevSecOps và workshop cuối kỳ](Worklogs/tuan-08-devsecops-architecture-workshop.md)
- [Tuần 09 - Hugo report, reference và bàn giao](Worklogs/tuan-09-hugo-report-cleanup.md)

## Ghi chú đạo văn

Repo này không copy nội dung của repo mẫu hoặc workshop gốc. Workshop được dùng như tài liệu tham khảo; phần trong repo chỉ ghi lại cách mình hiểu, cách mình kiểm chứng và cách mình liên hệ với báo cáo thực tập.
