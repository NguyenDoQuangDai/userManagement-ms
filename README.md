# User Management Microservice

## 📌 Giới thiệu
`userManagement-ms` là một **microservice** phục vụ cho việc quản lý người dùng trong hệ thống [Furnitica-Ecommerce](https://github.com/SamehSerag/Furnitica-Ecommerce).  
Dịch vụ này chịu trách nhiệm xử lý các nghiệp vụ liên quan đến **tài khoản người dùng**, bao gồm đăng ký, đăng nhập, phân quyền, và quản lý thông tin cá nhân.

## ⚙️ Chức năng chính
- **Đăng ký người dùng mới**  
- **Xác thực đăng nhập** (authentication)  
- **Phân quyền & quản lý vai trò** (authorization & role management)  
- **Cập nhật thông tin cá nhân**  
- **Quản lý danh sách người dùng** (CRUD operations)  
- **Tích hợp với các microservice khác** trong hệ thống Furnitica-Ecommerce  

## 🏗️ Kiến trúc
- Được xây dựng theo mô hình **Microservices**.  
- Giao tiếp với các dịch vụ khác thông qua **REST API**.  
- Hỗ trợ mở rộng và tích hợp dễ dàng với hệ thống thương mại điện tử.

## ⚡ Technologies and Libraries
- **Java 17**  
- **Spring Boot 3**  
- **Spring Security**  
- **JWT**  
- **MySQL**  
