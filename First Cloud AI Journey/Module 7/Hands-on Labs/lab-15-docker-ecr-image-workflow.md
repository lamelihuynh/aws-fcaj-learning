# Lab 15 - Docker image và đẩy image lên Amazon ECR

## Tài liệu tham khảo

- Workshop: [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành đóng gói ứng dụng bằng Docker và đẩy image lên ECR, có tag truy vết được.

## Luồng thực hành

1. Build image local và chạy container kiểm thử.
2. Tạo ECR repository private.
3. Đăng nhập ECR bằng aws ecr get-login-password.
4. Tag image bằng commit SHA hoặc version rõ ràng rồi push lên ECR.
5. Kiểm tra digest, tag và quyền repository.

## Kiểm chứng

- Image push thành công và có digest.
- Tag không chỉ dùng latest.
- Có cleanup image/repository nếu chỉ dùng lab.

## Ghi chú kỹ thuật

ECR workflow cần có tag, digest và repository policy rõ ràng. Chỉ dùng tag latest sẽ gây khó khăn khi truy vết image về source commit hoặc release cụ thể.
