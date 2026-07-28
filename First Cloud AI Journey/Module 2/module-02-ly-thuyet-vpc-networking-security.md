# Module 02 - Amazon VPC, routing và bảo mật mạng

## Mục đích

Module này gom phần mạng nền tảng: CIDR, subnet public/private, route table, Internet Gateway, NAT Gateway, Security Group, NACL, VPC Flow Logs và các mô hình kết nối giữa VPC hoặc hybrid.

## Ghi chú lý thuyết chính

- Thiết kế VPC theo lớp: public subnet cho điểm vào, private subnet cho workload, route table riêng cho từng nhóm subnet.
- Phân biệt Security Group stateful ở cấp tài nguyên với Network ACL stateless ở cấp subnet.
- Dùng Flow Logs để kiểm tra luồng mạng trước khi kết luận lỗi đến từ ứng dụng.
- So sánh VPC Peering, Transit Gateway, VPN, Direct Connect và Elastic Load Balancing theo tình huống sử dụng.

## Cách dùng trong báo cáo

- Dùng trong Week 1 để mô tả baseline network.
- Dùng lại trong Week 5 khi triển khai ECS Fargate phía sau ALB và trong Week 7 khi lập dashboard mạng.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/)
- [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- Amazon VPC User Guide: https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html
- Elastic Load Balancing User Guide: https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
