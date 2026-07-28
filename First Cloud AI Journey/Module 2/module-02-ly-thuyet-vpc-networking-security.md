# Module 02 - Amazon VPC, routing và bảo mật mạng

## Mục tiêu kỹ thuật

Phần này gom phần mạng nền tảng: CIDR, subnet public/private, route table, Internet Gateway, NAT Gateway, Security Group, NACL, VPC Flow Logs và các mô hình kết nối giữa VPC hoặc hybrid.

## Nội dung chính

- Thiết kế VPC theo lớp: public subnet cho điểm vào, private subnet cho workload, route table riêng cho từng nhóm subnet.
- Phân biệt Security Group stateful ở cấp tài nguyên với Network ACL stateless ở cấp subnet.
- Dùng Flow Logs để kiểm tra luồng mạng trước khi kết luận lỗi đến từ ứng dụng.
- So sánh VPC Peering, Transit Gateway, VPN, Direct Connect và Elastic Load Balancing theo tình huống sử dụng.

## Ứng dụng trong báo cáo

- Dùng trong Week 1 để mô tả baseline network.
- Dùng lại trong Week 5 khi triển khai ECS Fargate phía sau ALB và trong Week 7 khi lập dashboard mạng.

## Workshop tham khảo

- [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/)
- [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)

## Tài liệu AWS

- Amazon VPC User Guide: https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html
- Elastic Load Balancing User Guide: https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html

## Ghi chú kỹ thuật

- Khi đưa vào báo cáo, cần liên kết khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Với mỗi dịch vụ, nên nêu thêm rủi ro vận hành, lỗi cấu hình thường gặp hoặc điểm kiểm chứng.
