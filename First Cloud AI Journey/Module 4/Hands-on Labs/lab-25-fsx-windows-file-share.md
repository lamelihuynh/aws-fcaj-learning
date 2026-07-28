# Lab 25 - FSx for Windows File Server

## Tài liệu tham khảo

- Workshop: [000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/)

## Mục tiêu

Thực hành file share Windows/SMB được quản lý và hiểu nhu cầu Active Directory/domain-aware workload.

## Luồng thực hành

1. Chuẩn bị VPC, subnet và security group cho Windows/SMB.
2. Tạo FSx file system theo cấu hình lab.
3. Kết nối từ Windows instance hoặc client trong cùng network.
4. Tạo thư mục/file và kiểm tra quyền truy cập.
5. Ghi lại điểm khác FSx với S3 và Storage Gateway.

## Kiểm chứng

- Client mount được file share.
- Security Group chỉ mở port cần thiết.
- Cleanup FSx và instance để tránh chi phí.

## Ghi chú

Lab FSx giúp mình phân biệt file share kiểu Windows/SMB với S3 object storage. Phần cleanup cần chú ý vì FSx để chạy lâu sẽ tốn phí.
