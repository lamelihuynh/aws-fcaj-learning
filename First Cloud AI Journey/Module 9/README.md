# Module 09 - Kiến trúc DevSecOps, workshop và báo cáo cuối kỳ

## Vai trò trong lộ trình

Module này gom phần tổng hợp cuối: biến các dịch vụ đã học thành kiến trúc DevSecOps có security gate, artifact report, observability, cost cleanup và tài liệu song ngữ có thể trình bày.

## Quy ước file trong module

- File bắt đầu bằng `module-` là ghi chú lý thuyết, dùng để giải thích khái niệm và cách áp dụng vào báo cáo.
- File trong thư mục `Hands-on Labs/` bắt đầu bằng `lab-` là minh chứng thực hành, bám theo workshop cộng đồng AWS Study Group nhưng được viết lại theo luồng học cá nhân.

## Nội dung chính

- [Ghi chú lý thuyết](module-09-ly-thuyet-architecture-devsecops-report.md)

## Hands-on Labs

| Lab | Workshop gốc | Mục tiêu cá nhân |
| --- | --- | --- |
| [Lab 09 - Checklist kiến trúc DevSecOps cuối kỳ](Hands-on%20Labs/lab-09-devsecops-architecture-checklist.md) | [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/) | Tổng hợp pipeline container, security gate, report artifact, observability và cleanup thành checklist workshop cá nhân. |
| [Lab 98 - Chuyển security finding thành báo cáo vận hành](Hands-on%20Labs/lab-98-security-finding-to-report.md) | [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/) | Dùng GuardDuty/Security Hub/KMS/S3 evidence làm đầu vào cho phần báo cáo bảo mật thay vì chỉ mô tả lý thuyết. |
| [Lab 100 - DR, cleanup và bàn giao cuối kỳ](Hands-on%20Labs/lab-100-dr-cleanup-handover.md) | [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/) | Dùng tư duy DR và cleanup để kiểm tra báo cáo cuối kỳ không bỏ sót tài nguyên, chi phí hoặc rủi ro vận hành. |

## Liên kết với Worklog

Module này được dùng chính trong **Tuần 8-9**, và được tái sử dụng ở các tuần sau khi kiến trúc cần cùng nền tảng dịch vụ.
