# Network Design Practice Checklist

## Goal

Turn VPC theory into a design checklist that can be reused before deploying ECS Fargate services.

## Checklist

- Choose a non-overlapping VPC CIDR.
- Split public and private subnets across at least two Availability Zones.
- Attach an Internet Gateway for public subnet routing.
- Add NAT Gateway only when private workloads need outbound internet access.
- Confirm route table associations for every subnet.
- Use Security Groups for workload-level allow rules.
- Use NACLs only when subnet-level explicit deny behavior is needed.
- Enable VPC Flow Logs when evidence or troubleshooting is required.
- Place ALB in public subnets and application tasks in private subnets where possible.

## Validation

A complete design should show where traffic enters, where it is routed, what security layer allows it and where logs are collected.
