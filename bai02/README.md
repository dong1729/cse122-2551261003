# Bai 02 - Hanh trinh Trung Hoa

**Mã nguồn:** [bai02.html](bai02.html) · **Định dạng:** [style.css](style.css).

## Muc tieu

Trình bày trang quảng cáo tour du lịch với nền vàng chuyển sắc, chữ trắng, tiêu đề có bóng và ảnh Vạn Lý Trường Thành nổi bên phải. Nội dung gồm ba đoạn văn giới thiệu hành trình.

## Cau truc

| Thành phần | Vai trò |
| --- | --- |
| `article.banner` | Khung chứa toàn bộ nội dung quảng cáo. |
| `h1` | Tiêu đề trích dẫn, căn giữa và có bóng chữ. |
| `img.anh-noi` | Ảnh nổi bên phải, văn bản bao quanh. |
| `p` | Ba đoạn giới thiệu, căn đều hai lề. |
| `link rel="stylesheet"` | Liên kết HTML với style.css cùng thư mục. |

## Giai thich CSS

- **`max-width: 820px`:** giới hạn chiều rộng khung trên màn hình lớn; `margin: 20px auto` căn giữa theo chiều ngang.
- **`padding: 28px 36px`:** chừa khoảng trống bên trong khung, tránh chữ dính vào mép.
- **`linear-gradient(160deg, #C9A227, #A8861B)`:** tạo nền chuyển từ vàng sáng sang vàng đậm theo góc 160 độ.
- **`color: #ffffff`:** đặt màu chữ trắng cho khung; tiêu đề và đoạn văn kế thừa màu này.
- **`text-shadow`:** tạo bóng nhẹ phía sau chữ tiêu đề; `box-shadow` tạo bóng phía ngoài khung.
- **`text-align: justify`:** căn đều hai lề của các đoạn văn.
- **`float: right`:** đưa ảnh sang phải để chữ chạy bên trái; lề trái 18px giúp chữ không sát ảnh.
- **`overflow: hidden`:** giúp khung bao được ảnh nổi khi ảnh cao hơn phần văn bản.
- **`box-sizing: border-box`:** tính padding và border trong kích thước đã khai báo.

## Man hinh nho

Khi chiều rộng cửa sổ không quá **600px**, `@media` giảm đệm của khung và cỡ tiêu đề. Ảnh bỏ float, chuyển thành một khối ở giữa, rộng tối đa 320px để các đoạn văn nằm bên dưới. Không cần dùng `!important` vì CSS được tách khỏi các thuộc tính style trực tiếp trên HTML.

## Xem va kiem tra

1. Mở bai02.html bằng trình duyệt hoặc Live Server.
2. Trên màn hình lớn, kiểm tra ảnh nằm bên phải và chữ bao quanh bên trái.
3. Thu nhỏ dưới 600px: ảnh ở giữa, các đoạn văn nằm dưới và không tràn ngang.
4. Kiểm tra màu nền, bóng chữ, viền ảnh và đủ ba đoạn nội dung.

Ảnh hiện được tham chiếu bằng đường dẫn tương đối `../Anh/Bai02/greatwall.jpg`. Cần giữ đúng vị trí ảnh khi di chuyển các tệp.
