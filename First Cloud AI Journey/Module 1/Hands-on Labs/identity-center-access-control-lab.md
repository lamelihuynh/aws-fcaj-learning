# Identity Center Access Control Lab

## Goal

Practice centralized workforce access with AWS IAM Identity Center and avoid long-lived credentials for daily AWS CLI work.

## Lab Flow

1. Enable or review AWS Organizations and IAM Identity Center.
2. Create a user and group that represent an operator role.
3. Create permission sets for limited administrative or EC2-oriented access.
4. Assign the group to an AWS account through the permission set.
5. Sign in through the access portal and verify the visible account/role.
6. Generate temporary CLI credentials from the portal and run a read-only AWS CLI command.
7. Remove assignments or test users after the lab.

## Validation

- The user can sign in through the portal.
- The user sees only assigned accounts and roles.
- CLI commands work only during the temporary credential session.

## Notes For Report

This lab supports Week 1 and the security discussion around temporary access, least privilege and centralized identity.
