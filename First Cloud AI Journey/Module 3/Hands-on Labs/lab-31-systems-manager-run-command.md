# Lab 31 - Systems Manager Session/Run Command

## Tài liệu tham khảo

- Workshop: [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành quản lý EC2 bằng Systems Manager để giảm phụ thuộc vào SSH/RDP mở public.

## Luồng thực hành

1. Gắn IAM role có quyền Systems Manager cho EC2.
2. Kiểm tra SSM Agent và trạng thái managed instance.
3. Mở Session Manager hoặc chạy Run Command đơn giản.
4. Ghi lại lợi ích về audit trail và giảm inbound admin port.
5. Xác định điều kiện cần: outbound network, endpoint hoặc internet/NAT, IAM role đúng.

## Kiểm chứng

- Instance xuất hiện trong Systems Manager.
- Chạy được command kiểm thử.
- Biết cách troubleshoot khi managed instance không online.

## Ghi chú kỹ thuật

Systems Manager giúp giảm nhu cầu mở SSH/RDP trực tiếp ra internet. Điều kiện chính gồm IAM role đúng, SSM Agent hoạt động và network path tới Systems Manager endpoint.
