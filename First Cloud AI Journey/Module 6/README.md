# Module 06 - RDS, cache và lựa chọn dịch vụ dữ liệu

## Phạm vi module

Phần này dùng để phân loại workload dữ liệu: RDS/Aurora cho quan hệ, DynamoDB cho key-value/serverless, Redshift cho analytics, S3 data lake cho object scale lớn và ElastiCache Redis cho cache độ trễ thấp.

## File trong thư mục

- File `module-...md`: lưu phần lý thuyết, thuật ngữ và ý chính.
- Thư mục `Hands-on Labs/`: lưu luồng thực hành, kiểm chứng và ghi chú cleanup.

## Ghi chú chính

- [Ghi chú lý thuyết](module-06-ly-thuyet-rds-cache-data-services.md)

## Hands-on Labs

| Lab | Workshop | Mục tiêu |
| --- | --- | --- |
| [Lab 05 - Amazon RDS, Multi-AZ và backup cơ bản](Hands-on%20Labs/lab-05-rds-application-backup.md) | [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/) | Tạo RDS instance trong VPC, kết nối từ EC2/app mẫu và hiểu backup/restore cơ bản. |
| [Lab 61 - Amazon ElastiCache Redis](Hands-on%20Labs/lab-61-elasticache-redis.md) | [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/) | Hiểu Redis cache trên AWS và cách ứng dụng kết nối cache trong subnet an toàn. |
| [Lab 35 - Data lake baseline trên S3](Hands-on%20Labs/lab-35-s3-datalake-baseline.md) | [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/) | Ghi chú mô hình data lake căn bản trên S3 để so sánh với RDS/Redshift/ElastiCache. |

## Gắn với Worklog

Module này được dùng chính trong **Tuần 3** và tiếp tục hỗ trợ các phần kiến trúc, vận hành hoặc cleanup ở những tuần sau.
