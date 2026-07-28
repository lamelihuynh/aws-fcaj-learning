# Module 07 - Containers, Amazon ECR, ECS Fargate và CI/CD

## Phạm vi module

Phần này nối kiến thức compute với dự án cuối kỳ: Docker image, ECR repository, image tag, scan-on-push, ECS task definition, service, ALB, Fargate, Secrets Manager và pipeline triển khai.

## File trong thư mục

- File `module-...md`: lưu phần lý thuyết, thuật ngữ và ý chính.
- Thư mục `Hands-on Labs/`: lưu luồng thực hành, kiểm chứng và ghi chú cleanup.

## Ghi chú chính

- [Ghi chú lý thuyết](module-07-ly-thuyet-containers-ecr-ecs-cicd.md)

## Hands-on Labs

| Lab | Workshop | Mục tiêu |
| --- | --- | --- |
| [Lab 15 - Docker image và đẩy image lên Amazon ECR](Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/) | Thực hành đóng gói ứng dụng bằng Docker và đẩy image lên ECR, có tag truy vết được. |
| [Lab 16 - ECS Fargate service phía sau Application Load Balancer](Hands-on%20Labs/lab-16-ecs-fargate-alb-service.md) | [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/) | Triển khai container trên ECS/Fargate với task definition, service, target group và ALB. |
| [Lab 17 - CI/CD pipeline cho ECS Container](Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) | Thiết kế luồng build-scan-push-deploy cho ECS và hiểu các lựa chọn GitHub Actions, GitLab Runner, CodeBuild/CodePipeline. |
| [Lab 96 - Secrets Manager với RDS và AWS Fargate](Hands-on%20Labs/lab-96-secrets-manager-fargate.md) | [000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/) | Thực hành tách secret khỏi image/source code và inject secret vào workload Fargate đúng quyền. |

## Gắn với Worklog

Module này được dùng chính trong **Tuần 4-6** và tiếp tục hỗ trợ các phần kiến trúc, vận hành hoặc cleanup ở những tuần sau.
