# Lab 35 - Data lake baseline trên S3

## Nguồn tham khảo chính

- Workshop gốc: [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Ghi chú mô hình data lake căn bản trên S3 để so sánh với RDS/Redshift/ElastiCache.

## Luồng thực hành đã viết lại

1. Tạo bucket/phân vùng thư mục theo raw/processed/report.
2. Upload file mẫu và đặt metadata/tag nếu cần.
3. Ghi lại cách IAM/bucket policy kiểm soát quyền đọc ghi.
4. So sánh truy vấn batch/analytics với OLTP trên RDS.
5. Cleanup object hoặc lifecycle sau lab.

## Kiểm chứng cần có

- Phân biệt được object storage với database quan hệ.
- Có mapping dịch vụ theo workload dữ liệu.
- Không để dữ liệu lab public ngoài ý muốn.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
