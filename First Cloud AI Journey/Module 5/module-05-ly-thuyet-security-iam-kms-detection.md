# Module 05 - Security, IAM nâng cao, KMS và detection

## Mục đích

Module này đi sâu vào phần bảo mật: IAM policy, role, trust policy, permission boundary, condition key, KMS encryption, CloudTrail audit, Security Hub, GuardDuty và Macie.

## Ghi chú lý thuyết chính

- Đọc policy theo ba lớp: principal, action/resource và condition.
- Phân biệt identity-based policy, resource-based policy, permission boundary và SCP.
- Dùng KMS để quản lý encryption at rest và CloudTrail/Athena để kiểm chứng hành vi truy cập.
- Dùng Security Hub, GuardDuty và Macie như các nguồn finding cho dashboard hoặc báo cáo bảo mật.

## Cách dùng trong báo cáo

- Dùng trong Week 3 cho nền tảng bảo mật.
- Dùng lại ở Week 4-8 khi thiết kế security gate, scan report và xử lý finding.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/)
- [000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/)
- [000030 - IAM Permission Boundary](https://000030.awsstudygroup.com/vi/)
- [000033 - Mã hóa lưu trữ với AWS KMS](https://000033.awsstudygroup.com/vi/)
- [000044 - IAM Role & Condition](https://000044.awsstudygroup.com/vi/)
- [000048 - Ứng dụng truy cập dịch vụ AWS với IAM Role](https://000048.awsstudygroup.com/vi/)
- [000090 - Khám phá dữ liệu nhạy cảm trong S3 bằng Amazon Macie](https://000090.awsstudygroup.com/vi/)
- [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- AWS IAM User Guide: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
- AWS KMS Developer Guide: https://docs.aws.amazon.com/kms/latest/developerguide/concepts-intro.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
