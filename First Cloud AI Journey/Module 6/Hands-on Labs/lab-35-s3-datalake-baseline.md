# Lab 35 - Data lake baseline trên S3

## Tài liệu tham khảo

- Workshop: [000035 - Data Lake on AWS](https://000035.awsstudygroup.com/vi/)

## Mục tiêu

Ghi chú mô hình data lake căn bản trên S3 để so sánh với RDS/Redshift/ElastiCache.

## Luồng thực hành

1. Tạo bucket/phân vùng thư mục theo raw/processed/report.
2. Upload file mẫu và đặt metadata/tag nếu cần.
3. Ghi lại cách IAM/bucket policy kiểm soát quyền đọc ghi.
4. So sánh truy vấn batch/analytics với OLTP trên RDS.
5. Cleanup object hoặc lifecycle sau lab.

## Kiểm chứng

- Phân biệt được object storage với database quan hệ.
- Có mapping dịch vụ theo workload dữ liệu.
- Không để dữ liệu lab public ngoài ý muốn.

## Ghi chú

Data lake trên S3 giúp mình so sánh dữ liệu dạng object với database quan hệ. Phần quan trọng là cách chia raw/processed/report và quyền đọc ghi theo prefix.
