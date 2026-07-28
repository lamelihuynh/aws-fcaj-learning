# Database Selection Practice Checklist

## Goal

Practice selecting AWS database services from workload requirements instead of memorizing service names.

## Checklist

- If the workload needs standard relational transactions, start with Amazon RDS.
- If the workload needs higher relational scale and managed cluster storage, evaluate Aurora.
- If the workload is analytical and scans large datasets, evaluate Redshift.
- If the workload needs low-latency repeated reads, evaluate ElastiCache.
- Use Multi-AZ for availability, read replicas for read scaling and backups for recovery points.
- Consider DMS/SCT when migration from an existing database is part of the requirement.

## Validation

For each sample workload, write the chosen service, the reason for selection and the main operational risk.
