# Lab 04 - EC2 Linux/Windows, EBS Snapshot và AMI

## Tài liệu tham khảo

- Workshop: [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành khởi tạo, kết nối và vận hành EC2 cơ bản trên Linux/Windows theo workshop EC2.

## Luồng thực hành

1. Tạo VPC/Security Group phù hợp cho Linux hoặc Windows instance.
2. Launch EC2, kết nối bằng SSH/RDP hoặc Session Manager nếu có role.
3. Thử user data hoặc cài web service mẫu để kiểm tra instance hoạt động.
4. Tạo EBS snapshot và custom AMI để hiểu cơ chế sao lưu image.
5. Ghi lại các lỗi thường gặp: key pair, inbound rule, public IP, user/administrator password.

## Kiểm chứng

- Instance reachable đúng cách.
- Snapshot/AMI được tạo và đặt tên có tag cleanup.
- Security Group không mở rộng hơn nhu cầu lab.

## Ghi chú kỹ thuật

Các lỗi EC2 thường gặp gồm sai key pair, thiếu public IP, inbound rule chưa đúng hoặc dùng sai user khi SSH/RDP. Nội dung này là nền để so sánh EC2 tự quản lý với ECS Fargate.
