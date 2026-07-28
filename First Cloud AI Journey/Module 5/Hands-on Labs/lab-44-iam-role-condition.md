# Lab 44 - IAM Role và Condition

## Nguồn tham khảo chính

- Workshop gốc: [000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành assume role có điều kiện theo IP hoặc thời gian để hiểu policy condition trong IAM.

## Luồng thực hành đã viết lại

1. Tạo role và trust policy cho principal lab.
2. Thêm condition theo IP/time hoặc điều kiện phù hợp workshop.
3. Thử assume role trong điều kiện hợp lệ và không hợp lệ.
4. Ghi lại thông báo AccessDenied và cách đọc policy evaluation.
5. So sánh condition trong trust policy và permission policy.

## Kiểm chứng cần có

- Assume role chỉ thành công khi condition đúng.
- Giải thích được vì sao deny xảy ra.
- Cleanup role/policy/user lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
