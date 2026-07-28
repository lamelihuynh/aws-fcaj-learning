# VPC Networking and Load Balancing Notes

## Why This Module Matters

Most AWS workloads fail or become risky when networking is unclear. This module helps me reason about traffic paths, subnet boundaries, firewall layers and load balancer behavior before I deploy application services.

## Concepts I Focused On

- VPC CIDR planning and subnet placement across Availability Zones.
- Public subnet routing through an Internet Gateway.
- Private subnet outbound access through a NAT Gateway.
- Route table association as a frequent source of mistakes.
- Security Groups as stateful resource-level allow rules.
- Network ACLs as stateless subnet-level rules with allow and deny behavior.
- VPC Flow Logs as network evidence instead of guessing.
- VPC Peering for simple direct connectivity and Transit Gateway for hub-and-spoke scale.
- ALB for HTTP/HTTPS Layer 7 routing, NLB for high-performance Layer 4 routing and GWLB for inspection appliances.

## Architecture Notes

For the final DevSecOps workshop, I will use networking concepts to explain where ECS tasks run, how the ALB reaches them, and why security groups should be scoped narrowly.

## Self Check

- Can I follow traffic from the browser to ALB to ECS task?
- Can I explain why a private subnet still needs outbound access for some workflows?
- Can I choose ALB vs NLB based on application requirements?

## Official References

- [Amazon VPC User Guide](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
- [Elastic Load Balancing User Guide](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)
