# Lab 09 - Checklist kiến trúc DevSecOps cuối kỳ

## Tài liệu tham khảo

- Workshop: [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)

## Mục tiêu

Tổng hợp pipeline container, security gate, report artifact, observability và cleanup thành checklist workshop.

## Luồng thực hành

1. Vẽ lại flow từ commit đến image, ECR, ECS Fargate và ALB.
2. Thêm security scan/report upload vào S3 và Lambda tổng hợp finding.
3. Gắn CloudWatch dashboard/alarm cho runtime và pipeline.
4. Đánh dấu quyền IAM giữa Jenkins/ECR/ECS/S3/Lambda theo least privilege.
5. Kiểm tra từng bước có expected result và cleanup.

## Kiểm chứng

- Diagram không có mũi tên mơ hồ.
- Mỗi service có vai trò, permission và log/evidence rõ ràng.
- Checklist đủ dùng cho báo cáo và demo.

## Ghi chú kỹ thuật

Checklist kiến trúc cần liên kết từng thành phần với quyền IAM, network path, artifact, log và cleanup. Đây là cơ sở để kiểm tra workshop trước khi demo.
