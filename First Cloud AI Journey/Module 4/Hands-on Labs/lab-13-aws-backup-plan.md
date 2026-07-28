# Lab 13 - AWS Backup plan và kiểm thử restore

## Tài liệu tham khảo

- Workshop: [000013 - AWS Backup cho hệ thống](https://000013.awsstudygroup.com/vi/)

## Mục tiêu

Tạo kế hoạch backup tập trung cho tài nguyên AWS và hiểu quan hệ giữa backup plan, vault, retention và restore test.

## Luồng thực hành

1. Chọn tài nguyên lab như EBS/RDS/DynamoDB theo phạm vi nhỏ.
2. Tạo Backup Vault và Backup Plan với schedule/retention rõ ràng.
3. Gắn resource assignment theo tag hoặc ARN.
4. Chạy backup test hoặc kiểm tra job history.
5. Ghi lại cách restore test và notification nếu có.

## Kiểm chứng

- Backup job thành công hoặc có ghi chú lỗi rõ nguyên nhân.
- Có retention phù hợp thay vì giữ vô hạn.
- Xóa recovery point/tài nguyên test nếu lab kết thúc.

## Ghi chú kỹ thuật

Backup chỉ có ý nghĩa khi có thể restore được. Cần ghi rõ backup plan, vault, retention, restore test và cleanup recovery point sau khi hoàn tất lab.
