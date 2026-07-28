# Module 04 - Amazon S3, hybrid storage, backup và disaster recovery

## Phần này dùng để

Phần này gom các chủ đề lưu trữ: S3, CloudFront, versioning, lifecycle, encryption, Storage Gateway, FSx for Windows File Server, AWS Backup và tư duy RTO/RPO cho DR.

## File trong thư mục

- File `module-...md`: mình dùng để xem lại lý thuyết và ý chính.
- Thư mục `Hands-on Labs/`: mình để các bước thực hành, phần kiểm chứng và ghi chú cleanup.

## Ghi chú chính

- [Ghi chú lý thuyết](module-04-ly-thuyet-s3-storage-backup-dr.md)

## Hands-on Labs

| Lab | Workshop | Mục tiêu |
| --- | --- | --- |
| [Lab 57 - S3, static website và CloudFront](Hands-on%20Labs/lab-57-s3-cloudfront-static-website.md) | [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/) | Thực hành S3 bucket, upload object, versioning, static hosting và phân phối qua CloudFront theo hướng an toàn hơn. |
| [Lab 24 - Storage Gateway File Gateway](Hands-on%20Labs/lab-24-storage-gateway-file-share.md) | [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/) | Hiểu cách File Gateway kết nối môi trường giống on-premises với S3 thông qua file share. |
| [Lab 25 - FSx for Windows File Server](Hands-on%20Labs/lab-25-fsx-windows-file-share.md) | [000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/) | Thực hành file share Windows/SMB được quản lý và hiểu nhu cầu Active Directory/domain-aware workload. |
| [Lab 13 - AWS Backup plan và kiểm thử restore](Hands-on%20Labs/lab-13-aws-backup-plan.md) | [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/) | Tạo kế hoạch backup tập trung cho tài nguyên AWS và hiểu quan hệ giữa backup plan, vault, retention và restore test. |

## Gắn với Worklog

Mình dùng phần này nhiều nhất ở **Tuần 2**. Một vài ý sẽ quay lại ở các tuần sau, nhất là khi ráp kiến trúc cuối kỳ.
