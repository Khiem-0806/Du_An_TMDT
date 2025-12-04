# 📚 BookStore – Dự án Thương mại điện tử

## 🧭 Giới thiệu

**BookStore** là website thương mại điện tử được phát triển bằng **HTML, CSS và JavaScript thuần**, cho phép người dùng:

- Duyệt và tìm kiếm các đầu sách yêu thích 📖  
- Thêm sản phẩm vào giỏ hàng và **thanh toán qua mã QR động** 💳  
- Đăng ký / đăng nhập tài khoản cá nhân 🔐  
- Đánh giá và bình luận sản phẩm ⭐  
- Gửi phản hồi, liên hệ trực tiếp với cửa hàng 📬  
- Xem thông tin **tuyển dụng**, **chính sách**, **hướng dẫn mua hàng** và **hỗ trợ khách hàng** 👥  

---


## ⚙️ Cấu trúc thư mục

DuAnTMDT/
│
├── js/
│ ├── api.js # Xử lý dữ liệu & danh sách sản phẩm
│ ├── app.js # Logic tổng thể trang web
│ ├── auth.js # Quản lý đăng nhập / đăng ký
│ └── cart.js # Giỏ hàng và thanh toán QR
│
├── pages/
│ ├── about.html
│ ├── careers.html
│ ├── cart.html
│ ├── contact.html
│ ├── feedback.html
│ ├── guide.html
│ ├── home.html
│ ├── login.html
│ ├── policy.html
│ ├── products.html
│ ├── register.html
│ ├── return.html
│ └── support.html
│
├── styles/
│ ├── main.css
│ ├── responsive.css
│ └── variables.css
│
├── index.html
└── README.md

yaml
Copy code

---

## 🚀 Cách chạy dự án

### 🔹 Cách 1: Mở trực tiếp
Tải dự án về và mở file `index.html` bằng trình duyệt (Chrome, Edge, Firefox,…).

### 🔹 Cách 2: Dùng Live Server (Visual Studio Code)
1. Cài extension **Live Server**.  
2. Mở thư mục `DuAnTMDT` trong VS Code.  
3. Chuột phải vào `index.html` → chọn **“Open with Live Server”**.  
4. Truy cập trình duyệt tại địa chỉ hiển thị (thường là `http://127.0.0.1:5500/`).

---

## 💡 Tính năng nổi bật

✅ Giao diện hiện đại, tối ưu cho **desktop và mobile**  
✅ **QR động** hiển thị đúng số tiền cần thanh toán  
✅ Lưu dữ liệu người dùng và giỏ hàng bằng **LocalStorage**  
✅ Form **liên hệ / phản hồi / ứng tuyển** có thông báo cảm ơn (toast popup)  
✅ **Header & Footer** đồng nhất giữa tất cả các trang  
✅ Hiển thị **thông báo đăng nhập, đăng ký, và thanh toán** mượt mà  

---

## 🧠 Công nghệ sử dụng

- **HTML5 / CSS3 / JavaScript (Vanilla JS)**  
- **Flexbox & CSS Grid Layout**  
- **LocalStorage API**  
- **Dynamic QR Generator API**  
- **Responsive Design (main.css & responsive.css)**  

---
 
📍 Việt Nam  
📧 Email: `cskh@bookstore.com`  
🌐 GitHub: [Khiem-0806](https://github.com/Khiem-0806)  
📞 Hotline: 1900 1234 

---

## 📄 Giấy phép

Dự án được xây dựng với mục đích **học tập và thực hành kỹ năng lập trình web**.  
Mọi người có thể sao chép, chia sẻ hoặc chỉnh sửa **cho mục đích phi thương mại**.

---

## 🚧 Định hướng phát triển trong tương lai

- Tích hợp **CSDL thực tế** (MySQL hoặc Firebase)  
- Kết nối với **API thanh toán thực tế (Momo, VNPay, v.v.)**  
- Thêm **trang quản trị (Admin Dashboard)** để quản lý sách & đơn hàng  
- Gửi **email tự động** khi người dùng đăng ký hoặc mua hàng  
