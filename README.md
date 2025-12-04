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
| **LocalStorage** | Lưu trữ thông tin người dùng và giỏ hàng |
| **Responsive Design** | Tối ưu hiển thị trên mọi thiết bị |
| **Visual Studio Code** | Công cụ phát triển chính |

---

## 🗂️ 3. Cấu trúc thư mục

🧠 Thư mục chính

DuAnTMDT/
Chứa toàn bộ mã nguồn và các tệp của dự án BookStore.

**📜 Thư mục js/ – Xử lý logic JavaScript

- api.js: Quản lý dữ liệu sản phẩm và danh mục.

- app.js: Điều khiển luồng hoạt động chính của website.

- auth.js: Quản lý đăng nhập, đăng ký và xác thực người dùng.

- cart.js: Xử lý giỏ hàng, tính tổng tiền và tạo mã QR thanh toán.

**🧾 Thư mục pages/ – Các trang con của website

- about.html: Trang giới thiệu về BookStore.

- careers.html: Trang tuyển dụng và form ứng tuyển trực tuyến.

- cart.html: Trang giỏ hàng và thanh toán.

- contact.html: Trang liên hệ trực tiếp.

- feedback.html: Trang gửi phản hồi người dùng.

- guide.html: Trang hướng dẫn mua hàng.

- home.html: Trang chủ của website.

- login.html: Trang đăng nhập tài khoản.

- policy.html: Chính sách bảo mật thông tin.

- products.html: Danh sách tất cả sản phẩm.

- register.html: Trang đăng ký tài khoản mới.

- return.html: Chính sách đổi trả hàng hóa.

- support.html: Gửi yêu cầu hỗ trợ khách hàng.

**🎨 Thư mục styles/ – Giao diện và định dạng CSS

- main.css: Giao diện tổng thể của toàn bộ website.

- responsive.css: Giao diện tối ưu trên điện thoại và tablet.

- variables.css: Chứa các biến màu sắc, font chữ và kích thước dùng chung.

**🏠 Các tệp khác

- index.html: Trang khởi đầu (trang chính của website).

- README.md: Tệp mô tả chi tiết dự án (thông tin, hướng dẫn, cấu trúc, tác giả).

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

## 🧠 6. Ghi chú

Dự án được thực hiện với mục đích **học tập và minh họa** cho môn **Thương Mại Điện Tử**.  
Tất cả hình ảnh, nội dung và dữ liệu trong website chỉ mang tính mô phỏng, **không dùng cho mục đích thương mại**.

---

✨ *“BookStore – Nơi tri thức được lan tỏa qua từng trang sách.”* ✨
