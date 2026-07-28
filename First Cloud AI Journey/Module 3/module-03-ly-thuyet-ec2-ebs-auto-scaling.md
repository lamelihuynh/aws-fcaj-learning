# Module 03 - Amazon EC2, EBS, AMI và Auto Scaling

## Mình học phần này để làm gì

Phần này tập trung vào compute truyền thống trên AWS: vòng đời EC2, kết nối Linux/Windows, EBS, snapshot, AMI, user data, Systems Manager, Launch Template, Load Balancer và Auto Scaling Group.

## Ý mình cần nhớ

- Hiểu instance lifecycle, key pair, security group, IMDS và các lỗi kết nối SSH/RDP phổ biến.
- So sánh EBS, instance store, snapshot, AMI và cách chuẩn hóa image cho triển khai lặp lại.
- Dùng Launch Template, Target Group, ALB và Auto Scaling Group để tăng tính sẵn sàng cho web tier.
- Ưu tiên Systems Manager Session Manager/Run Command khi cần thao tác vận hành an toàn hơn mở port quản trị.

## Dùng lại trong báo cáo

- Dùng trong Week 2 cho phần compute và DR cơ bản.
- Dùng lại ở Week 4-5 khi so sánh vì sao dự án cuối kỳ chọn ECS Fargate thay vì tự quản lý EC2 worker.

## Workshop mình tham khảo

- [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/)
- [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/)
- [000011 - Làm quen với AWS CLI](https://000011.awsstudygroup.com/vi/)
- [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)

## Tài liệu AWS

- Amazon EC2 User Guide: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
- AWS Systems Manager User Guide: https://docs.aws.amazon.com/systems-manager/latest/userguide/what-is-systems-manager.html

## Tự nhắc

- Khi đưa vào báo cáo, mình cần gắn khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Nếu nhắc tới dịch vụ này, mình nên nói thêm một rủi ro hoặc lỗi cấu hình dễ gặp.
