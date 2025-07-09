# 🛍️ Little Baby Shop - Mini Siêu Thị

Dự án mini siêu thị được xây dựng bằng **React.js** với giao diện thân thiện, dễ sử dụng. Phù hợp để quản lý sản phẩm, đơn hàng và trải nghiệm người dùng cho cửa hàng nhỏ.

## 🚀 Tính năng chính

- 🎨 Giao diện người dùng thân thiện, responsive
- 🛒 Danh sách sản phẩm động
- 📦 Chi tiết sản phẩm và giỏ hàng
- 🔍 Tìm kiếm, phân loại sản phẩm
- 🔐 Đăng nhập/Đăng ký người dùng
- 🌐 Kết nối với API backend

## 📁 Cấu trúc thư mục

src/
├── components/ # Các thành phần giao diện
├── pages/ # Các trang chính như Home, Login, ProductDetail
├── services/ # Gọi API
├── assets/ # Hình ảnh, CSS
└── App.js # File gốc

## ⚙️ Cài đặt & chạy dự án

# 1. Cài đặt dependencies
npm install

# 2. Chạy server phát triển
npm start
Ứng dụng sẽ chạy tại: http://localhost:3000

🧪 Test
npm test

🛠️ Build để triển khai
npm run build
Thư mục build/ sẽ chứa toàn bộ mã nguồn tối ưu hóa sẵn sàng để deploy.

🔗 Công nghệ sử dụng
React.js (Create React App)
React Router
Axios
FontAwesome

💡 Ghi chú
Đây là frontend, kết nối với backend Node.js qua API (/api/...)
Cấu hình proxy trong setupProxy.js nếu cần redirect đến backend
