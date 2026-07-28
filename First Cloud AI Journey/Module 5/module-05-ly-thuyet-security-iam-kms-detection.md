# Module 05 - Security, IAM nâng cao, KMS và detection

## Mục tiêu kỹ thuật

Phần này đi sâu vào phần bảo mật: IAM policy, role, trust policy, permission boundary, condition key, KMS encryption, CloudTrail audit, Security Hub, GuardDuty và Macie.

## Nội dung chính

- Đọc policy theo ba lớp: principal, action/resource và condition.
- Phân biệt identity-based policy, resource-based policy, permission boundary và SCP.
- Dùng KMS để quản lý encryption at rest và CloudTrail/Athena để kiểm chứng hành vi truy cập.
- Dùng Security Hub, GuardDuty và Macie như các nguồn finding cho dashboard hoặc báo cáo bảo mật.

## Ứng dụng trong báo cáo

- Dùng trong Week 3 cho nền tảng bảo mật.
- Dùng lại ở Week 4-8 khi thiết kế security gate, scan report và xử lý finding.

## Workshop tham khảo

- [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/)
- [000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/)
- [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/)
- [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)
- [000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/)
- [000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/)
- [000090 - Khám phá dữ liệu nhạy cảm trong S3 bằng Amazon Macie](https://000090.awsstudygroup.com/vi/)
- [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)

## Tài liệu AWS

- AWS IAM User Guide: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
- AWS KMS Developer Guide: https://docs.aws.amazon.com/kms/latest/developerguide/concepts-intro.html

## Ghi chú kỹ thuật

- Khi đưa vào báo cáo, cần liên kết khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Với mỗi dịch vụ, nên nêu thêm rủi ro vận hành, lỗi cấu hình thường gặp hoặc điểm kiểm chứng.
