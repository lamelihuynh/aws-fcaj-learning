# Cloud Foundations and Identity Notes

## Why This Module Matters

This module gives me the vocabulary to explain later architecture decisions. Before deploying ECR, ECS Fargate or Lambda, I need to understand what an AWS account is, where resources run, how access is granted and how cost can grow if resources are left idle.

## Concepts I Focused On

- Cloud value: elasticity, managed services, speed of provisioning and OpEx-style spending.
- AWS global infrastructure: Region for geography, Availability Zone for fault isolation and edge locations for low-latency delivery.
- Access methods: Console for visual inspection, CLI for repeatable operations and SDK for application integration.
- Identity baseline: root user protection, IAM users only when needed, roles for temporary access and IAM Identity Center for centralized workforce access.
- Cost habits: budgets, tagging, service cleanup and choosing managed/serverless services where possible.

## Notes I Will Reuse In The Report

- Use Well-Architected language when explaining tradeoffs: security, reliability, performance, cost and operations.
- Prefer temporary credentials and permission sets over long-lived access keys.
- Always connect technical setup with cleanup responsibility.

## Self Check

- Can I explain Region vs AZ without reading notes?
- Can I explain why the root account should not be used for daily work?
- Can I configure CLI access using temporary credentials from Identity Center?

## Official References

- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/2025-02-25/framework/welcome.html)
- [AWS IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
