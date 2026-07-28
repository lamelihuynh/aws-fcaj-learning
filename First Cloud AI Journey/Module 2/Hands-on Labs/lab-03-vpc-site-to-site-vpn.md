# Lab 03 - VPC public/private subnet và kết nối mạng

## Nguồn tham khảo chính

- Workshop gốc: [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/)

## Mục tiêu cá nhân

Thiết kế VPC cơ bản và hiểu routing, Internet Gateway, NAT Gateway, Security Group, NACL và mô hình VPN theo workshop.

## Luồng thực hành đã viết lại

1. Tạo hoặc vẽ lại VPC CIDR, public subnet và private subnet.
2. Gắn Internet Gateway cho public route và NAT Gateway cho private outbound nếu cần.
3. Tạo security group theo chiều truy cập tối thiểu.
4. Triển khai EC2 kiểm thử để xác nhận public/private routing.
5. Ghi lại điểm khác nhau giữa route table, SG và NACL khi troubleshooting.

## Kiểm chứng cần có

- Public instance truy cập được từ internet theo rule cho phép.
- Private instance không nhận inbound trực tiếp từ internet.
- Có bảng kiểm tra route table/subnet association trước khi kết luận lỗi ứng dụng.

## Ghi chú cho báo cáo

Lab này không sao chép nguyên văn workshop gốc. Nội dung được dùng như minh chứng cá nhân: tôi ghi lại mục tiêu, điểm cần kiểm chứng, lỗi cần tránh và cleanup sau khi thực hành. Khi đưa vào Worklog, link reference phải trỏ về đúng file lab này và workshop AWS Study Group tương ứng.
