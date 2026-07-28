# Lab 01 - Thiết lập Free Tier, credit và cảnh báo chi phí

## Tài liệu tham khảo

- Workshop: [000001 - AWS Free Tier 2025](https://000001.awsstudygroup.com/vi/)

## Mục tiêu

Kiểm tra trạng thái tài khoản, hiểu Free Tier/credit và thiết lập thói quen theo dõi chi phí trước khi chạy các lab khác.

## Luồng thực hành

1. Đọc giới hạn Free Tier/credit và ghi lại dịch vụ cần tránh nếu không cần thiết.
2. Tạo Cost Budget hoặc ghi lại cấu hình budget dự kiến theo ngưỡng 80% và 100%.
3. Tạo quy ước tag cho lab: project, week, owner, cleanup-date.
4. Sau mỗi lab, kiểm tra Billing/Cost Explorer và xóa tài nguyên không dùng.

## Kiểm chứng

- Có checklist cost guardrail trước khi bắt đầu lab.
- Biết vị trí kiểm tra AWS Budgets và khu vực Billing.
- Có quy tắc cleanup thống nhất trong worklog.

## Ghi chú kỹ thuật

Cost guardrail nên được kiểm tra trước khi tạo tài nguyên mới. Các dịch vụ có thể phát sinh chi phí nhanh như EC2, NAT Gateway, ALB hoặc RDS cần được gắn tag và có kế hoạch cleanup rõ ràng.
