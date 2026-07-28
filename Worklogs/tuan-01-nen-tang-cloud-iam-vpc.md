# Tuần 01 - Nền tảng cloud, IAM Identity Center và VPC

## Mình tập trung vào

Tuần này mình ghi lại các phần đã học, lab đã xem và link workshop cần mở lại khi viết báo cáo.

## Theo ngày

| Ngày | Thời gian | Nội dung thực hiện | Minh chứng trong repo | Workshop/Tài liệu cộng đồng |
| --- | --- | --- | --- | --- |
| Thứ 2 | 15/06/2026 | Onboarding FCAJ, đọc yêu cầu báo cáo, kiểm tra Free Tier/credit và lập thói quen cost guardrail. | [Module 1](../First%20Cloud%20AI%20Journey/Module%201/module-01-ly-thuyet-cloud-account-identity.md)<br>[Lab 01 Free Tier](../First%20Cloud%20AI%20Journey/Module%201/Hands-on%20Labs/lab-01-free-tier-budget-guardrail.md) | [000001 - AWS Free Tier 2025](https://000001.awsstudygroup.com/vi/)<br>[000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/) |
| Thứ 3 | 16/06/2026 | Thực hành IAM Identity Center, group, permission set và CLI credential tạm thời. | [Module 1](../First%20Cloud%20AI%20Journey/Module%201/module-01-ly-thuyet-cloud-account-identity.md)<br>[Lab 12 IAM Identity Center](../First%20Cloud%20AI%20Journey/Module%201/Hands-on%20Labs/lab-12-iam-identity-center.md) | [000012 - AWS IAM Identity Center](https://000012.awsstudygroup.com/vi/)<br>[000002 - Quản trị quyền truy cập với AWS IAM](https://000002.awsstudygroup.com/vi/) |
| Thứ 4 | 17/06/2026 | Thiết kế VPC nền tảng với public/private subnet, route table, Internet Gateway và NAT Gateway. | [Module 2](../First%20Cloud%20AI%20Journey/Module%202/module-02-ly-thuyet-vpc-networking-security.md)<br>[Lab 03 VPC](../First%20Cloud%20AI%20Journey/Module%202/Hands-on%20Labs/lab-03-vpc-site-to-site-vpn.md) | [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/) |
| Thứ 5 | 18/06/2026 | So sánh Security Group/NACL và ghi lại cách dùng VPC Flow Logs để phân tích mạng. | [Module 2](../First%20Cloud%20AI%20Journey/Module%202/module-02-ly-thuyet-vpc-networking-security.md)<br>[Lab 74 Flow Logs](../First%20Cloud%20AI%20Journey/Module%202/Hands-on%20Labs/lab-74-vpc-flow-logs.md) | [000074 - Giám sát hạ tầng mạng với VPC Flow Logs](https://000074.awsstudygroup.com/vi/) |
| Thứ 6 | 19/06/2026 | Tổng hợp mô hình VPC Peering, Transit Gateway, VPN, Direct Connect và các loại Load Balancer. | [Module 2](../First%20Cloud%20AI%20Journey/Module%202/module-02-ly-thuyet-vpc-networking-security.md) | [000003 - Amazon VPC và Site-to-Site VPN](https://000003.awsstudygroup.com/vi/) |

## Ghi chú cuối tuần

- Nắm được luồng bắt đầu một tài khoản AWS: kiểm tra chi phí, bảo vệ root user, sau đó mới tạo quyền truy cập cho công việc hằng ngày.
- VPC cần đọc theo thứ tự CIDR, subnet, route table rồi mới tới security rule; như vậy lúc debug sẽ đỡ rối hơn.
