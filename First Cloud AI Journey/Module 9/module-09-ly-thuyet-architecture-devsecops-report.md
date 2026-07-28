# Module 09 - Kiến trúc DevSecOps, workshop và báo cáo cuối kỳ

## Mục đích

Module này gom phần tổng hợp cuối: biến các dịch vụ đã học thành kiến trúc DevSecOps có security gate, artifact report, observability, cost cleanup và tài liệu song ngữ có thể trình bày.

## Ghi chú lý thuyết chính

- Mỗi mũi tên trong diagram phải gắn với một permission, network route, event trigger hoặc dữ liệu thực tế.
- Security gate cần có rule rõ ràng: mức finding nào chặn release, evidence lưu ở đâu và ai có quyền xem.
- Workshop cần có prerequisites, expected results, troubleshooting, cleanup và ảnh minh chứng đủ để người khác làm lại.
- Báo cáo cuối kỳ phải tách rõ nội dung học, nội dung tự thực hành và tài liệu tham khảo.

## Cách dùng trong báo cáo

- Dùng trong Week 8 để thiết kế workshop DevSecOps.
- Dùng trong Week 9 để chuẩn hóa Hugo report, reference và checklist bàn giao.

## Phân biệt với file lab

File này chỉ ghi lại phần lý thuyết, thuật ngữ và quyết định kiến trúc. Các thao tác console/CLI, bước kiểm thử, kết quả mong đợi và cleanup được đặt trong thư mục `Hands-on Labs/` để không trộn lẫn giữa học khái niệm và thực hành.

## Workshop cộng đồng đã đối chiếu

- [000007 - Quản lý chi phí với AWS Budgets](https://000007.awsstudygroup.com/vi/)
- [000017 - CI/CD với ECS Container](https://000017.awsstudygroup.com/vi/)
- [000037 - AWS CloudFormation](https://000037.awsstudygroup.com/vi/)
- [000098 - Làm quen với Amazon GuardDuty qua thực hành](https://000098.awsstudygroup.com/vi/)
- [000100 - AWS Elastic Disaster Recovery Workshop](https://000100.awsstudygroup.com/vi/)

## Tài liệu AWS chính thức bổ trợ

- AWS Prescriptive Guidance - DevSecOps best practices: https://docs.aws.amazon.com/prescriptive-guidance/latest/designing-a-devsecops-mechanism/best-practices.html
- AWS Well-Architected Framework: https://docs.aws.amazon.com/wellarchitected/2025-02-25/framework/welcome.html

## Tự kiểm tra

- Tôi có giải thích được khi nào nên dùng dịch vụ này thay vì lựa chọn khác không?
- Tôi có nêu được rủi ro bảo mật hoặc chi phí thường gặp không?
- Tôi có liên kết được kiến thức này với worklog và kiến trúc cuối kỳ không?
