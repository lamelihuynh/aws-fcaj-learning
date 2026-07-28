# Lab 100 - DR, cleanup và bàn giao cuối kỳ

## Nguồn tham khảo chính

- Workshop gốc: [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Dùng tư duy DR và cleanup để kiểm tra báo cáo cuối kỳ không bỏ sót tài nguyên, chi phí hoặc rủi ro vận hành.

## Luồng thực hành đã viết lại

1. Liệt kê tài nguyên còn tồn tại: ECS, ALB, ECR, S3, Lambda, CloudWatch, NAT Gateway, EC2, IAM.
2. Đánh dấu tài nguyên cần giữ làm minh chứng và tài nguyên phải xóa.
3. Ghi lại phương án phục hồi hoặc tạo lại bằng template/script nếu cần.
4. Kiểm tra Billing/Budgets sau cleanup.
5. Cập nhật README/reference để người đọc truy vết được nguồn học tập.

## Kiểm chứng cần có

- Có checklist cleanup cuối kỳ.
- Không còn tài nguyên chi phí cao ngoài ý muốn.
- Báo cáo có link reference đến repo learning và workshop nguồn.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
