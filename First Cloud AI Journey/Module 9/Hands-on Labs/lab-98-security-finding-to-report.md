# Lab 98 - Chuyển security finding thành báo cáo vận hành

## Tài liệu tham khảo

- Workshop: [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)

## Mục tiêu

Dùng GuardDuty/Security Hub/KMS/S3 evidence làm đầu vào cho phần báo cáo bảo mật thay vì chỉ mô tả lý thuyết.

## Luồng thực hành

1. Chọn một finding mẫu hoặc finding lab an toàn.
2. Ghi lại severity, resource, account/region và thời điểm.
3. Đề xuất hành động xử lý: investigate, isolate, rotate, patch hoặc suppress hợp lệ.
4. Đưa finding vào mẫu report JSON hoặc bảng tổng hợp.
5. Liên hệ với CloudWatch alarm/dashboard nếu cần cảnh báo.

## Kiểm chứng

- Finding được diễn giải bằng ngôn ngữ vận hành.
- Có action cụ thể thay vì chỉ ghi “đã phát hiện”.
- Không đưa dữ liệu nhạy cảm thật vào report public.

## Ghi chú kỹ thuật

Security finding nên được chuyển thành thông tin vận hành: phát hiện gì, tài nguyên nào bị ảnh hưởng, mức độ nghiêm trọng và hành động xử lý đề xuất.
