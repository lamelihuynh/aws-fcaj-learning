# Week 6 Evidence - GitOps Release Control Notes

## Scope

- **Timeline:** 20/07/2026 - 24/07/2026
- **Personal focus:** Design a GitOps delivery model with staging automation and production control.
- **Report connection:** Supports Week 6 in the Hugo report.

## Evidence Notes

1. I summarized GitOps as desired state stored in Git plus reconciliation by a controller.
2. I reviewed Argo CD Application concepts, sync status and health status.
3. I designed staging auto-sync from a new image tag to a running environment.
4. I designed production promotion with manual approval and rollback notes.
5. I wrote down credential and drift-handling concerns for the final workshop.

## Reference Materials

- [Argo CD on Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/argocd.html)
- [AWS CodePipeline User Guide](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)
- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/2025-02-25/framework/welcome.html)
