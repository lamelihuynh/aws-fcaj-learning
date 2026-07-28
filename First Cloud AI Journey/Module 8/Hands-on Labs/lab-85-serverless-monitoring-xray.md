# Lab 85 - Monitoring serverless với CloudWatch và X-Ray

## Nguồn tham khảo chính

- Workshop gốc: [000085 - Monitoring Serverless app với CloudWatch và X-Ray](https://000085.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Theo dõi ứng dụng serverless bằng CloudWatch metric/log và X-Ray trace.

## Luồng thực hành đã viết lại

1. Bật log cho Lambda/API nếu chưa có.
2. Tạo lỗi hoặc request mẫu để quan sát metric/error.
3. Bật X-Ray tracing nếu phù hợp và đọc service map/trace.
4. Viết query tìm lỗi theo request id hoặc function name.
5. Ghi lại cách áp dụng cho Lambda aggregator ở dự án cuối kỳ.

## Kiểm chứng cần có

- Có log và metric cho Lambda/API.
- Trace hoặc query giúp tìm điểm lỗi nhanh hơn.
- Cleanup tracing/log không cần thiết sau lab.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
