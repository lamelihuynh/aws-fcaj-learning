# Database Services and Cache Notes

## Why This Module Matters

Databases are selected by workload shape. This module helps me distinguish transactional, analytical and cache workloads, then choose an AWS managed service that fits the reliability and scaling requirement.

## Concepts I Focused On

- Relational modeling basics: primary key, foreign key, normalization and indexes.
- RDBMS versus NoSQL tradeoffs.
- OLTP for transactional systems and OLAP for analytics.
- Amazon RDS for managed relational databases.
- Multi-AZ for availability and read replicas for read scaling.
- Amazon Aurora cluster storage, replicas and global database scenarios.
- Amazon Redshift for analytical workloads and columnar processing.
- ElastiCache for low-latency cache patterns using Redis or Memcached.
- DMS and SCT as migration support tools.

## Architecture Notes

The final DevSecOps workshop does not require a database tier, but these notes help me explain how the architecture could evolve if the application later needed user state, analytics or caching.

## Self Check

- Can I choose RDS, Aurora, Redshift or ElastiCache from workload requirements?
- Can I explain Multi-AZ versus read replica?
- Can I identify when cache improves performance and when it adds consistency complexity?

## Official References

- [Amazon RDS User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
