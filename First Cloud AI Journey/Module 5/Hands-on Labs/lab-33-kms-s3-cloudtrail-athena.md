# Lab 33 - KMS, S3 encryption, CloudTrail và Athena

## Nguồn tham khảo chính

- Workshop gốc: [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Hiểu encryption at rest bằng KMS và cách audit hành vi truy cập qua CloudTrail/Athena.

## Luồng thực hành đã viết lại

1. Tạo hoặc chọn KMS key dùng cho S3 lab.
2. Cấu hình bucket/object encryption bằng SSE-KMS.
3. Bật CloudTrail hoặc dùng trail sẵn có để ghi sự kiện KMS/S3.
4. Truy vấn log bằng Athena theo thời gian, principal hoặc action.
5. Ghi lại điểm cần chú ý về key policy, IAM policy và chi phí log/query.

## Kiểm chứng cần có

- Object được mã hóa bằng KMS key mong muốn.
- Có sự kiện audit khi truy cập hoặc dùng key.
- Cleanup bucket object, Athena output và key nếu là key lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
