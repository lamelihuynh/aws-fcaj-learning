# Lab 37 - CloudFormation baseline và drift awareness

## Nguồn tham khảo chính

- Workshop gốc: [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Làm quen Infrastructure as Code bằng CloudFormation template và hiểu drift detection ở mức cơ bản.

## Luồng thực hành đã viết lại

1. Đọc cấu trúc template: Parameters, Resources, Outputs.
2. Triển khai stack nhỏ như S3/IAM/Lambda hoặc tài nguyên workshop.
3. Cập nhật template có kiểm soát thay vì sửa tay nhiều lần.
4. Chạy hoặc ghi chú drift detection để biết tài nguyên lệch khỏi template.
5. Cleanup stack để xóa tài nguyên cùng nhóm.

## Kiểm chứng cần có

- Stack tạo thành công và có output rõ ràng.
- Hiểu vì sao IaC giúp tái lập lab/workshop.
- Cleanup bằng stack deletion an toàn.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
