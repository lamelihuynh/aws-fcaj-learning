# Module 04 - Amazon S3, hybrid storage, backup và disaster recovery

## Mục đích

Module này gom các chủ đề lưu trữ: S3, CloudFront, versioning, lifecycle, encryption, Storage Gateway, FSx for Windows File Server, AWS Backup và tư duy RTO/RPO cho DR.

## Ghi chú lý thuyết chính

- Cấu hình S3 an toàn: Block Public Access, bucket policy tối thiểu, encryption, versioning và lifecycle.
- Dùng CloudFront cho phân phối nội dung thay vì mở public object không kiểm soát.
- Phân biệt Storage Gateway cho kết nối hybrid với FSx cho file share Windows/SMB.
- Dùng AWS Backup để gom backup plan, retention, notification và kiểm thử restore.

## Cách dùng trong báo cáo

- Dùng trong Week 2 cho storage và DR.
- Dùng lại ở Week 5 khi thiết kế S3 report bucket cho security scan output.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/)
- [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/)
- [000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/)
- [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/)
- [000069 - Thực hành bảo mật S3](https://000069.awsstudygroup.com/vi/)
- [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- Amazon S3 User Guide: https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html
- AWS Backup Developer Guide: https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
