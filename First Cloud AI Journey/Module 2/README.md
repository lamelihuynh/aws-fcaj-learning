# Module 02 - Amazon VPC, routing và bảo mật mạng

## Vai trò trong lộ trình

Module này gom phần mạng nền tảng: CIDR, subnet public/private, route table, Internet Gateway, NAT Gateway, Security Group, NACL, VPC Flow Logs và các mô hình kết nối giữa VPC hoặc hybrid.

## Quy ước file trong module

- File bắt đầu bằng `module-` là ghi chú lý thuyết, dùng để giải thích khái niệm và cách áp dụng vào báo cáo.
- File trong thư mục `Hands-on Labs/` bắt đầu bằng `lab-` là minh chứng thực hành, bám theo workshop cộng đồng AWS Study Group nhưng được viết lại theo luồng học cá nhân.

## Nội dung chính

- [Ghi chú lý thuyết](module-02-ly-thuyet-vpc-networking-security.md)

## Hands-on Labs

| Lab | Workshop gốc | Mục tiêu cá nhân |
| --- | --- | --- |
| [Lab 02 - IAM user, group, role và switch role](Hands-on%20Labs/lab-02-iam-user-role-baseline.md) | [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/) | Ôn lại IAM cốt lõi để đọc policy và hiểu sự khác nhau giữa user, group, role, trust policy và permission policy. |
| [Lab 03 - VPC public/private subnet và kết nối mạng](Hands-on%20Labs/lab-03-vpc-site-to-site-vpn.md) | [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/) | Thiết kế VPC cơ bản và hiểu routing, Internet Gateway, NAT Gateway, Security Group, NACL và mô hình VPN theo workshop. |
| [Lab 74 - VPC Flow Logs cho quan sát lưu lượng mạng](Hands-on%20Labs/lab-74-vpc-flow-logs.md) | [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/) | Bật VPC Flow Logs và gửi log về CloudWatch Logs hoặc S3 để phục vụ phân tích mạng. |

## Liên kết với Worklog

Module này được dùng chính trong **Tuần 1**, và được tái sử dụng ở các tuần sau khi kiến trúc cần cùng nền tảng dịch vụ.
