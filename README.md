# PawPaw – Website thương mại điện tử (prototype)

## Chạy thử trên máy tính
1. Giải nén `pawpaw-website.zip`.
2. Mở thư mục `pawpaw-website`.
3. Mở `index.html` bằng trình duyệt (Chrome/Edge).

## Triển khai công khai bằng Vercel (không cần cài đặt)
1. Truy cập https://vercel.com và đăng ký/đăng nhập.
2. Tại trang Dashboard, chọn **Add New → Project**.
3. Chọn **Deploy a new project** / **Browse** hoặc kéo thả thư mục website nếu giao diện Vercel hỗ trợ.
4. Cách ổn định nhất: tạo repository GitHub mới, tải lên 3 tệp `index.html`, `style.css`, `app.js` cùng `vercel.json`, sau đó vào Vercel → Add New → Project → Import Git Repository.
5. Trong phần cấu hình dự án:
   - Framework Preset: **Other**
   - Root Directory: `./`
   - Build Command: để trống
   - Output Directory: `./`
6. Nhấn **Deploy**. Vercel sẽ cấp URL dạng `https://ten-du-an.vercel.app`.
7. Mở URL để kiểm tra website. Mỗi lần cập nhật mã nguồn và push lên GitHub, Vercel tự triển khai lại.

## Lưu ý quan trọng
Đây là front-end prototype: sản phẩm, giá, giỏ hàng và đơn hàng chạy phía trình duyệt. Chưa có cơ sở dữ liệu, quản trị viên, tài khoản khách hàng, lưu đơn hàng lên máy chủ, cổng thanh toán VietQR thật, vận chuyển GHN/GHTK/J&T hoặc chat thời gian thực. Không nhập thông tin thanh toán/nhạy cảm thật vào bản demo.
Hình ảnh sản phẩm đang tải từ Unsplash nên cần Internet. Email liên hệ là nội dung mẫu, hãy thay bằng địa chỉ chính thức trước khi công bố.
