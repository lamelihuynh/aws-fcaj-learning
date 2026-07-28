# Lab 05 - Amazon RDS, Multi-AZ và backup cơ bản

## Tài liệu tham khảo

- Workshop: [000005 - Bắt đầu với Amazon RDS](https://000005.awsstudygroup.com/vi/)

## Mục tiêu

Tạo RDS instance trong VPC, kết nối từ EC2/app mẫu và hiểu backup/restore cơ bản.

## Luồng thực hành

1. Chuẩn bị VPC, DB subnet group và security group riêng cho EC2/RDS.
2. Tạo RDS instance nhỏ theo phạm vi lab.
3. Kết nối từ EC2 hoặc app mẫu, không mở DB public nếu không cần.
4. Kiểm tra automated backup hoặc snapshot thủ công.
5. Ghi lại khác biệt Multi-AZ, Read Replica và backup snapshot.

## Kiểm chứng

- App/EC2 kết nối được database qua endpoint.
- Security Group chỉ cho phép source hợp lệ.
- Có snapshot/backup minh chứng và cleanup DB sau lab.

## Ghi chú kỹ thuật

RDS cần được đặt trong subnet phù hợp, giới hạn inbound từ nguồn hợp lệ và có backup/restore strategy rõ ràng. Không nên mở database public nếu không có yêu cầu cụ thể.
