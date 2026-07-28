# IAM Permission Boundary Lab

## Goal

Understand how a permission boundary limits the maximum effective permissions of an IAM principal.

## Lab Flow

1. Create a managed policy that represents the maximum allowed scope.
2. Attach it as a permission boundary to a test user or role.
3. Attach another policy that appears broader than the boundary.
4. Test actions inside and outside the boundary.
5. Document the effective permission result.
6. Delete the test principal and policies.

## Validation

Actions outside the boundary should be denied even if another attached policy appears to allow them.
