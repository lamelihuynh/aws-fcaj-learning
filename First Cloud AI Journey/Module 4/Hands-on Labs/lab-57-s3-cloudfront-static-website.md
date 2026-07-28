# Lab 57 - S3, static website và CloudFront

## Nguồn tham khảo chính

- Workshop gốc: [000057 - Khởi đầu với Amazon S3](https://000057.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành S3 bucket, upload object, versioning, static hosting và phân phối qua CloudFront theo hướng an toàn hơn.

## Luồng thực hành đã viết lại

1. Tạo bucket có tên duy nhất và bật Block Public Access theo nhu cầu lab.
2. Upload nội dung tĩnh, bật versioning/lifecycle nếu cần minh chứng.
3. Kiểm tra bucket policy hoặc object permission ở mức tối thiểu.
4. Gắn CloudFront distribution để phân phối nội dung thay vì phụ thuộc public object trực tiếp.
5. Ghi lại cleanup distribution, bucket object và policy.

## Kiểm chứng cần có

- Object truy cập được theo đúng mô hình đã chọn.
- Không để bucket public ngoài phạm vi lab.
- Có giải thích vì sao CloudFront tốt hơn mở public rộng.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
