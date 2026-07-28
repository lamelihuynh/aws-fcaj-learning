# Compute Operations Practice Checklist

## Goal

Practice EC2 operations that support later container and deployment decisions.

## Checklist

- Launch a small Linux EC2 instance with a known AMI.
- Restrict inbound access to the minimum required source and port.
- Connect with SSH and verify user data execution.
- Attach an EBS volume and mount it to a test directory.
- Create a snapshot and record how it can be used for recovery.
- Create a simple AMI for repeatability.
- Review metadata access and avoid exposing credentials.
- Stop or terminate resources after testing.

## Validation

The instance should be reachable only through approved network rules, the mounted volume should persist after reboot, and cleanup should remove billable resources.
