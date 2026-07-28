# Lab 44 - IAM Role và Condition

## Tài liệu tham khảo

- Workshop: [000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành assume role có điều kiện theo IP hoặc thời gian để hiểu policy condition trong IAM.

## Luồng thực hành

1. Tạo role và trust policy cho principal lab.
2. Thêm condition theo IP/time hoặc điều kiện phù hợp workshop.
3. Thử assume role trong điều kiện hợp lệ và không hợp lệ.
4. Ghi lại thông báo AccessDenied và cách đọc policy evaluation.
5. So sánh condition trong trust policy và permission policy.

## Kiểm chứng

- Assume role chỉ thành công khi condition đúng.
- Giải thích được vì sao deny xảy ra.
- Cleanup role/policy/user lab.

## Ghi chú kỹ thuật

Policy condition có thể giới hạn assume role theo IP, thời gian hoặc context key. Khi gặp AccessDenied, cần kiểm tra cả action/resource lẫn condition trong policy evaluation.
