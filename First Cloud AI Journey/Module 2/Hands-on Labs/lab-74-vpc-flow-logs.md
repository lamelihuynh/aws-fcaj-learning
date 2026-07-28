# Lab 74 - VPC Flow Logs cho quan sát lưu lượng mạng

## Tài liệu tham khảo

- Workshop: [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)

## Mục tiêu

Bật VPC Flow Logs và gửi log về CloudWatch Logs hoặc S3 để phục vụ phân tích mạng.

## Luồng thực hành

1. Chuẩn bị log group hoặc bucket đích.
2. Tạo Flow Log với filter phù hợp cho ENI/Subnet/VPC.
3. Tạo lưu lượng kiểm thử tới EC2 hoặc endpoint.
4. Đọc log để xác định ACCEPT/REJECT, source, destination và port.
5. Ghi lại truy vấn hoặc ảnh minh chứng dùng cho phần observability.

## Kiểm chứng

- Flow log xuất hiện ở đúng đích.
- Có thể phân biệt log bị chặn bởi rule mạng với lỗi ứng dụng.
- Có cleanup log group/bucket nếu chỉ dùng cho lab.

## Ghi chú kỹ thuật

VPC Flow Logs cung cấp bằng chứng ACCEPT/REJECT cho lưu lượng mạng. Dữ liệu này hữu ích khi cần phân biệt lỗi route, rule mạng và lỗi tầng ứng dụng.
