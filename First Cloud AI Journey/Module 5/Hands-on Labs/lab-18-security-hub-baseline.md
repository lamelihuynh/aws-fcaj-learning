# Lab 18 - Security Hub baseline

## Tài liệu tham khảo

- Workshop: [000018 - Bắt đầu với AWS Security Hub](https://000018.awsstudygroup.com/vi/)

## Mục tiêu

Bật Security Hub để quan sát security standard, score và finding mẫu trong tài khoản lab.

## Luồng thực hành

1. Kích hoạt Security Hub trong Region dùng cho lab.
2. Bật chuẩn kiểm tra phù hợp như AWS Foundational Security Best Practices.
3. Đọc finding theo severity, resource và remediation hint.
4. Ghi lại cách finding có thể trở thành đầu vào cho báo cáo DevSecOps.
5. Tắt/xóa tài nguyên liên quan nếu chỉ dùng thử.

## Kiểm chứng

- Security Hub hiển thị score/finding.
- Phân biệt finding informational với high/critical.
- Có ghi chú không coi score là kết luận duy nhất về bảo mật.

## Ghi chú

Security Hub cho mình một cách nhìn tổng quan về finding trong tài khoản. Khi đưa vào báo cáo mình sẽ không chỉ ghi score, mà ghi finding đó liên quan tài nguyên nào.
