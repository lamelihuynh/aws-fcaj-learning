# Tuần 02 - EC2, storage, backup và DR

## Trọng tâm

Tuần này ghi lại các nội dung đã học, lab đã tham khảo và workshop cần đối chiếu khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 22/06/2026 | Launch Linux/Windows EC2, kiểm tra SSH/RDP, security group, user data và lỗi kết nối phổ biến. | [Module 3](../First%20Cloud%20AI%20Journey/Module%203/module-03-ly-thuyet-ec2-ebs-auto-scaling.md)<br>[Lab 04 EC2](../First%20Cloud%20AI%20Journey/Module%203/Hands-on%20Labs/lab-04-ec2-linux-windows-operations.md) | [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/) |
| Thứ 3 | 23/06/2026 | Thực hành EBS, snapshot, AMI và mô hình Auto Scaling Group sau ALB. | [Module 3](../First%20Cloud%20AI%20Journey/Module%203/module-03-ly-thuyet-ec2-ebs-auto-scaling.md)<br>[Lab 06 ASG](../First%20Cloud%20AI%20Journey/Module%203/Hands-on%20Labs/lab-06-auto-scaling-load-balancer.md) | [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/) |
| Thứ 4 | 24/06/2026 | Tạo S3 bucket, upload object, versioning, lifecycle và mô hình static website/CloudFront. | [Module 4](../First%20Cloud%20AI%20Journey/Module%204/module-04-ly-thuyet-s3-storage-backup-dr.md)<br>[Lab 57 S3](../First%20Cloud%20AI%20Journey/Module%204/Hands-on%20Labs/lab-57-s3-cloudfront-static-website.md) | [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/) |
| Thứ 5 | 25/06/2026 | So sánh EFS, FSx và Storage Gateway; ghi lại luồng File Gateway và SMB share. | [Module 4](../First%20Cloud%20AI%20Journey/Module%204/module-04-ly-thuyet-s3-storage-backup-dr.md)<br>[Lab 24 Storage Gateway](../First%20Cloud%20AI%20Journey/Module%204/Hands-on%20Labs/lab-24-storage-gateway-file-share.md)<br>[Lab 25 FSx](../First%20Cloud%20AI%20Journey/Module%204/Hands-on%20Labs/lab-25-fsx-windows-file-share.md) | [000024 - Triển khai AWS Storage Gateway](https://000024.awsstudygroup.com/vi/)<br>[000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/) |
| Thứ 6 | 26/06/2026 | Lập bảng RTO/RPO, backup plan, retention và cleanup cho tài nguyên compute/storage. | [Module 4](../First%20Cloud%20AI%20Journey/Module%204/module-04-ly-thuyet-s3-storage-backup-dr.md)<br>[Lab 13 AWS Backup](../First%20Cloud%20AI%20Journey/Module%204/Hands-on%20Labs/lab-13-aws-backup-plan.md) | [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/)<br>[000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/) |

## Kết quả chính

- EC2, EBS, AMI và Auto Scaling cung cấp nền tảng compute truyền thống trước khi chuyển sang container hoặc serverless.
- Storage cần được chọn theo cách dữ liệu được sử dụng: object, file share, hybrid access hoặc backup/restore.
