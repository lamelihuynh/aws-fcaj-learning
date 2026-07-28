# KMS, S3 and Audit Encryption Lab

## Goal

Practice data-at-rest protection using AWS KMS and understand how access can be audited.

## Lab Flow

1. Create or identify a customer managed KMS key.
2. Configure an S3 bucket to use SSE-KMS encryption.
3. Upload a test object and verify encryption metadata.
4. Review key policy and IAM permissions needed to decrypt.
5. Enable or inspect CloudTrail events related to key usage.
6. Query or review audit records for access evidence.
7. Schedule key deletion or clean up resources safely after the lab.

## Validation

The object should be encrypted with the selected KMS key and audit evidence should show relevant API activity.
