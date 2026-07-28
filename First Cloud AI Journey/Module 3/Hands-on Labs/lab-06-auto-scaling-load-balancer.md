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

## Ghi chú kỹ thuật

ALB health check và desired capacity là hai điểm cần kiểm tra trước khi kết luận ứng dụng lỗi. Target group, port mapping và Security Group phải khớp với cấu hình instance.
