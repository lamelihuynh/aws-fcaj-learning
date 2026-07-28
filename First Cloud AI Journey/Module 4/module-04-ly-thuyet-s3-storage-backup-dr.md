# Module 04 - Amazon S3, hybrid storage, backup và disaster recovery

## Mục tiêu kỹ thuật

Phần này gom các chủ đề lưu trữ: S3, CloudFront, versioning, lifecycle, encryption, Storage Gateway, FSx for Windows File Server, AWS Backup và tư duy RTO/RPO cho DR.

## Nội dung chính

- Cấu hình S3 an toàn: Block Public Access, bucket policy tối thiểu, encryption, versioning và lifecycle.
- Dùng CloudFront cho phân phối nội dung thay vì mở public object không kiểm soát.
- Phân biệt Storage Gateway cho kết nối hybrid với FSx cho file share Windows/SMB.
- Dùng AWS Backup để gom backup plan, retention, notification và kiểm thử restore.

## Ứng dụng trong báo cáo

- Dùng trong Week 2 cho storage và DR.
- Dùng lại ở Week 5 khi thiết kế S3 report bucket cho security scan output.

## Workshop tham khảo

- [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/)
- [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/)
- [000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/)
- [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/)
- [000069 - Thực hành bảo mật S3](https://000069.awsstudygroup.com/vi/)
- [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/)

## Tài liệu AWS

- Amazon S3 User Guide: https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html
- AWS Backup Developer Guide: https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html

## Ghi chú kỹ thuật

- Khi đưa vào báo cáo, cần liên kết khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Với mỗi dịch vụ, nên nêu thêm rủi ro vận hành, lỗi cấu hình thường gặp hoặc điểm kiểm chứng.
