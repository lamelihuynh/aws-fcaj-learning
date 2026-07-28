# Week 7 Evidence - CloudWatch Operations and Cost Guardrails

## Scope

- **Timeline:** 27/07/2026 - 31/07/2026
- **Personal focus:** Observe ECS workloads, query logs and prevent unexpected AWS lab cost.
- **Report connection:** Supports Week 7 in the Hugo report.

## Evidence Notes

1. I reviewed CloudWatch Container Insights for ECS workload metrics.
2. I planned log group naming, retention and Logs Insights queries.
3. I drafted dashboard metrics for CPU, memory, network, task count and target health.
4. I set cost guardrail notes using AWS Budgets and cleanup checklists.
5. I wrote an incident drill for unhealthy service investigation.

## Reference Materials

- [CloudWatch Container Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/ContainerInsights.html)
- [ECS Container Insights Metrics](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/Container-Insights-metrics-ECS.html)
- [Monitor Amazon ECS with CloudWatch](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cloudwatch-metrics.html)
- [AWS Budgets User Guide](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html)
