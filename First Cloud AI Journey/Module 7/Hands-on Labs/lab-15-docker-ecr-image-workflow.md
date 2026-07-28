# Lab 15 - Docker image và đẩy image lên Amazon ECR

## Nguồn tham khảo chính

- Workshop gốc: [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành đóng gói ứng dụng bằng Docker và đẩy image lên ECR, có tag truy vết được.

## Luồng thực hành đã viết lại

1. Build image local và chạy container kiểm thử.
2. Tạo ECR repository private.
3. Đăng nhập ECR bằng aws ecr get-login-password.
4. Tag image bằng commit SHA hoặc version rõ ràng rồi push lên ECR.
5. Kiểm tra digest, tag và quyền repository.

## Kiểm chứng cần có

- Image push thành công và có digest.
- Tag không chỉ dùng latest.
- Có cleanup image/repository nếu chỉ dùng lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
