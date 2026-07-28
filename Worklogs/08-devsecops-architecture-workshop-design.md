# Week 8 Evidence - DevSecOps Architecture and Workshop Design

## Scope

- **Timeline:** 03/08/2026 - 07/08/2026
- **Personal focus:** Convert scattered technical work into a coherent workshop architecture.
- **Report connection:** Supports Week 8 in the Hugo report.

## Evidence Notes

1. I grouped the solution into network, identity, CI/CD, runtime, report storage, Lambda processing and observability layers.
2. I drafted diagrams where every arrow represents a route, permission or event trigger.
3. I wrote a workshop lab outline from prerequisites to validation.
4. I prepared snippets for Dockerfile, Jenkinsfile, ECS task definition, Lambda handler and sample scan JSON.
5. I added troubleshooting notes and a static demo backup plan.

## Reference Materials

- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/2025-02-25/framework/welcome.html)
- [AWS Prescriptive Guidance - DevSecOps Best Practices](https://docs.aws.amazon.com/prescriptive-guidance/latest/designing-a-devsecops-mechanism/best-practices.html)
- [Amazon ECS on AWS Fargate Guide](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started-fargate.html)
- [Amazon ECR User Guide](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
- [AWS Lambda with S3 Trigger Tutorial](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html)
- [CloudWatch Container Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/ContainerInsights.html)
