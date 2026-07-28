# Module 03 - Amazon EC2, EBS, AMI và Auto Scaling

## Mục đích

Module này tập trung vào compute truyền thống trên AWS: vòng đời EC2, kết nối Linux/Windows, EBS, snapshot, AMI, user data, Systems Manager, Launch Template, Load Balancer và Auto Scaling Group.

## Ghi chú lý thuyết chính

- Hiểu instance lifecycle, key pair, security group, IMDS và các lỗi kết nối SSH/RDP phổ biến.
- So sánh EBS, instance store, snapshot, AMI và cách chuẩn hóa image cho triển khai lặp lại.
- Dùng Launch Template, Target Group, ALB và Auto Scaling Group để tăng tính sẵn sàng cho web tier.
- Ưu tiên Systems Manager Session Manager/Run Command khi cần thao tác vận hành an toàn hơn mở port quản trị.

## Cách dùng trong báo cáo

- Dùng trong Week 2 cho phần compute và DR cơ bản.
- Dùng lại ở Week 4-5 khi so sánh vì sao dự án cuối kỳ chọn ECS Fargate thay vì tự quản lý EC2 worker.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/)
- [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/)
- [000011 - Làm quen với AWS CLI](https://000011.awsstudygroup.com/vi/)
- [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- Amazon EC2 User Guide: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html
- AWS Systems Manager User Guide: https://docs.aws.amazon.com/systems-manager/latest/userguide/what-is-systems-manager.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
