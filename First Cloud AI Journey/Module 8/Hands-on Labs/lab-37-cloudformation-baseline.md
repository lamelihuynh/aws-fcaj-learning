# Lab 37 - CloudFormation baseline và drift awareness

## Tài liệu tham khảo

- Workshop: [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)

## Mục tiêu

Làm quen Infrastructure as Code bằng CloudFormation template và hiểu drift detection ở mức cơ bản.

## Luồng thực hành

1. Đọc cấu trúc template: Parameters, Resources, Outputs.
2. Triển khai stack nhỏ như S3/IAM/Lambda hoặc tài nguyên workshop.
3. Cập nhật template có kiểm soát thay vì sửa tay nhiều lần.
4. Chạy hoặc ghi chú drift detection để biết tài nguyên lệch khỏi template.
5. Cleanup stack để xóa tài nguyên cùng nhóm.

## Kiểm chứng

- Stack tạo thành công và có output rõ ràng.
- Hiểu vì sao IaC giúp tái lập lab/workshop.
- Cleanup bằng stack deletion an toàn.

## Ghi chú

CloudFormation giúp mình gom tài nguyên vào một stack dễ tạo lại và dễ xóa. Phần này sẽ dùng lại khi nói về IaC và drift trong release flow.
