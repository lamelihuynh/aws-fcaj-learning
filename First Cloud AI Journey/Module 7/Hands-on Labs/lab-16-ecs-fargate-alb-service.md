# Lab 16 - ECS Fargate service phía sau Application Load Balancer

## Nguồn tham khảo chính

- Workshop gốc: [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Triển khai container trên ECS/Fargate với task definition, service, target group và ALB.

## Luồng thực hành đã viết lại

1. Chuẩn bị VPC/subnet/security group cho ALB và task.
2. Tạo ECS cluster, task definition và task execution role.
3. Tạo target group/ALB và service chạy Fargate.
4. Kiểm tra health check, log driver và rolling deployment.
5. Ghi lại điểm khác ECS service với EC2/ASG.

## Kiểm chứng cần có

- ALB route được đến task healthy.
- Task log xuất hiện ở CloudWatch Logs.
- Cleanup service, task, ALB và NAT Gateway nếu có.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
