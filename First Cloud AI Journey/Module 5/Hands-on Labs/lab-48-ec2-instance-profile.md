# Lab 48 - EC2 Instance Profile truy cập S3

## Nguồn tham khảo chính

- Workshop gốc: [000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Cấp quyền cho ứng dụng trên EC2 truy cập dịch vụ AWS bằng IAM role thay vì nhúng access key.

## Luồng thực hành đã viết lại

1. Tạo S3 bucket/object test.
2. Tạo IAM role cho EC2 với policy tối thiểu.
3. Gắn instance profile vào EC2.
4. Từ EC2, dùng AWS CLI/SDK đọc object theo quyền role.
5. Gỡ bỏ access key khỏi code và ghi lại lý do role an toàn hơn.

## Kiểm chứng cần có

- EC2 truy cập S3 bằng role metadata credential.
- Không có credential dài hạn trong file cấu hình.
- Cleanup EC2, role, bucket object sau lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
