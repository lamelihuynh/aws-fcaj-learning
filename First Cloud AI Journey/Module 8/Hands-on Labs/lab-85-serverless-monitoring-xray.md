# Lab 85 - Monitoring serverless với CloudWatch và X-Ray

## Tài liệu tham khảo

- Workshop: [000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/)

## Mục tiêu

Theo dõi ứng dụng serverless bằng CloudWatch metric/log và X-Ray trace.

## Luồng thực hành

1. Bật log cho Lambda/API nếu chưa có.
2. Tạo lỗi hoặc request mẫu để quan sát metric/error.
3. Bật X-Ray tracing nếu phù hợp và đọc service map/trace.
4. Viết query tìm lỗi theo request id hoặc function name.
5. Ghi lại cách áp dụng cho Lambda aggregator ở dự án cuối kỳ.

## Kiểm chứng

- Có log và metric cho Lambda/API.
- Trace hoặc query giúp tìm điểm lỗi nhanh hơn.
- Cleanup tracing/log không cần thiết sau lab.

## Ghi chú kỹ thuật

Monitoring serverless cần dựa vào CloudWatch Logs, metrics và trace vì không có server để đăng nhập trực tiếp. Request id và trace id giúp lần theo lỗi nhanh hơn.
