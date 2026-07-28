# Lab 66 - Lambda, API Gateway và SAM

## Tài liệu tham khảo

- Workshop: [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/)

## Mục tiêu

Hiểu serverless backend với Lambda, API Gateway, S3/DynamoDB/Cognito theo mô hình workshop serverless.

## Luồng thực hành

1. Đọc kiến trúc frontend/backend serverless của workshop.
2. Triển khai function hoặc stack mẫu phạm vi nhỏ.
3. Kiểm tra API Gateway gọi Lambda và log xuất hiện trong CloudWatch.
4. Ghi lại cách event-driven phù hợp với tác vụ xử lý report.
5. Cleanup stack/function/API sau lab.

## Kiểm chứng

- Lambda được invoke thành công.
- Log CloudWatch cho thấy input/output hoặc lỗi.
- Có note về IAM role của Lambda.

## Ghi chú kỹ thuật

Serverless nên được mô tả theo event source, function, permission và log. Mô hình này phù hợp với tác vụ xử lý report khi có object mới trên S3.
