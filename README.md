# 📚 BookStore – Dự án Thương Mại Điện Tử

**BookStore** là website bán sách trực tuyến giúp người dùng dễ dàng tìm kiếm, chọn mua và thanh toán các đầu sách chất lượng.  
Dự án được phát triển trong khuôn khổ môn học **Thương Mại Điện Tử**, tập trung vào trải nghiệm người dùng, tối ưu giao diện và tích hợp thanh toán bằng **mã QR VietQR**.

---

## 🏷️ 1. Giới thiệu

BookStore mang đến một nền tảng mua sách hiện đại, thân thiện và tiện lợi.  
Người dùng có thể:

- 🔍 Duyệt và tìm kiếm sách theo thể loại.  
- 🛒 Thêm sản phẩm vào giỏ hàng và thanh toán qua mã QR.  
- 👤 Đăng ký / đăng nhập tài khoản cá nhân.  
- 💬 Gửi phản hồi, liên hệ hoặc yêu cầu hỗ trợ trực tiếp.  
- 🧾 Xem thông tin về đổi trả, chính sách bảo mật, hướng dẫn mua hàng, và tuyển dụng.

---

## 🧰 2. Công nghệ sử dụng

| Công nghệ | Mục đích |
|------------|-----------|
| **HTML5, CSS3, JavaScript (ES6)** | Xây dựng giao diện và xử lý logic chính |
| **VietQR API** | Tạo mã QR thanh toán tự động theo số tiền |
| **LocalStorage** | Lưu trữ thông tin người dùng và giỏ hàng |
| **Responsive Design** | Tối ưu hiển thị trên mọi thiết bị |
| **Visual Studio Code** | Công cụ phát triển chính |

---

## 🗂️ 3. Cấu trúc thư mục

DuAnTMDT/
│
├── js/ # Xử lý logic JavaScript
│ ├── api.js # Xử lý dữ liệu sản phẩm
│ ├── app.js # Logic chính của website
│ ├── auth.js # Quản lý đăng nhập / đăng ký
│ └── cart.js # Xử lý giỏ hàng và QR thanh toán
│
├── pages/ # Các trang con của website
│ ├── about.html # Giới thiệu BookStore
│ ├── careers.html # Tuyển dụng và form ứng tuyển
│ ├── cart.html # Giỏ hàng & thanh toán
│ ├── contact.html # Liên hệ trực tiếp
│ ├── feedback.html # Phản hồi người dùng
│ ├── guide.html # Hướng dẫn mua hàng
│ ├── home.html # Trang chủ
│ ├── login.html # Đăng nhập tài khoản
│ ├── policy.html # Chính sách bảo mật
│ ├── products.html # Danh sách tất cả sản phẩm
│ ├── register.html # Đăng ký tài khoản
│ ├── return.html # Chính sách đổi trả
│ └── support.html # Gửi yêu cầu hỗ trợ
│
├── styles/ # Định dạng giao diện CSS
│ ├── main.css # Giao diện tổng thể
│ ├── responsive.css # Tối ưu hiển thị trên mobile
│ └── variables.css # Biến màu sắc & font chữ
│
├── index.html # Trang khởi đầu của website
└── README.md # Thông tin mô tả dự án

yaml
Copy code

---

## 🚀 4. Cách chạy dự án

### 🔧 Cách 1: Chạy cục bộ bằng Live Server
1. Mở thư mục dự án bằng **Visual Studio Code**.  
2. Cài tiện ích mở rộng **Live Server** (nếu chưa có).  
3. Nhấn chuột phải vào `index.html` → chọn **Open with Live Server**.  
4. Truy cập: `http://127.0.0.1:5500/DuAnTMDT/index.html`.

### ☁️ Cách 2: Triển khai lên GitHub Pages
1. Push toàn bộ mã nguồn lên GitHub.  
2. Vào **Settings → Pages**.  
3. Chọn branch: `main` → folder `/root` → **Save**.  
4. Truy cập link GitHub Pages được cung cấp (ví dụ:  
   `https://khiem-0806.github.io/Du_An_TMDT/`).

---

## 📄 5. Các tính năng chính

- 👁️ Giao diện hiện đại, nhất quán trên mọi trang.  
- 🛍️ Hệ thống giỏ hàng động (thêm, xóa, cập nhật số lượng).  
- 💸 Thanh toán bằng **mã QR VietQR** tự động tính giá.  
- 🔐 Đăng ký / đăng nhập với xác thực LocalStorage.  
- 📬 Form liên hệ, phản hồi và ứng tuyển.  
- 🧾 Các trang thông tin: giới thiệu, chính sách, đổi trả, hướng dẫn.

---
 
- **Địa điểm:** TP. Hồ Chí Minh, Việt Nam  
- **GitHub:** [https://github.com/Khiem-0806](https://github.com/Khiem-0806)

---

## 🧠 6. Ghi chú

Dự án được thực hiện với mục đích **học tập và minh họa** cho môn **Thương Mại Điện Tử**.  
Tất cả hình ảnh, nội dung và dữ liệu trong website chỉ mang tính mô phỏng, **không dùng cho mục đích thương mại**.

---

✨ *“BookStore – Nơi tri thức được lan tỏa qua từng trang sách.”* ✨
