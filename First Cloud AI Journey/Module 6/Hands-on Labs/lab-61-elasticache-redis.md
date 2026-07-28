# Lab 61 - Amazon ElastiCache Redis

## Nguồn tham khảo chính

- Workshop gốc: [000061 - Amazon ElastiCache Redis](https://000061.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Hiểu Redis cache trên AWS và cách ứng dụng kết nối cache trong subnet an toàn.

## Luồng thực hành đã viết lại

1. Chuẩn bị subnet group và security group cho cache.
2. Tạo Redis cluster nhỏ hoặc serverless cache theo workshop/phạm vi tài khoản.
3. Kết nối từ client trong VPC, thử set/get key.
4. Ghi lại latency/use case: session cache, read-through cache, pub/sub.
5. Cleanup cache cluster để tránh chi phí chạy liên tục.

## Kiểm chứng cần có

- Client trong VPC set/get dữ liệu thành công.
- Redis không public internet.
- Có ghi chú khi nào không nên dùng cache.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
