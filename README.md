# 📱 Contact Manager App (Flutter + Firebase)

> 📌 Đồ án cuối kỳ - Công nghệ lập trình đa nền tảng cho ứng dụng di động

---

## 👨‍🎓 Thông tin sinh viên
- **Sinh viên:** Võ Minh Hân  
- **MSSV:** 1050080096  
- **Lớp:** 10_ĐH_CNPM2  
- **Giảng viên hướng dẫn:** ThS. Nguyễn Thanh Truyền  
- **Trường:** Đại học Tài Nguyên và Môi Trường TP.HCM  
- **Niên khóa:** 2021 - 2025  

---

## 📖 Giới thiệu dự án

Ứng dụng **Contact Manager** là một ứng dụng quản lý danh bạ cá nhân, cho phép người dùng:

- Quản lý thông tin liên hệ (CRUD)
- Đăng ký / đăng nhập tài khoản
- Phân quyền người dùng (User / Admin)
- Tìm kiếm và gọi điện trực tiếp
- Đồng bộ dữ liệu thời gian thực với Firebase

---

## 🎯 Mục tiêu

- Xây dựng ứng dụng mobile hoàn chỉnh bằng Flutter  
- Áp dụng Firebase vào xác thực và lưu trữ dữ liệu  
- Hiểu rõ quy trình phát triển ứng dụng thực tế  
- Rèn luyện kỹ năng UI/UX và xử lý logic  

---

## 🛠️ Công nghệ sử dụng

- **Framework:** Flutter  
- **Ngôn ngữ:** Dart  
- **Backend:** Firebase  
  - Firebase Authentication  
  - Cloud Firestore / Realtime Database  
- **Thư viện:**
  - url_launcher (gọi điện)
  - fl_chart / charts_flutter (biểu đồ)

---

## ⚙️ Chức năng chính

### 🔐 1. Xác thực người dùng
- Đăng ký bằng Email/Password
- Đăng nhập
- Đăng nhập bằng Google
- Phân quyền:
  - User
  - Admin

---

### 👤 2. Quản lý danh bạ
- Thêm liên hệ
- Sửa liên hệ
- Xóa liên hệ
- Hiển thị danh sách liên hệ
- Gọi điện trực tiếp từ app

---

### 🔍 3. Tìm kiếm
- Tìm theo tên
- Tìm theo số điện thoại

---

### 🏠 4. Màn hình Home
- Hiển thị danh sách liên hệ
- Thanh tìm kiếm
- Nút thêm liên hệ (+)
- Gọi điện nhanh

---

### 👨‍💼 5. Admin Dashboard
- Xem danh sách người dùng
- Phân quyền (User / Admin)
- Xóa người dùng
- Thống kê số lượng liên hệ
- Hiển thị biểu đồ

---

## 🧩 Kiến trúc hệ thống

Ứng dụng sử dụng mô hình:

- **Frontend:** Flutter UI  
- **Backend:** Firebase  
- **Database:** Firestore  

Luồng hoạt động:
1. User đăng nhập → Firebase Authentication  
2. Lấy dữ liệu từ Firestore  
3. Hiển thị danh bạ realtime  

---

## 🔄 Luồng hoạt động chính
User → Login/Register → Firebase Auth
     → Fetch Data → Firestore
     → Display UI → Flutter
     
---
  
Các màn hình chính
🔹 Đăng ký (Sign Up)

Nhập email + password

Validate dữ liệu

Tạo tài khoản Firebase

🔹 Đăng nhập (Login)

Xác thực tài khoản

Điều hướng:

User → Home

Admin → Dashboard

🔹 Home Screen

Hiển thị danh bạ

Tìm kiếm

Gọi điện

Thêm liên hệ

🔹 Admin Screen

Quản lý người dùng

Thống kê dữ liệu

Xóa tài khoản

📊 Dữ liệu & Firebase

Dữ liệu lưu dưới dạng JSON

Collection chính:

users

contacts

Ví dụ:

{
  "name": "Nguyen Van A",
  "phone": "0123456789",
  "email": "example@gmail.com"
}
🚀 Hướng phát triển

Backup & Restore dữ liệu

Đồng bộ với Google Contacts

Thêm ảnh đại diện

Dark Mode

AI gợi ý liên hệ

📸 Screenshots

![image Alt](https://github.com/hansily14/Flutter/blob/07d2bba9df0ad109a187b49d602e29f7d207afdb/images/Picture1.jpg)

![image Alt](https://github.com/hansily14/Flutter/blob/07d2bba9df0ad109a187b49d602e29f7d207afdb/images/Picture2.jpg)

![image Alt](https://github.com/hansily14/Flutter/blob/07d2bba9df0ad109a187b49d602e29f7d207afdb/images/Picture3.jpg)

📄 Tài liệu chi tiết: file FPF 12_VoMinhHan_1050080096 ở trên



