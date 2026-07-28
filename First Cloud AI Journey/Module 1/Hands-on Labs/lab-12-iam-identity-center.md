# Lab 12 - IAM Identity Center và truy cập CLI tạm thời

## Nguồn tham khảo chính

- Workshop gốc: [000012 - AWS IAM Identity Center](https://000012.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành quản lý định danh tập trung bằng IAM Identity Center, permission set và credential tạm thời cho AWS CLI.

## Luồng thực hành đã viết lại

1. Kiểm tra AWS Organizations/IAM Identity Center và access portal.
2. Tạo user/group lab theo vai trò thực tập sinh hoặc operator.
3. Tạo permission set tối thiểu để quan sát tài nguyên cần học.
4. Gán group vào account qua permission set và đăng nhập access portal.
5. Lấy credential tạm thời từ portal, chạy lệnh CLI read-only và ghi lại thời gian hết hạn session.

## Kiểm chứng cần có

- User chỉ nhìn thấy account/role được gán.
- CLI hoạt động bằng credential tạm thời, không lưu access key dài hạn.
- Có bước gỡ assignment hoặc xóa user lab khi hoàn tất.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
