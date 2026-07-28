# Lab 09 - Checklist kiến trúc DevSecOps cuối kỳ

## Nguồn tham khảo chính

- Workshop gốc: [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Tổng hợp pipeline container, security gate, report artifact, observability và cleanup thành checklist workshop cá nhân.

## Luồng thực hành đã viết lại

1. Vẽ lại flow từ commit đến image, ECR, ECS Fargate và ALB.
2. Thêm security scan/report upload vào S3 và Lambda tổng hợp finding.
3. Gắn CloudWatch dashboard/alarm cho runtime và pipeline.
4. Đánh dấu quyền IAM giữa Jenkins/ECR/ECS/S3/Lambda theo least privilege.
5. Kiểm tra từng bước có expected result và cleanup.

## Kiểm chứng cần có

- Diagram không có mũi tên mơ hồ.
- Mỗi service có vai trò, permission và log/evidence rõ ràng.
- Checklist đủ dùng cho báo cáo và demo.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
