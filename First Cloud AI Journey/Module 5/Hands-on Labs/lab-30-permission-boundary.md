# Lab 30 - IAM Permission Boundary

## Nguồn tham khảo chính

- Workshop gốc: [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành giới hạn quyền tối đa của IAM user/role bằng permission boundary.

## Luồng thực hành đã viết lại

1. Tạo policy boundary chỉ cho phép nhóm action cần thiết.
2. Gắn boundary cho user/role lab.
3. Cố gắng attach policy vượt phạm vi và quan sát kết quả bị chặn.
4. So sánh permission policy cho phép với boundary giới hạn trần quyền.
5. Ghi lại tình huống dùng boundary khi delegate quyền tạo role/user.

## Kiểm chứng cần có

- Hành động vượt boundary bị deny.
- Giải thích được boundary không tự cấp quyền nếu permission policy không allow.
- Xóa user/role/policy lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
