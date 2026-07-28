# Lab 96 - Secrets Manager với RDS và AWS Fargate

## Nguồn tham khảo chính

- Workshop gốc: [000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành tách secret khỏi image/source code và inject secret vào workload Fargate đúng quyền.

## Luồng thực hành đã viết lại

1. Tạo secret cho thông tin database hoặc biến nhạy cảm lab.
2. Gắn quyền đọc secret cho ECS task role ở phạm vi tối thiểu.
3. Cấu hình task definition tham chiếu secret.
4. Deploy service và kiểm tra app đọc secret thành công.
5. Ghi lại rotation/permission cần cân nhắc trong production.

## Kiểm chứng cần có

- Secret không xuất hiện trong Dockerfile/source code.
- Task role chỉ đọc secret cần thiết.
- Cleanup secret hoặc schedule deletion sau lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
