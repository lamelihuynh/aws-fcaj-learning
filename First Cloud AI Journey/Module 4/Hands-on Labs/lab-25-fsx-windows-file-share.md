# Lab 25 - FSx for Windows File Server

## Nguồn tham khảo chính

- Workshop gốc: [000025 - Triển khai FSx trên Windows](https://000025.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thực hành file share Windows/SMB được quản lý và hiểu nhu cầu Active Directory/domain-aware workload.

## Luồng thực hành đã viết lại

1. Chuẩn bị VPC, subnet và security group cho Windows/SMB.
2. Tạo FSx file system theo cấu hình lab.
3. Kết nối từ Windows instance hoặc client trong cùng network.
4. Tạo thư mục/file và kiểm tra quyền truy cập.
5. Ghi lại điểm khác FSx với S3 và Storage Gateway.

## Kiểm chứng cần có

- Client mount được file share.
- Security Group chỉ mở port cần thiết.
- Cleanup FSx và instance để tránh chi phí.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
