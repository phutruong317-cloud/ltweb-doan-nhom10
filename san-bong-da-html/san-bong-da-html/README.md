# Sân Bóng Thắng Lợi – Bộ khung HTML5 (Phần B)

Bộ khung tĩnh cho website đặt sân bóng đá trực tuyến, chưa dùng CSS/JavaScript
theo đúng yêu cầu đề bài (2.2 Phần B).

## Danh sách trang (7 trang, tối thiểu yêu cầu là 5)

| Trang | Tệp | Nội dung chính |
|---|---|---|
| Trang chủ | `index.html` | Giới thiệu dịch vụ, loại sân, tiện ích |
| Sân & lịch trống | `san-va-lich.html` | Bảng dữ liệu lịch trống theo khung giờ |
| Đặt sân | `dat-san.html` | Form đặt sân có kiểm tra hợp lệ (HTML5) |
| Đăng nhập / Đăng ký | `tai-khoan.html` | Hai form: đăng nhập và đăng ký |
| Lịch sử đặt sân | `lich-su.html` | Bảng lịch sử đơn đặt sân |
| Quản trị | `quan-tri.html` | Sơ đồ sân, bảng giá, thống kê, video hướng dẫn |
| Liên hệ | `lien-he.html` | Thông tin liên hệ, figure, bản đồ iframe |

## Cấu trúc dùng chung mọi trang
- `header` chứa tên hệ thống + `nav` với menu liên kết đủ 7 trang
- `main` với đúng một `h1`, cây tiêu đề không nhảy cấp (h1 → h2)
- `footer` thống nhất: địa chỉ, liên hệ, liên kết nhanh, bản quyền
- Mỗi trang có `title` và `meta description` riêng biệt

## Việc cần làm trước khi nộp
1. Đổi tên repo GitHub thành `ltweb-doan-nhomZZ` (thay ZZ bằng số nhóm) và đẩy các tệp này lên nhánh `main`.
2. Vào **Settings → Pages → Deploy from a branch → main** để bật GitHub Pages công khai.
3. Thay ảnh placeholder trong thư mục `images/` bằng ảnh thật do nhóm chụp/thiết kế, giữ tên tệp không dấu.
4. Thay đường link video/bản đồ mẫu (YouTube, Google Maps) bằng nội dung thật của nhóm nếu có.
5. Chạy kiểm tra W3C Validator cho từng trang và Lighthouse cho trang chủ (Accessibility ≥ 90, SEO ≥ 90), tổng hợp kết quả vào bảng trong báo cáo.
6. Sau khi chương 3–4 hoàn tất, có thể bổ sung CSS/JavaScript riêng trong tệp CSS/JS tách biệt (không chỉnh sửa cấu trúc HTML này).
