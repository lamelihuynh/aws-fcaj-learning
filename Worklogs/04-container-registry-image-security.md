# Week 4 Evidence - Container Registry and Image Security

## Scope

- **Timeline:** 06/07/2026 - 10/07/2026
- **Personal focus:** Use Amazon ECR as the trusted image registry and make image delivery traceable.
- **Report connection:** Supports Week 4 in the Hugo report.

## Evidence Notes

1. I studied ECR repositories, repository policy and IAM actions required by CI jobs.
2. I practiced Docker authentication through `aws ecr get-login-password`.
3. I designed image tags based on commit SHA and environment labels instead of relying only on `latest`.
4. I compared ECR scan-on-push with pipeline image scanning.
5. I created a delivery checklist: build, scan, authenticate, push, verify digest and store evidence.

## Reference Materials

- [Amazon ECR User Guide](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
- [AWS IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [Trivy Documentation](https://aquasecurity.github.io/trivy/)
