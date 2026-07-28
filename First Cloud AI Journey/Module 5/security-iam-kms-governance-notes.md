# Security, IAM and KMS Governance Notes

## Why This Module Matters

Security is not one final checklist. It appears in account access, network controls, encryption, logging, CI/CD gates and cleanup. This module gives me the foundation for explaining DevSecOps on AWS.

## Concepts I Focused On

- Shared Responsibility Model and customer-owned controls.
- IAM principals, users, groups, roles and policies.
- Least privilege, permission boundaries and trust policies.
- AWS Organizations and SCPs for account-level guardrails.
- IAM Identity Center for workforce access.
- Cognito as application identity for end users.
- KMS key hierarchy and envelope encryption.
- S3 encryption and CloudTrail/Athena audit patterns.
- Security Hub for findings and security posture visibility.

## Architecture Notes

In the final project, IAM roles are used for ECS task execution, Lambda processing and limited S3 report access. KMS/S3/CloudWatch concepts support the evidence and audit story.

## Self Check

- Can I explain why a role is safer than hardcoded credentials?
- Can I identify whether a failed access attempt is blocked by identity policy, resource policy or boundary?
- Can I explain envelope encryption in simple terms?

## Official References

- [AWS IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [AWS KMS Concepts](https://docs.aws.amazon.com/kms/latest/developerguide/concepts-intro.html)
