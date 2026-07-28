# Lab 13 - AWS Backup plan và kiểm thử restore

## Nguồn tham khảo chính

- Workshop gốc: [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Tạo kế hoạch backup tập trung cho tài nguyên AWS và hiểu quan hệ giữa backup plan, vault, retention và restore test.

## Luồng thực hành đã viết lại

1. Chọn tài nguyên lab như EBS/RDS/DynamoDB theo phạm vi nhỏ.
2. Tạo Backup Vault và Backup Plan với schedule/retention rõ ràng.
3. Gắn resource assignment theo tag hoặc ARN.
4. Chạy backup test hoặc kiểm tra job history.
5. Ghi lại cách restore test và notification nếu có.

## Kiểm chứng cần có

- Backup job thành công hoặc có ghi chú lỗi rõ nguyên nhân.
- Có retention phù hợp thay vì giữ vô hạn.
- Xóa recovery point/tài nguyên test nếu lab kết thúc.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
