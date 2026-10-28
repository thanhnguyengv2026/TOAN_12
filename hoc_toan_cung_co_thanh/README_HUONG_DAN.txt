HỌC TOÁN CÙNG CÔ THANH — HƯỚNG DẪN NHANH

1. CẤU TRÚC THƯ MỤC
- index.html: trang chủ
- tai-lieu.html: trang tài liệu
- de-thi.html: trang đề thi và đáp án
- kien-thuc.html: trang kiến thức trọng tâm
- video.html: trang video
- lien-he.html: trang liên hệ
- css/style.css: màu sắc, cỡ chữ, giao diện
- tai-lieu/: nơi cô có thể để file PDF
- de-thi/: nơi cô có thể để file đề/đáp án
- video/: thư mục dành cho ghi chú/link video

2. ĐƯA WEBSITE LÊN NETLIFY (CÁCH ĐƠN GIẢN)
- Giải nén file ZIP này vào máy tính.
- Mở https://app.netlify.com/ và đăng nhập/tạo tài khoản.
- Tìm mục thêm site mới hoặc Netlify Drop (giao diện có thể thay đổi).
- Kéo thả thư mục hoc_toan_cung_co_thanh đã giải nén vào vùng tải website.
- Đợi Netlify triển khai xong và mở đường link .netlify.app được cấp.
- Giữ lại thư mục gốc để lần sau sửa và tải lại.

3. CÁCH THAY LINK GOOGLE DRIVE
- Tải PDF lên Google Drive.
- Nhấn Chia sẻ > quyền truy cập chung > Bất kỳ ai có đường liên kết > Người xem.
- Sao chép link chia sẻ.
- Mở file HTML liên quan bằng Notepad hoặc VS Code.
- Tìm LINK_GOOGLE_DRIVE (hoặc LINK_DE_THI, LINK_DAP_AN, LINK_VIDEO_1...).
- Thay đúng chữ LINK_... trong dấu ngoặc kép bằng link thật; giữ nguyên dấu ngoặc kép.
Ví dụ:
<a href="https://drive.google.com/file/d/ID_FILE/view" target="_blank" rel="noopener">Xem tài liệu</a>

4. CÁCH THÊM FILE PDF TRỰC TIẾP VÀO WEBSITE
- Sao chép PDF vào thư mục tai-lieu.
- Trong file tai-lieu.html, dùng link như:
<a href="tai-lieu/cong-thuc-toan-12.pdf" target="_blank">Mở bảng công thức</a>
- Tên file trong link phải giống chính xác tên file thật.

5. CÁCH SỬA NỘI DUNG
- Nhấp phải file HTML > Open with > Notepad.
- Chỉ sửa chữ hiển thị hoặc đường link trong dấu ngoặc kép.
- Lưu lại (Ctrl+S), sau đó tải lại toàn bộ thư mục lên Netlify.
- Nếu sửa giao diện/màu sắc, mở css/style.css.

6. LƯU Ý
- Không đổi tên index.html.
- Không xóa thư mục css.
- Không dùng đường dẫn kiểu C:\\Users\\... vì học sinh trên mạng không truy cập được.
- Nên ưu tiên link Google Drive/YouTube để website nhẹ và tải nhanh.
- Thử mở trang bằng điện thoại và cửa sổ ẩn danh trước khi gửi link cho học sinh.
- Không đưa thông tin cá nhân riêng tư hoặc danh sách điểm của học sinh lên trang công khai.
