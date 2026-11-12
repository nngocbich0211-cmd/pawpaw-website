# PawPaw – Website thương mại điện tử (bản demo học tập)

## 1. Chạy thử trên máy tính
1. Giải nén thư mục website.
2. Mở `index.html` bằng Chrome, Edge hoặc Firefox.
3. Cần kết nối Internet để tải font và ảnh từ Google Fonts/Unsplash.

## 2. Các chức năng trong bản demo
- Trang chủ, danh mục, tìm kiếm và sắp xếp sản phẩm.
- Trang chi tiết sản phẩm.
- Cá nhân hóa bắt buộc tên thú cưng đối với vòng cổ, dây dắt, combo và thẻ tên; có thêm trường ghi chú tùy chọn.
- Giỏ hàng, thay đổi số lượng, xóa sản phẩm và lưu giỏ hàng trong trình duyệt bằng localStorage.
- Trang thanh toán demo với thông tin nhận hàng, COD và lựa chọn VietQR mô phỏng.
- Trang giới thiệu, liên hệ và hộp chat mô phỏng.
- Giao diện responsive cho máy tính và điện thoại.

## 3. Cập nhật lên Vercel nhưng giữ nguyên đường link hiện tại
**Không tạo project Vercel mới và không đổi tên project.** Hãy cập nhật source trong đúng GitHub repository đang kết nối với project `pawpaw-website`:

1. Giải nén gói source này trên máy tính.
2. Mở GitHub repository đang được Vercel dùng để triển khai website.
3. Tải lên/ghi đè các tệp trong thư mục gốc: `index.html`, `style.css`, `app.js`, `vercel.json`, `README.md`.
4. Commit thay đổi vào đúng branch Production đang cấu hình (thường là `main`).
5. Mở Vercel Dashboard → project `pawpaw-website` → **Deployments**. Chờ deployment mới có trạng thái **Ready**.
6. Mở lại `https://pawpaw-website.vercel.app/`, tải mới cứng bằng `Ctrl + Shift + R` hoặc mở cửa sổ ẩn danh để kiểm tra phiên bản mới.

Nếu repository hiện tại không còn kết nối, vào Vercel → project `pawpaw-website` → **Settings → Git** để kiểm tra repository và Production Branch trước khi thay đổi. Không xóa project, không tạo project thay thế và không sửa Project Name nếu muốn giữ nguyên URL.

## 4. Giới hạn cần nêu trong báo cáo
Đây là front-end prototype, không phải hệ thống bán hàng production. Dữ liệu sản phẩm được khai báo trong `app.js`; giỏ hàng lưu cục bộ trên trình duyệt hiện tại. Đơn hàng, form liên hệ và chat chưa gửi lên máy chủ. VietQR chỉ là lựa chọn mô phỏng, chưa tạo mã QR thanh toán động hoặc xác nhận giao dịch. Chưa có cơ sở dữ liệu, trang quản trị, tài khoản khách hàng, tích hợp GHN/GHTK/J&T hay quản lý tồn kho. Không nhập dữ liệu cá nhân hoặc thanh toán thật trong bản demo.

Email `support@pawpaw.vn` là thông tin mẫu; thay bằng email doanh nghiệp đã xác thực trước khi công bố. Hình ảnh đang tải từ Unsplash.
