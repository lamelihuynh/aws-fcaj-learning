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

## Ghi chú kỹ thuật

Security Hub cung cấp finding theo chuẩn kiểm tra bảo mật. Khi dùng trong báo cáo, nên nêu resource, severity và hướng xử lý thay vì chỉ ghi security score.
