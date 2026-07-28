# Lab 16 - ECS Fargate service phía sau Application Load Balancer

## Tài liệu tham khảo

- Workshop: [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)

## Mục tiêu

Triển khai container trên ECS/Fargate với task definition, service, target group và ALB.

## Luồng thực hành

1. Chuẩn bị VPC/subnet/security group cho ALB và task.
2. Tạo ECS cluster, task definition và task execution role.
3. Tạo target group/ALB và service chạy Fargate.
4. Kiểm tra health check, log driver và rolling deployment.
5. Ghi lại điểm khác ECS service với EC2/ASG.

## Kiểm chứng

- ALB route được đến task healthy.
- Task log xuất hiện ở CloudWatch Logs.
- Cleanup service, task, ALB và NAT Gateway nếu có.

## Ghi chú

ECS Fargate có nhiều mảnh nhỏ nên mình ghi theo đường đi của request: ALB, target group, service, task và log. Khi lỗi health check thì đọc theo thứ tự đó sẽ dễ hơn.
