# Lab 02 - IAM user, group, role và switch role

## Nguồn tham khảo chính

- Workshop gốc: [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Ôn lại IAM cốt lõi để đọc policy và hiểu sự khác nhau giữa user, group, role, trust policy và permission policy.

## Luồng thực hành đã viết lại

1. Tạo group có policy giới hạn theo phạm vi lab.
2. Tạo user lab và bật MFA nếu cần đăng nhập console.
3. Tạo role với trust policy rõ principal được assume role.
4. Thử switch role và quan sát permission khác nhau giữa user ban đầu và role được assume.

## Kiểm chứng cần có

- Đọc được policy theo action/resource/condition.
- Biết khi nào dùng IAM user và khi nào dùng role.
- Không dùng root user cho lab hằng ngày.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
