# Module 06 - RDS, cache và lựa chọn dịch vụ dữ liệu

## Vai trò trong lộ trình

Module này dùng để phân loại workload dữ liệu: RDS/Aurora cho quan hệ, DynamoDB cho key-value/serverless, Redshift cho analytics, S3 data lake cho object scale lớn và ElastiCache Redis cho cache độ trễ thấp.

## Quy ước file trong module

- File bắt đầu bằng `module-` là ghi chú lý thuyết, dùng để giải thích khái niệm và cách áp dụng vào báo cáo.
- File trong thư mục `Hands-on Labs/` bắt đầu bằng `lab-` là minh chứng thực hành, bám theo workshop cộng đồng AWS Study Group nhưng được viết lại theo luồng học cá nhân.

## Nội dung chính

- [Ghi chú lý thuyết](module-06-ly-thuyet-rds-cache-data-services.md)

## Hands-on Labs

| Lab | Workshop gốc | Mục tiêu cá nhân |
| --- | --- | --- |
| [Lab 05 - Amazon RDS, Multi-AZ và backup cơ bản](Hands-on%20Labs/lab-05-rds-application-backup.md) | [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/) | Tạo RDS instance trong VPC, kết nối từ EC2/app mẫu và hiểu backup/restore cơ bản. |
| [Lab 61 - Amazon ElastiCache Redis](Hands-on%20Labs/lab-61-elasticache-redis.md) | [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/) | Hiểu Redis cache trên AWS và cách ứng dụng kết nối cache trong subnet an toàn. |
| [Lab 35 - Data lake baseline trên S3](Hands-on%20Labs/lab-35-s3-datalake-baseline.md) | [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/) | Ghi chú mô hình data lake căn bản trên S3 để so sánh với RDS/Redshift/ElastiCache. |

## Liên kết với Worklog

Module này được dùng chính trong **Tuần 3**, và được tái sử dụng ở các tuần sau khi kiến trúc cần cùng nền tảng dịch vụ.
