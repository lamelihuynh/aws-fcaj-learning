# Lab 98 - Chuyển security finding thành báo cáo vận hành

## Nguồn tham khảo chính

- Workshop gốc: [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Dùng GuardDuty/Security Hub/KMS/S3 evidence làm đầu vào cho phần báo cáo bảo mật thay vì chỉ mô tả lý thuyết.

## Luồng thực hành đã viết lại

1. Chọn một finding mẫu hoặc finding lab an toàn.
2. Ghi lại severity, resource, account/region và thời điểm.
3. Đề xuất hành động xử lý: investigate, isolate, rotate, patch hoặc suppress hợp lệ.
4. Đưa finding vào mẫu report JSON hoặc bảng tổng hợp.
5. Liên hệ với CloudWatch alarm/dashboard nếu cần cảnh báo.

## Kiểm chứng cần có

- Finding được diễn giải bằng ngôn ngữ vận hành.
- Có action cụ thể thay vì chỉ ghi “đã phát hiện”.
- Không đưa dữ liệu nhạy cảm thật vào report public.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
