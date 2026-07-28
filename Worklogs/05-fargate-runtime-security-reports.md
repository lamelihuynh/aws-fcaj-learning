# Week 5 Evidence - Fargate Runtime and Security Report Processing

## Scope

- **Timeline:** 13/07/2026 - 17/07/2026
- **Personal focus:** Deploy container workloads with ECS Fargate and centralize security scan outputs in S3/Lambda.
- **Report connection:** Supports Week 5 in the Hugo report.

## Evidence Notes

1. I compared EKS and ECS Fargate, then selected Fargate for lower operational overhead during demos.
2. I prepared task definition fields for image URI, CPU/memory, port mapping, logging and IAM roles.
3. I connected ECS services with subnets, Security Groups, target groups and ALB health checks.
4. I designed an S3 report bucket with prefixes for multiple security tools.
5. I designed a Lambda aggregator that reads JSON reports and highlights High/Critical findings.

## Reference Materials

- [Amazon ECS on AWS Fargate Guide](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/getting-started-fargate.html)
- [Fargate Task Definitions](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate-tasks-services.html)
- [Fargate Task Networking](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate-task-networking.html)
- [Amazon S3 User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html)
- [AWS Lambda with S3 Trigger Tutorial](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html)
