# Lab 06 - Auto Scaling Group và Application Load Balancer

## Tài liệu tham khảo

- Workshop: [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành Launch Template, Target Group, ALB và Auto Scaling Group để hiểu high availability cho web tier.

## Luồng thực hành

1. Chuẩn bị VPC nhiều AZ và security group cho ALB/instance.
2. Tạo Launch Template từ AMI hoặc cấu hình EC2 đã kiểm thử.
3. Tạo Target Group và ALB để health check web tier.
4. Tạo Auto Scaling Group gắn target group và kiểm tra scale/replace instance.
5. Ghi lại khác biệt manual, scheduled, dynamic hoặc predictive scaling ở mức khái niệm.

## Kiểm chứng

- ALB trả response từ instance healthy.
- ASG thay instance lỗi hoặc duy trì desired capacity.
- Có cleanup ALB, target group, ASG, launch template và instance.

## Ghi chú

Ở lab này mình chú ý nhiều tới health check và desired capacity. Nếu ALB báo unhealthy thì chưa vội kết luận app lỗi, phải kiểm tra target group, port mapping và security group.
