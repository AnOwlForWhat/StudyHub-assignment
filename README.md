# StudyHub assignment

StudyHub là bài demo quản lý tài liệu học tập bằng Spring Boot và Thymeleaf. Đây là bản khởi đầu: ứng dụng chạy được và hiển thị trang chào tại `/`. Chức năng quản lý tài liệu và hai thư viện UI sẽ được thêm trong các bước tiếp theo.

## Chạy bản khởi đầu

Cần JDK 17+ và Maven 3.9+. Tại thư mục repo, chạy:

```powershell
mvn spring-boot:run
```

Mở <http://localhost:8080>. Nếu cổng 8080 bận, có thể đổi cổng bằng biến môi trường `PORT`.

## Cấu trúc hiện tại

- `pom.xml`: cấu hình Spring Boot 4.1.2, Spring MVC và Thymeleaf.
- `StudyHubApplication.java`: điểm khởi chạy ứng dụng.
- `HomeController.java`: route `/` trả về trang Thymeleaf.
- `templates/index.html`: trang chào ban đầu.

## Các bước dự kiến tiếp theo

1. Tích hợp Bootstrap và DataTables vào giao diện Thymeleaf.
2. Thêm model, repository, service, controller để quản lý tài liệu.
3. Bổ sung lưu tệp, kiểm thử và hướng dẫn sử dụng bằng DOCX.
