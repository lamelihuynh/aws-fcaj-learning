# Module 06 - RDS, cache và lựa chọn dịch vụ dữ liệu

## Mục tiêu kỹ thuật

Phần này dùng để phân loại workload dữ liệu: RDS/Aurora cho quan hệ, DynamoDB cho key-value/serverless, Redshift cho analytics, S3 data lake cho object scale lớn và ElastiCache Redis cho cache độ trễ thấp.

## Nội dung chính

- Chọn RDS khi cần SQL, transaction và mô hình quan hệ rõ ràng; chọn Aurora khi cần khả năng sẵn sàng và scale cao hơn.
- Dùng Multi-AZ cho availability, Read Replica cho đọc nhiều và backup/snapshot cho bảo vệ dữ liệu.
- Dùng ElastiCache Redis để giảm tải đọc, session cache hoặc pub/sub nhẹ.
- Không ép một dịch vụ dữ liệu vào mọi bài toán; quyết định dựa vào truy vấn, consistency, latency, chi phí và vận hành.

## Ứng dụng trong báo cáo

- Dùng trong Week 3 để so sánh dịch vụ dữ liệu.
- Dùng lại ở Week 4-5 khi workshop container cần RDS/Secrets Manager hoặc khi chọn S3 cho report artifact.

## Workshop tham khảo

- [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/)
- [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/)
- [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/)

## Tài liệu AWS

- Amazon RDS User Guide: https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html
- Amazon ElastiCache User Guide: https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/WhatIs.html

## Ghi chú kỹ thuật

- Khi đưa vào báo cáo, cần liên kết khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Với mỗi dịch vụ, nên nêu thêm rủi ro vận hành, lỗi cấu hình thường gặp hoặc điểm kiểm chứng.
