# Storage Gateway File Share Lab

## Goal

Practice a hybrid storage pattern where users access files through SMB/NFS while data is backed by S3.

## Lab Flow

1. Prepare an S3 bucket for file share backing storage.
2. Deploy or review a File Gateway appliance.
3. Configure network rules for SMB or NFS access.
4. Create a file share and connect it to the S3 bucket.
5. Mount the share from a client machine.
6. Create test files and confirm they appear in S3.
7. Clean up the share, gateway resources and S3 objects.

## Validation

A test file created through the mounted share should be visible as an S3 object, proving the hybrid storage path.
