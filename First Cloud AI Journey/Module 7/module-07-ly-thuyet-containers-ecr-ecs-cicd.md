# Module 07 - Containers, Amazon ECR, ECS Fargate và CI/CD

## Mục đích

Module này nối kiến thức compute với dự án cuối kỳ: Docker image, ECR repository, image tag, scan-on-push, ECS task definition, service, ALB, Fargate, Secrets Manager và pipeline triển khai.

## Ghi chú lý thuyết chính

- Đóng gói ứng dụng thành image có tag truy vết được về commit SHA thay vì chỉ dùng latest.
- Dùng ECR để lưu image private, kiểm soát push/pull bằng IAM và theo dõi digest để xác minh artifact.
- Hiểu ECS task definition, task execution role, task role, log configuration, service deployment và health check qua ALB.
- Tách CI build/scan/push khỏi CD deploy/promote để có điểm kiểm soát bảo mật.

## Cách dùng trong báo cáo

- Dùng trong Week 4 cho ECR/image security.
- Dùng trong Week 5 cho ECS Fargate runtime và Week 6 cho release control.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)
- [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)
- [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)
- [000067 - Monolith to Microservices với Docker, ECS và Fargate](https://000067.awsstudygroup.com/vi/)
- [000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- Amazon ECR User Guide: https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html
- Amazon ECS Developer Guide: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
