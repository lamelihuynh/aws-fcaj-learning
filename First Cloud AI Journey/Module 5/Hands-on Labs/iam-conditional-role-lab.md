# IAM Conditional Role Lab

## Goal

Practice adding conditions to role trust or permission policies so access depends on context.

## Lab Flow

1. Create a test IAM role with limited permissions.
2. Add a trust policy condition such as source IP or time window.
3. Attempt role assumption from an allowed context.
4. Attempt the same operation from a disallowed context.
5. Record the difference between explicit deny, implicit deny and allowed access.
6. Remove the test role after validation.

## Validation

The role should be usable only when the condition is satisfied.
