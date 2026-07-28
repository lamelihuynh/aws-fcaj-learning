# Lab 05 - Amazon RDS, Multi-AZ và backup cơ bản

## Nguồn tham khảo chính

- Workshop gốc: [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Tạo RDS instance trong VPC, kết nối từ EC2/app mẫu và hiểu backup/restore cơ bản.

## Luồng thực hành đã viết lại

1. Chuẩn bị VPC, DB subnet group và security group riêng cho EC2/RDS.
2. Tạo RDS instance nhỏ theo phạm vi lab.
3. Kết nối từ EC2 hoặc app mẫu, không mở DB public nếu không cần.
4. Kiểm tra automated backup hoặc snapshot thủ công.
5. Ghi lại khác biệt Multi-AZ, Read Replica và backup snapshot.

## Kiểm chứng cần có

- App/EC2 kết nối được database qua endpoint.
- Security Group chỉ cho phép source hợp lệ.
- Có snapshot/backup minh chứng và cleanup DB sau lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
