# Lab 48 - EC2 Instance Profile truy cập S3

## Tài liệu tham khảo

- Workshop: [000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/)

## Mục tiêu

Cấp quyền cho ứng dụng trên EC2 truy cập dịch vụ AWS bằng IAM role thay vì nhúng access key.

## Luồng thực hành

1. Tạo S3 bucket/object test.
2. Tạo IAM role cho EC2 với policy tối thiểu.
3. Gắn instance profile vào EC2.
4. Từ EC2, dùng AWS CLI/SDK đọc object theo quyền role.
5. Gỡ bỏ access key khỏi code và ghi lại lý do role an toàn hơn.

## Kiểm chứng

- EC2 truy cập S3 bằng role metadata credential.
- Không có credential dài hạn trong file cấu hình.
- Cleanup EC2, role, bucket object sau lab.

## Ghi chú kỹ thuật

Instance profile giúp ứng dụng trên EC2 truy cập dịch vụ AWS mà không cần hard-code access key. Policy của role vẫn phải được giới hạn theo nguyên tắc least privilege.
