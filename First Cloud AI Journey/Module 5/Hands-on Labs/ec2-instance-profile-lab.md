# EC2 Instance Profile Lab

## Goal

Understand how applications on EC2 can access AWS services through an attached role instead of hardcoded credentials.

## Lab Flow

1. Create an IAM role trusted by EC2.
2. Attach a least-privilege policy, such as limited S3 read or write.
3. Launch an EC2 instance with the instance profile.
4. Run AWS CLI commands from the instance without configuring access keys.
5. Compare this behavior with hardcoded credentials and note the risk reduction.
6. Remove the instance profile, role and test instance after the lab.

## Validation

The instance should access the allowed AWS service through role credentials obtained automatically from instance metadata.
