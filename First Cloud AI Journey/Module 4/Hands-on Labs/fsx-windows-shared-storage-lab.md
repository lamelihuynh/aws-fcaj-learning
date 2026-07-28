# FSx Windows Shared Storage Lab

## Goal

Understand managed Windows file storage with SMB access and Active Directory integration.

## Lab Flow

1. Review the need for AWS Managed Microsoft AD or an existing directory.
2. Create an FSx for Windows File Server file system.
3. Launch or use a Windows EC2 instance joined to the domain.
4. Mount the SMB file share from the client.
5. Create and read a test file from the share.
6. Review backup, throughput and storage settings.
7. Delete the file system and directory resources when the lab is complete.

## Validation

The Windows client can mount the share and access files through domain-aware SMB permissions.
