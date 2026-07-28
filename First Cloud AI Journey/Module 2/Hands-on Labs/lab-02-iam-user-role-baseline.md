# Lab 02 - IAM user, group, role và switch role

## Tài liệu tham khảo

- Workshop: [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/)

## Mục tiêu

Ôn lại IAM cốt lõi để đọc policy và hiểu sự khác nhau giữa user, group, role, trust policy và permission policy.

## Luồng thực hành

1. Tạo group có policy giới hạn theo phạm vi lab.
2. Tạo user lab và bật MFA nếu cần đăng nhập console.
3. Tạo role với trust policy rõ principal được assume role.
4. Thử switch role và quan sát permission khác nhau giữa user ban đầu và role được assume.

## Kiểm chứng

- Đọc được policy theo action/resource/condition.
- Biết khi nào dùng IAM user và khi nào dùng role.
- Không dùng root user cho lab hằng ngày.

## Ghi chú

Sau lab này mình thấy IAM dễ nhầm nhất ở chỗ role không giống user. Khi viết báo cáo, mình sẽ giải thích role theo hướng ai được assume role và role đó được phép làm gì.
