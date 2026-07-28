# Lab 17 - CI/CD pipeline cho ECS Container

## Tài liệu tham khảo

- Workshop: [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)

## Mục tiêu

Thiết kế luồng build-scan-push-deploy cho ECS và hiểu các lựa chọn GitHub Actions, GitLab Runner, CodeBuild/CodePipeline.

## Luồng thực hành

1. Xác định source repository và biến môi trường/secret cần có.
2. Build image, scan image và push lên ECR.
3. Cập nhật ECS task definition hoặc image tag.
4. Triển khai service và kiểm tra rollout/rollback.
5. Ghi lại nơi lưu log, artifact và security report.

## Kiểm chứng

- Pipeline có artifact image rõ tag.
- Có điểm kiểm soát trước khi deploy production.
- Secret không hard-code trong repository.

## Ghi chú kỹ thuật

Pipeline DevSecOps cần tách rõ build, scan, push, deploy và rollback. Secret phải được quản lý qua cơ chế an toàn, không hard-code trong repository.
