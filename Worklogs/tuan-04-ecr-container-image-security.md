# Tuần 04 - Amazon ECR, image tag và image security

## Mục tiêu tuần

Tuần này ghi lại phần học và thực hành theo lộ trình AWS FCAJ. Reference được tách thành hai lớp: file minh chứng trong repo này và workshop cộng đồng AWS Study Group để người đọc biết chính xác nội dung học dựa trên nguồn nào.

## Bảng tham chiếu theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 06/07/2026 | Học private registry, ECR repository, repository policy và boundary giữa account/region. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md)<br>[Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/) |
| Thứ 3 | 07/07/2026 | Thực hành aws ecr get-login-password, docker login, push/pull image và kiểm tra lỗi account/region. | [Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/) |
| Thứ 4 | 08/07/2026 | Xây dựng quy ước tag theo commit SHA, branch/environment và release tag bất biến. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 5 | 09/07/2026 | Đối chiếu ECR scan-on-push, pipeline scan và cách High/Critical finding chặn promote. | [Module 5](../First%20Cloud%20AI%20Journey/Module%205/module-05-ly-thuyet-security-iam-kms-detection.md)<br>[Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)<br>[000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/) |
| Thứ 6 | 10/07/2026 | Hoàn thiện checklist build-scan-auth-push-verify digest và chuẩn bị Jenkins credential. | [Lab 15 Docker ECR](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-15-docker-ecr-image-workflow.md)<br>[Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)<br>[000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |

## Kết quả rút ra

- Nội dung trong tuần đã được viết lại bằng tiếng Việt theo góc nhìn cá nhân, không giữ nguyên cấu trúc câu của workshop gốc.
- Mỗi ngày có ít nhất một minh chứng nội bộ hoặc workshop liên quan để khi đưa vào Hugo Worklog không bị trỏ sai module/lab.
- Các lab có cleanup hoặc cảnh báo chi phí để phù hợp với môi trường thực tập và tài khoản cá nhân.
