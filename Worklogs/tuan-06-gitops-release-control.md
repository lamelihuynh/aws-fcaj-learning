# Tuần 06 - GitOps, release control và rollback

## Mình tập trung vào

Tuần này mình ghi lại các phần đã học, lab đã xem và link workshop cần mở lại khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 20/07/2026 | Học GitOps: manifest khai báo, Git là source of truth, reconciliation và rollback bằng version history. | [Module 9](../First%20Cloud%20AI%20Journey/Module%209/module-09-ly-thuyet-architecture-devsecops-report.md)<br>[Lab 37 CloudFormation](../First%20Cloud%20AI%20Journey/Module%208/Hands-on%20Labs/lab-37-cloudformation-baseline.md) | [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |
| Thứ 3 | 21/07/2026 | Đọc cách Argo CD/EKS hoặc pipeline tương đương quản lý sync status và health status. | [Module 7](../First%20Cloud%20AI%20Journey/Module%207/module-07-ly-thuyet-containers-ecr-ecs-cicd.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 4 | 22/07/2026 | Thiết kế staging flow: Jenkins build image, update tag và deploy tự động sau khi kiểm tra health. | [Lab 17 CI/CD ECS](../First%20Cloud%20AI%20Journey/Module%207/Hands-on%20Labs/lab-17-ecs-cicd-pipeline.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) |
| Thứ 5 | 23/07/2026 | Thiết kế production promotion với manual approval, controlled sync và rollback step. | [Lab 09 Architecture Checklist](../First%20Cloud%20AI%20Journey/Module%209/Hands-on%20Labs/lab-09-devsecops-architecture-checklist.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)<br>[000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/) |
| Thứ 6 | 24/07/2026 | Hoàn thiện runbook credential, drift, rollback và incident note cho workshop. | [Module 9](../First%20Cloud%20AI%20Journey/Module%209/module-09-ly-thuyet-architecture-devsecops-report.md) | [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)<br>[000031 - AWS Systems Manager](https://000031.awsstudygroup.com/vi/) |

## Ghi chú cuối tuần

- GitOps giúp mình nhìn deployment như một thay đổi có lịch sử, có rollback và có trạng thái sync rõ ràng.
- Production promotion cần manual approval hoặc gate riêng, không nên đi cùng nhịp với staging.
