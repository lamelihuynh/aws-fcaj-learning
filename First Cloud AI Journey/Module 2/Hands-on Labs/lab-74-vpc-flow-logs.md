# Lab 74 - VPC Flow Logs cho quan sát lưu lượng mạng

## Nguồn tham khảo chính

- Workshop gốc: [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Bật VPC Flow Logs và gửi log về CloudWatch Logs hoặc S3 để phục vụ phân tích mạng.

## Luồng thực hành đã viết lại

1. Chuẩn bị log group hoặc bucket đích.
2. Tạo Flow Log với filter phù hợp cho ENI/Subnet/VPC.
3. Tạo lưu lượng kiểm thử tới EC2 hoặc endpoint.
4. Đọc log để xác định ACCEPT/REJECT, source, destination và port.
5. Ghi lại truy vấn hoặc ảnh minh chứng dùng cho phần observability.

## Kiểm chứng cần có

- Flow log xuất hiện ở đúng đích.
- Có thể phân biệt log bị chặn bởi rule mạng với lỗi ứng dụng.
- Có cleanup log group/bucket nếu chỉ dùng cho lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
