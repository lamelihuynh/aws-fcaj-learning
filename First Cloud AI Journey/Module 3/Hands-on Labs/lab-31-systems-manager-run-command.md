# Lab 31 - Systems Manager Session/Run Command

## Nguồn tham khảo chính

- Workshop gốc: [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành quản lý EC2 bằng Systems Manager để giảm phụ thuộc vào SSH/RDP mở public.

## Luồng thực hành đã viết lại

1. Gắn IAM role có quyền Systems Manager cho EC2.
2. Kiểm tra SSM Agent và trạng thái managed instance.
3. Mở Session Manager hoặc chạy Run Command đơn giản.
4. Ghi lại lợi ích về audit trail và giảm inbound admin port.
5. Xác định điều kiện cần: outbound network, endpoint hoặc internet/NAT, IAM role đúng.

## Kiểm chứng cần có

- Instance xuất hiện trong Systems Manager.
- Chạy được command kiểm thử.
- Biết cách troubleshoot khi managed instance không online.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
