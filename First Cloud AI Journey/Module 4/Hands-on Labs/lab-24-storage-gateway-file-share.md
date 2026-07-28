# Lab 24 - Storage Gateway File Gateway

## Tài liệu tham khảo

- Workshop: [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/)

## Mục tiêu

Hiểu cách File Gateway kết nối môi trường giống on-premises với S3 thông qua file share.

## Luồng thực hành

1. Chuẩn bị S3 bucket đích và EC2/appliance theo workshop.
2. Tạo gateway và kích hoạt trong console.
3. Tạo file share, gắn IAM role/policy cho bucket.
4. Mount file share từ máy kiểm thử và tạo file test.
5. Kiểm tra object tương ứng xuất hiện trong S3.

## Kiểm chứng

- File tạo qua share đồng bộ về S3.
- Role chỉ có quyền trên bucket lab.
- Xóa gateway, file share, EC2 và bucket object sau lab.

## Ghi chú

Storage Gateway hơi dài bước chuẩn bị, nên mình giữ lại flow ngắn để nhớ mối liên hệ giữa file share và S3 bucket phía sau.
