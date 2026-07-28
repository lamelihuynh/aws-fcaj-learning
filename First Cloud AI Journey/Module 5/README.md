# Module 05 - Security, IAM nâng cao, KMS và detection

## Phạm vi module

Phần này đi sâu vào phần bảo mật: IAM policy, role, trust policy, permission boundary, condition key, KMS encryption, CloudTrail audit, Security Hub, GuardDuty và Macie.

## File trong thư mục

- File `module-...md`: lưu phần lý thuyết, thuật ngữ và ý chính.
- Thư mục `Hands-on Labs/`: lưu luồng thực hành, kiểm chứng và ghi chú cleanup.

## Ghi chú chính

- [Ghi chú lý thuyết](module-05-ly-thuyet-security-iam-kms-detection.md)

## Hands-on Labs

| Lab | Workshop | Mục tiêu |
| --- | --- | --- |
| [Lab 18 - Security Hub baseline](Hands-on%20Labs/lab-18-security-hub-baseline.md) | [000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/) | Bật Security Hub để quan sát security standard, score và finding mẫu trong tài khoản lab. |
| [Lab 30 - IAM Permission Boundary](Hands-on%20Labs/lab-30-permission-boundary.md) | [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/) | Thực hành giới hạn quyền tối đa của IAM user/role bằng permission boundary. |
| [Lab 33 - KMS, S3 encryption, CloudTrail và Athena](Hands-on%20Labs/lab-33-kms-s3-cloudtrail-athena.md) | [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/) | Hiểu encryption at rest bằng KMS và cách audit hành vi truy cập qua CloudTrail/Athena. |
| [Lab 44 - IAM Role và Condition](Hands-on%20Labs/lab-44-iam-role-condition.md) | [000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/) | Thực hành assume role có điều kiện theo IP hoặc thời gian để hiểu policy condition trong IAM. |
| [Lab 48 - EC2 Instance Profile truy cập S3](Hands-on%20Labs/lab-48-ec2-instance-profile.md) | [000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/) | Cấp quyền cho ứng dụng trên EC2 truy cập dịch vụ AWS bằng IAM role thay vì nhúng access key. |
| [Lab 98 - GuardDuty finding practice](Hands-on%20Labs/lab-98-guardduty-finding-practice.md) | [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) | Làm quen với GuardDuty, cách phát hiện bất thường và cách đọc finding trong ngữ cảnh vận hành. |

## Gắn với Worklog

Module này được dùng chính trong **Tuần 3** và tiếp tục hỗ trợ các phần kiến trúc, vận hành hoặc cleanup ở những tuần sau.
