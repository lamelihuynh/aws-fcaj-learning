# Lab 61 - Amazon ElastiCache Redis

## Tài liệu tham khảo

- Workshop: [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/)

## Mục tiêu

Hiểu Redis cache trên AWS và cách ứng dụng kết nối cache trong subnet an toàn.

## Luồng thực hành

1. Chuẩn bị subnet group và security group cho cache.
2. Tạo Redis cluster nhỏ hoặc serverless cache theo workshop/phạm vi tài khoản.
3. Kết nối từ client trong VPC, thử set/get key.
4. Ghi lại latency/use case: session cache, read-through cache, pub/sub.
5. Cleanup cache cluster để tránh chi phí chạy liên tục.

## Kiểm chứng

- Client trong VPC set/get dữ liệu thành công.
- Redis không public internet.
- Có ghi chú khi nào không nên dùng cache.

## Ghi chú kỹ thuật

Redis cache nên được dùng khi có nhu cầu giảm độ trễ hoặc giảm tải đọc. Cache không thay thế database chính và cần được đặt trong network private.
