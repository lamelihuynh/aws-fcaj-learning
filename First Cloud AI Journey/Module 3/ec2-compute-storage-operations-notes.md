# EC2 Compute and Storage Operations Notes

## Why This Module Matters

Even when the final project uses serverless containers, EC2 remains important because many AWS services and lab environments expose the same ideas: instance sizing, network access, bootstrapping, disks, images and scaling.

## Concepts I Focused On

- EC2 lifecycle: launch, connect, stop, start, reboot and terminate.
- AMI as an operating system and software baseline.
- Key pairs, SSH/RDP and security group rules for safe access.
- EBS volumes as persistent block storage and snapshots as recovery points.
- Instance Store as fast temporary local storage with data loss risk.
- User Data for bootstrap automation.
- Instance metadata for runtime context.
- Auto Scaling Groups and load balancers for elasticity and health replacement.
- Lightsail and AWS MGN as adjacent compute/migration options.

## Architecture Notes

These notes help me explain why I later preferred ECS Fargate for the capstone: fewer servers to patch, simpler scale-down and better cost control for short demos.

## Self Check

- Can I attach and mount an EBS volume?
- Can I explain snapshot versus AMI?
- Can I identify whether an EC2 connection problem is caused by key, route or security group configuration?

## Official References

- [Amazon EC2 User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
