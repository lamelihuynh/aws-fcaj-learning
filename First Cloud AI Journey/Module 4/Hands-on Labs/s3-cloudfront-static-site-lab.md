# S3 and CloudFront Static Site Lab

## Goal

Understand how S3 stores static assets and how CloudFront can sit in front of S3 for safer and faster delivery.

## Lab Flow

1. Create an S3 bucket with a unique name.
2. Upload sample static files.
3. Review Block Public Access and object ownership settings.
4. Enable versioning before making changes to files.
5. Configure a CloudFront distribution with S3 as origin.
6. Restrict direct public access where possible and let CloudFront serve viewers.
7. Test content delivery and cache behavior.
8. Clean up CloudFront and S3 resources after the lab.

## Validation

The site content loads through CloudFront, object versions are visible in S3 and the cleanup checklist is complete.
