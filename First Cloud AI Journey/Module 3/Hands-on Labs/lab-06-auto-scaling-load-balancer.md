# Lab 06 - Auto Scaling Group và Application Load Balancer

## Nguồn tham khảo chính

- Workshop gốc: [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành Launch Template, Target Group, ALB và Auto Scaling Group để hiểu high availability cho web tier.

## Luồng thực hành đã viết lại

1. Chuẩn bị VPC nhiều AZ và security group cho ALB/instance.
2. Tạo Launch Template từ AMI hoặc cấu hình EC2 đã kiểm thử.
3. Tạo Target Group và ALB để health check web tier.
4. Tạo Auto Scaling Group gắn target group và kiểm tra scale/replace instance.
5. Ghi lại khác biệt manual, scheduled, dynamic hoặc predictive scaling ở mức khái niệm.

## Kiểm chứng cần có

- ALB trả response từ instance healthy.
- ASG thay instance lỗi hoặc duy trì desired capacity.
- Có cleanup ALB, target group, ASG, launch template và instance.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
