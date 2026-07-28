# Lab 66 - Lambda, API Gateway và SAM

## Nguồn tham khảo chính

- Workshop gốc: [000066 - Serverless với Lambda, API Gateway và SAM](https://000066.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Hiểu serverless backend với Lambda, API Gateway, S3/DynamoDB/Cognito theo mô hình workshop serverless.

## Luồng thực hành đã viết lại

1. Đọc kiến trúc frontend/backend serverless của workshop.
2. Triển khai function hoặc stack mẫu phạm vi nhỏ.
3. Kiểm tra API Gateway gọi Lambda và log xuất hiện trong CloudWatch.
4. Ghi lại cách event-driven phù hợp với tác vụ xử lý report.
5. Cleanup stack/function/API sau lab.

## Kiểm chứng cần có

- Lambda được invoke thành công.
- Log CloudWatch cho thấy input/output hoặc lỗi.
- Có note về IAM role của Lambda.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
