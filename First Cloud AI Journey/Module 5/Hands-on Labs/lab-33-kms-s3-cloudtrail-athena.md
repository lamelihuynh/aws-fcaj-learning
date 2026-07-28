# Lab 33 - KMS, S3 encryption, CloudTrail và Athena

## Tài liệu tham khảo

- Workshop: [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)

## Mục tiêu

Hiểu encryption at rest bằng KMS và cách audit hành vi truy cập qua CloudTrail/Athena.

## Luồng thực hành

1. Tạo hoặc chọn KMS key dùng cho S3 lab.
2. Cấu hình bucket/object encryption bằng SSE-KMS.
3. Bật CloudTrail hoặc dùng trail sẵn có để ghi sự kiện KMS/S3.
4. Truy vấn log bằng Athena theo thời gian, principal hoặc action.
5. Ghi lại điểm cần chú ý về key policy, IAM policy và chi phí log/query.

## Kiểm chứng

- Object được mã hóa bằng KMS key mong muốn.
- Có sự kiện audit khi truy cập hoặc dùng key.
- Cleanup bucket object, Athena output và key nếu là key lab.

## Ghi chú kỹ thuật

Lab này liên kết mã hóa KMS, dữ liệu S3 và audit log qua CloudTrail/Athena. Key policy và IAM policy cần được kiểm tra cùng lúc khi gặp lỗi AccessDenied.
