# S3, Hybrid Storage and Disaster Recovery Notes

## Why This Module Matters

Storage decisions affect security, cost, durability and recovery. This module helps me choose object, file, hybrid and backup services based on access pattern rather than memorizing service names.

## Concepts I Focused On

- S3 object storage, bucket naming, object keys and storage classes.
- Block Public Access, bucket policy, object ownership, encryption, versioning and lifecycle rules.
- CloudFront as a safer global delivery layer for static content.
- Glacier classes for archive data and compliance-oriented retention.
- EFS for Linux shared file storage and FSx for Windows SMB workloads.
- Storage Gateway as a bridge between on-premises file access and S3-backed storage.
- AWS Backup as centralized policy-driven backup management.
- DR strategies: Backup and Restore, Pilot Light, Warm Standby and Multi-site Active-Active.
- RTO and RPO as the language for recovery decisions.

## Architecture Notes

The final workshop uses S3 as a report bucket for security scan output. Versioning, encryption, lifecycle cleanup and least-privilege upload policy are the key ideas I reuse from this module.

## Self Check

- Can I explain why S3 static website hosting and CloudFront are different roles?
- Can I choose between S3, EFS, FSx and Storage Gateway?
- Can I map a workload to a DR strategy based on RTO/RPO?

## Official References

- [Amazon S3 User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html)
- [AWS Storage Gateway Documentation](https://docs.aws.amazon.com/storagegateway/)
- [AWS Backup Developer Guide](https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html)
