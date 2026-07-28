# Module 06 - RDS, cache và lựa chọn dịch vụ dữ liệu

## Mục đích

Module này dùng để phân loại workload dữ liệu: RDS/Aurora cho quan hệ, DynamoDB cho key-value/serverless, Redshift cho analytics, S3 data lake cho object scale lớn và ElastiCache Redis cho cache độ trễ thấp.

## Ghi chú lý thuyết chính

- Chọn RDS khi cần SQL, transaction và mô hình quan hệ rõ ràng; chọn Aurora khi cần khả năng sẵn sàng và scale cao hơn.
- Dùng Multi-AZ cho availability, Read Replica cho đọc nhiều và backup/snapshot cho bảo vệ dữ liệu.
- Dùng ElastiCache Redis để giảm tải đọc, session cache hoặc pub/sub nhẹ.
- Không ép một dịch vụ dữ liệu vào mọi bài toán; quyết định dựa vào truy vấn, consistency, latency, chi phí và vận hành.

## Cách dùng trong báo cáo

- Dùng trong Week 3 để so sánh dịch vụ dữ liệu.
- Dùng lại ở Week 4-5 khi workshop container cần RDS/Secrets Manager hoặc khi chọn S3 cho report artifact.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/)
- [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/)
- [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- Amazon RDS User Guide: https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html
- Amazon ElastiCache User Guide: https://docs.aws.amazon.com/AmazonElastiCache/latest/red-ug/WhatIs.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
