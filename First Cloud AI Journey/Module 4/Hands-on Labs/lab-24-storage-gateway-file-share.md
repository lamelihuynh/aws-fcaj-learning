# Lab 24 - Storage Gateway File Gateway

## Nguồn tham khảo chính

- Workshop gốc: [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Hiểu cách File Gateway kết nối môi trường giống on-premises với S3 thông qua file share.

## Luồng thực hành đã viết lại

1. Chuẩn bị S3 bucket đích và EC2/appliance theo workshop.
2. Tạo gateway và kích hoạt trong console.
3. Tạo file share, gắn IAM role/policy cho bucket.
4. Mount file share từ máy kiểm thử và tạo file test.
5. Kiểm tra object tương ứng xuất hiện trong S3.

## Kiểm chứng cần có

- File tạo qua share đồng bộ về S3.
- Role chỉ có quyền trên bucket lab.
- Xóa gateway, file share, EC2 và bucket object sau lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
