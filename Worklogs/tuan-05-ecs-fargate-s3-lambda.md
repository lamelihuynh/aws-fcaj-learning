# Tuần 05 - ECS Fargate, S3 report bucket và Lambda aggregator

## Trọng tâm

Tuần này ghi lại các nội dung đã học, lab đã tham khảo và workshop cần đối chiếu khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 13/07/2026 | So sánh ECS Fargate với EC2/EKS và chọn runtime không phải quản lý worker node cho demo. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md)<br>[Lab 16 ECS Fargate](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-16-ecs-fargate-alb-service.md) | [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)<br>[000067 - Monolith to Microservices với Docker, ECS và Fargate](https://000067.awsstudygroup.com/vi/) |
| Thứ 3 | 14/07/2026 | Thiết kế task definition: image URI, CPU/memory, port, log, task execution role và task role. | [Lab 16 ECS Fargate](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-16-ecs-fargate-alb-service.md)<br>[Lab 96 Secrets](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-96-secrets-manager-fargate.md) | [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)<br>[000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/) |
| Thứ 4 | 15/07/2026 | Cấu hình ECS service networking với subnet, Security Group, Target Group và ALB health check. | [Lab 16 ECS Fargate](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-16-ecs-fargate-alb-service.md)<br>[Module 2](../First%20Cloud%20AI%20Journey/Module%202/module-02-ly-thuyet-vpc-networking-security.md) | [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)<br>[000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/) |
| Thứ 5 | 16/07/2026 | Tạo S3 report bucket cho scan output, bật encryption/versioning/lifecycle và policy least privilege. | [Module 4](../First%20Cloud%20AI%20Journey/Module%204/module-04-ly-thuyet-s3-storage-backup-dr.md)<br>[Lab 57 S3](../First%20Cloud%20AI%20Journey/Module%204/Hands-on%20Labs/lab-57-s3-cloudfront-static-website.md)<br>[Lab 33 KMS](../First%20Cloud%20AI%20Journey/Module%205/Hands-on%20Labs/lab-33-kms-s3-cloudtrail-athena.md) | [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/)<br>[000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)<br>[000069 - Thực hành bảo mật S3](https://000069.awsstudygroup.com/vi/) |
| Thứ 6 | 17/07/2026 | Thiết kế Lambda aggregator xử lý object report mới, tổng hợp finding và log ra CloudWatch. | [Module 8](../First%20Cloud%20AI%20Journey/Module%208/module-08-ly-thuyet-serverless-observability-iac.md)<br>[Lab 66 Lambda](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-66-lambda-api-gateway-sam.md) | [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/)<br>[000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/) |

## Kết quả chính

- ECS Fargate giảm nhu cầu quản lý node nhưng vẫn cần thiết kế kỹ subnet, Security Group, ALB và logging.
- S3 report bucket và Lambda aggregator tạo luồng xử lý security report rõ ràng cho workshop.
