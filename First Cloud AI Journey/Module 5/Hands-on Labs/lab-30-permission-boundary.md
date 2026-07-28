# Lab 30 - IAM Permission Boundary

## Tài liệu tham khảo

- Workshop: [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành giới hạn quyền tối đa của IAM user/role bằng permission boundary.

## Luồng thực hành

1. Tạo policy boundary chỉ cho phép nhóm action cần thiết.
2. Gắn boundary cho user/role lab.
3. Cố gắng attach policy vượt phạm vi và quan sát kết quả bị chặn.
4. So sánh permission policy cho phép với boundary giới hạn trần quyền.
5. Ghi lại tình huống dùng boundary khi delegate quyền tạo role/user.

## Kiểm chứng

- Hành động vượt boundary bị deny.
- Giải thích được boundary không tự cấp quyền nếu permission policy không allow.
- Xóa user/role/policy lab.

## Ghi chú

Permission boundary ban đầu hơi dễ nhầm với policy cấp quyền. Mình ghi lại điểm chính: boundary chỉ giới hạn trần quyền, không tự cấp quyền.
