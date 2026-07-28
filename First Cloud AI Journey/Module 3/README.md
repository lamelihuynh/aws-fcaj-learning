# Module 03 - Amazon EC2, EBS, AMI và Auto Scaling

## Vai trò trong lộ trình

Module này tập trung vào compute truyền thống trên AWS: vòng đời EC2, kết nối Linux/Windows, EBS, snapshot, AMI, user data, Systems Manager, Launch Template, Load Balancer và Auto Scaling Group.

## Quy ước file trong module

- File bắt đầu bằng `module-` là ghi chú lý thuyết, dùng để giải thích khái niệm và cách áp dụng vào báo cáo.
- File trong thư mục `Hands-on Labs/` bắt đầu bằng `lab-` là minh chứng thực hành, bám theo workshop cộng đồng AWS Study Group nhưng được viết lại theo luồng học cá nhân.

## Nội dung chính

- [Ghi chú lý thuyết](module-03-ly-thuyet-ec2-ebs-auto-scaling.md)

## Hands-on Labs

| Lab | Workshop gốc | Mục tiêu cá nhân |
| --- | --- | --- |
| [Lab 04 - EC2 Linux/Windows, EBS Snapshot và AMI](Hands-on%20Labs/lab-04-ec2-linux-windows-operations.md) | [000004 - Giới thiệu về Amazon EC2](https://000004.awsstudygroup.com/vi/) | Thực hành khởi tạo, kết nối và vận hành EC2 cơ bản trên Linux/Windows theo workshop EC2. |
| [Lab 06 - Auto Scaling Group và Application Load Balancer](Hands-on%20Labs/lab-06-auto-scaling-load-balancer.md) | [000006 - FCJ Management với Auto Scaling Group](https://000006.awsstudygroup.com/vi/) | Thực hành Launch Template, Target Group, ALB và Auto Scaling Group để hiểu high availability cho web tier. |
| [Lab 31 - Systems Manager Session/Run Command](Hands-on%20Labs/lab-31-systems-manager-run-command.md) | [000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/) | Thực hành quản lý EC2 bằng Systems Manager để giảm phụ thuộc vào SSH/RDP mở public. |

## Liên kết với Worklog

Module này được dùng chính trong **Tuần 2**, và được tái sử dụng ở các tuần sau khi kiến trúc cần cùng nền tảng dịch vụ.
