# Lab 17 - CI/CD pipeline cho ECS Container

## Nguồn tham khảo chính

- Workshop gốc: [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thiết kế luồng build-scan-push-deploy cho ECS và hiểu các lựa chọn GitHub Actions, GitLab Runner, CodeBuild/CodePipeline.

## Luồng thực hành đã viết lại

1. Xác định source repository và biến môi trường/secret cần có.
2. Build image, scan image và push lên ECR.
3. Cập nhật ECS task definition hoặc image tag.
4. Triển khai service và kiểm tra rollout/rollback.
5. Ghi lại nơi lưu log, artifact và security report.

## Kiểm chứng cần có

- Pipeline có artifact image rõ tag.
- Có điểm kiểm soát trước khi deploy production.
- Secret không hard-code trong repository.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
