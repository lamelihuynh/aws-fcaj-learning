# Module 01 - Nền tảng cloud, tài khoản AWS và định danh

## Mình học phần này để làm gì

Phần này đặt nền cho toàn bộ báo cáo: hiểu tài khoản AWS, mô hình trách nhiệm chia sẻ, hạ tầng toàn cầu, cách truy cập Console/CLI và thói quen kiểm soát chi phí ngay từ đầu.

## Ý mình cần nhớ

- Phân biệt Region, Availability Zone, Edge Location và lý do phải chọn Region theo độ trễ, dữ liệu và chi phí.
- Bảo vệ root user, bật MFA, dùng IAM Identity Center hoặc IAM role cho công việc hằng ngày thay vì access key dài hạn.
- Thiết lập ngân sách, tag tài nguyên và cleanup sau lab để không phát sinh chi phí ngoài ý muốn.
- Dùng ngôn ngữ Well-Architected khi giải thích quyết định: security, reliability, operational excellence, performance và cost optimization.

## Dùng lại trong báo cáo

- Dùng trong Week 1 để giải thích vì sao mọi lab đều bắt đầu bằng identity baseline và cost guardrail.
- Dùng lại ở Week 8-9 khi kiểm tra kiến trúc cuối kỳ và chuẩn bị checklist bàn giao.

## Workshop mình tham khảo

- [000001 - AWS Free Tier 2025](https://000001.awsstudygroup.com/vi/)
- [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/)
- [000012 - AWS IAM Identity Center](https://000012.awsstudygroup.com/vi/)

## Tài liệu AWS

- AWS Well-Architected Framework: https://docs.aws.amazon.com/wellarchitected/2025-02-25/framework/welcome.html
- AWS IAM User Guide: https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

## Tự nhắc

- Khi đưa vào báo cáo, mình cần gắn khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Nếu nhắc tới dịch vụ này, mình nên nói thêm một rủi ro hoặc lỗi cấu hình dễ gặp.
