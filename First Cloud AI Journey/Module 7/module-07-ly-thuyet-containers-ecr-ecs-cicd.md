# Module 07 - Containers, Amazon ECR, ECS Fargate và CI/CD

## Mình học phần này để làm gì

Phần này nối kiến thức compute với dự án cuối kỳ: Docker image, ECR repository, image tag, scan-on-push, ECS task definition, service, ALB, Fargate, Secrets Manager và pipeline triển khai.

## Ý mình cần nhớ

- Đóng gói ứng dụng thành image có tag truy vết được về commit SHA thay vì chỉ dùng latest.
- Dùng ECR để lưu image private, kiểm soát push/pull bằng IAM và theo dõi digest để xác minh artifact.
- Hiểu ECS task definition, task execution role, task role, log configuration, service deployment và health check qua ALB.
- Tách CI build/scan/push khỏi CD deploy/promote để có điểm kiểm soát bảo mật.

## Dùng lại trong báo cáo

- Dùng trong Week 4 cho ECR/image security.
- Dùng trong Week 5 cho ECS Fargate runtime và Week 6 cho release control.

## Workshop mình tham khảo

- [000015 - Triển khai Docker với AWS](https://000015.awsstudygroup.com/vi/)
- [000016 - Triển khai ứng dụng trên Amazon ECS](https://000016.awsstudygroup.com/vi/)
- [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)
- [000067 - Monolith to Microservices với Docker, ECS và Fargate](https://000067.awsstudygroup.com/vi/)
- [000096 - Secrets Manager với Amazon RDS và AWS Fargate](https://000096.awsstudygroup.com/vi/)

## Tài liệu AWS

- Amazon ECR User Guide: https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html
- Amazon ECS Developer Guide: https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html

## Tự nhắc

- Khi đưa vào báo cáo, mình cần gắn khái niệm với lab hoặc quyết định kiến trúc cụ thể.
- Nếu nhắc tới dịch vụ này, mình nên nói thêm một rủi ro hoặc lỗi cấu hình dễ gặp.
