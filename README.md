🛍️ Laravel E-Commerce Platform
📖 Giới thiệu

Đây là dự án Website Thương mại điện tử được phát triển bằng Laravel, do một mình tôi thực hiện.
Ứng dụng mô phỏng hệ thống bán hàng trực tuyến cơ bản, với đầy đủ tính năng từ quản lý sản phẩm, giỏ hàng, thanh toán, đến quản lý người dùng (admin và khách hàng).

🚀 Công nghệ sử dụng

Framework: Laravel 11

Ngôn ngữ: PHP, Blade Template, JavaScript

Cơ sở dữ liệu: MySQL (qua XAMPP hoặc Laragon)

Giao diện: Bootstrap 5 / TailwindCSS (tùy bạn chọn)

Quản lý phiên bản: Git & GitHub

Server cục bộ: XAMPP

💡 Tính năng chính
👥 Người dùng (Khách hàng)

Đăng ký, đăng nhập, đăng xuất

Xem danh sách sản phẩm

Tìm kiếm, lọc sản phẩm theo danh mục

Thêm sản phẩm vào giỏ hàng

Xem chi tiết sản phẩm

Thanh toán đơn hàng

🛠️ Quản trị viên (Admin)

Đăng nhập với quyền quản trị

Quản lý sản phẩm (thêm, sửa, xóa)

Quản lý danh mục

Quản lý người dùng

Xem và xử lý đơn hàng

⚙️ Cài đặt & Chạy dự án
1️⃣ Clone dự án về máy
git clone https://github.com/leducvu192005/laravel-ecommerce-platform.git
cd laravel-ecommerce-platform

2️⃣ Cài đặt thư viện
composer install

3️⃣ Tạo file cấu hình môi trường
cp .env.example .env

4️⃣ Cấu hình database trong file .env

Ví dụ:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ecommerce_db
DB_USERNAME=root
DB_PASSWORD=


Sau đó chạy:

php artisan key:generate

5️⃣ Tạo database & chạy migration
php artisan migrate --seed


--seed để thêm dữ liệu mẫu nếu có.

6️⃣ Chạy server Laravel
php artisan serve


Mở trình duyệt tại:

http://127.0.0.1:8000

🧑‍💻 Tác giả

Lê Đức Vũ
Sinh viên Trường Đại học Phenikaa
Email: 23010608@st.phenikaa-uni.edu.vn

GitHub: @leducvu192005

🌐 Tương lai phát triển

Thêm chức năng thanh toán online (VNPAY, Momo)

Giao diện thân thiện hơn (Vue.js hoặc React)

API phục vụ ứng dụng di động

Tích hợp hệ thống đánh giá và bình luận sản phẩm

🏷️ Giấy phép
