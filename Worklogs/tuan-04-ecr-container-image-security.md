# Tuần 04 - Amazon ECR, image tag và image security

## Mình tập trung vào

Tuần này mình ghi lại các phần đã học, lab đã xem và link workshop cần mở lại khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 06/07/2026 | Học private registry, ECR repository, repository policy và boundary giữa account/region. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md)<br>[Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/) |
| Thứ 3 | 07/07/2026 | Thực hành aws ecr get-login-password, docker login, push/pull image và kiểm tra lỗi account/region. | [Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/) |
| Thứ 4 | 08/07/2026 | Xây dựng quy ước tag theo commit SHA, branch/environment và release tag bất biến. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 5 | 09/07/2026 | Đối chiếu ECR scan-on-push, pipeline scan và cách High/Critical finding chặn promote. | [Module 5](../First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md)<br>[Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)<br>[000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/) |
| Thứ 6 | 10/07/2026 | Hoàn thiện checklist build-scan-auth-push-verify digest và chuẩn bị Jenkins credential. | [Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md)<br>[Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)<br>[000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |

## Ghi chú cuối tuần

- ECR không chỉ là nơi đẩy image; tag, digest và scan result là phần giúp truy vết release.
- Pipeline cần có điểm chặn rõ ràng khi image hoặc dependency có finding nghiêm trọng.
