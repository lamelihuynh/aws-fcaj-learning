# Lab 98 - GuardDuty finding practice

## Tài liệu tham khảo

- Workshop: [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)

## Mục tiêu

Làm quen với GuardDuty, cách phát hiện bất thường và cách đọc finding trong ngữ cảnh vận hành.

## Luồng thực hành

1. Bật GuardDuty trong Region lab.
2. Tạo sample finding hoặc làm theo luồng thực hành an toàn trong workshop.
3. Đọc resource, severity, type và recommended action.
4. Liên hệ finding với dashboard/report security gate.
5. Tắt GuardDuty nếu không dùng tiếp để kiểm soát chi phí.

## Kiểm chứng

- Finding xuất hiện và đọc được ngữ cảnh.
- Có phân loại xử lý theo severity.
- Có cleanup hoặc ghi chú trạng thái dịch vụ sau lab.

## Ghi chú kỹ thuật

GuardDuty là nguồn cảnh báo phục vụ phát hiện bất thường. Finding cần được đọc theo severity, resource, account/region và recommended action.
