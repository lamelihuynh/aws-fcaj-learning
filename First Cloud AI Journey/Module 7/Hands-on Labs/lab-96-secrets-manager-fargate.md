# Lab 96 - Secrets Manager với RDS và AWS Fargate

## Tài liệu tham khảo

- Workshop: [000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành tách secret khỏi image/source code và inject secret vào workload Fargate đúng quyền.

## Luồng thực hành

1. Tạo secret cho thông tin database hoặc biến nhạy cảm lab.
2. Gắn quyền đọc secret cho ECS task role ở phạm vi tối thiểu.
3. Cấu hình task definition tham chiếu secret.
4. Deploy service và kiểm tra app đọc secret thành công.
5. Ghi lại rotation/permission cần cân nhắc trong production.

## Kiểm chứng

- Secret không xuất hiện trong Dockerfile/source code.
- Task role chỉ đọc secret cần thiết.
- Cleanup secret hoặc schedule deletion sau lab.

## Ghi chú kỹ thuật

Secrets Manager giúp tách secret khỏi image và source code. ECS task role cần được cấp quyền đọc đúng secret ở phạm vi tối thiểu.
