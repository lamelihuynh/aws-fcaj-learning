# Lab 08 - CloudWatch Logs, Metrics, Alarms và Dashboards

## Tài liệu tham khảo

- Workshop: [000008 - AWS CloudWatch Workshop](https://000008.awsstudygroup.com/vi/)

## Mục tiêu

Thiết lập quan sát cơ bản cho workload bằng CloudWatch metric, log, alarm và dashboard.

## Luồng thực hành

1. Xác định metric cần theo dõi: CPU, memory, error, latency hoặc task count.
2. Đẩy log ứng dụng/ECS/Lambda về CloudWatch Logs.
3. Viết Logs Insights query cho lỗi chính.
4. Tạo alarm hoặc dashboard đơn giản.
5. Ghi lại retention policy để kiểm soát chi phí log.

## Kiểm chứng

- Log và metric xuất hiện đúng namespace/log group.
- Alarm hoặc dashboard phản ánh tình trạng workload.
- Có retention thay vì giữ log vô hạn.

## Ghi chú kỹ thuật

CloudWatch nên được cấu hình trước khi xảy ra lỗi. Log group, metric, alarm, dashboard và retention policy là các phần cần có trong vận hành workload.
