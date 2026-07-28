# IAM Users, Roles and MFA Lab

## Goal

Practice identity basics and understand why IAM roles are preferred for temporary privileged operations.

## Lab Flow

1. Create a test IAM group with limited permissions.
2. Create a test user and require MFA.
3. Create a role with a clear trust relationship.
4. Switch role from the console and compare permissions.
5. Confirm denied actions when permissions are not granted.
6. Remove the test user, group and role after validation.

## Validation

The test user should access only allowed services and should require MFA before sensitive operations.
