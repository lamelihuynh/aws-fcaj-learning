# Lab 08 - CloudWatch Logs, Metrics, Alarms và Dashboards

## Nguồn tham khảo chính

- Workshop gốc: [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thiết lập quan sát cơ bản cho workload bằng CloudWatch metric, log, alarm và dashboard.

## Luồng thực hành đã viết lại

1. Xác định metric cần theo dõi: CPU, memory, error, latency hoặc task count.
2. Đẩy log ứng dụng/ECS/Lambda về CloudWatch Logs.
3. Viết Logs Insights query cho lỗi chính.
4. Tạo alarm hoặc dashboard đơn giản.
5. Ghi lại retention policy để kiểm soát chi phí log.

## Kiểm chứng cần có

- Log và metric xuất hiện đúng namespace/log group.
- Alarm hoặc dashboard phản ánh tình trạng workload.
- Có retention thay vì giữ log vô hạn.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
