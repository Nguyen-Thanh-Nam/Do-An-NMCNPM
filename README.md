# Đồ Án Nhập Môn Công Nghệ Phần Mềm

## Website Bán Hàng Thời Trang

### Mục tiêu dự án
Thiết kế và xây dựng một website thương mại điện tử đơn giản trong lĩnh vực thời trang, có đầy đủ chức năng cơ bản để phục vụ người dùng và quản trị viên.

### Tính năng chính

#### Người dùng
- Đăng ký, đăng nhập
- Duyệt sản phẩm theo danh mục
- Tìm kiếm, xem chi tiết sản phẩm
- Thêm sản phẩm vào giỏ hàng
- Đặt hàng, xem lịch sử đơn hàng
- Xem các bài viết, khuyến mãi, và đánh giá sản phẩm

#### Quản trị viên
- Quản lý sản phẩm, danh mục
- Quản lý tài khoản người dùng
- Bảo trì đơn hàng, bài viết, khuyến mãi
- Thống kê và xuất báo cáo

### Công nghệ sử dụng
- **JSP/Servlet**: Xử lý logic backend và giao tiếp cơ sở dữ liệu
- **Bootstrap**: Thiết kế giao diện đẹp mắt, responsive
- **MySQL**: Lưu trữ dữ liệu hệ thống
- **Java**: Ngôn ngữ chính cho logic xử lý và điều hướng

### Cấu trúc hệ thống
- Frontend: Trang chủ, trang danh mục, trang sản phẩm, giỏ hàng, bài viết
- Backend: Trang quản trị với các chức năng bảo trì và thống kê
- CSDL: Thiết kế theo mô hình UML với các bảng như `SAN_PHAM`, `DON_HANG`, `KHUYEN_MAI`, `KHACH_HANG`, v.v.

### Hướng phát triển tương lai
- Tích hợp cổng thanh toán trực tuyến (MoMo, VNPay)
- Bổ sung chatbot hỗ trợ người dùng
- Cải thiện bảo mật, xác thực đa yếu tố
- Tối ưu giao diện cho thiết bị di động

