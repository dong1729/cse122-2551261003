# Chuong 02 - Trung binh: Cau truc ngu nghia

> **Tệp thực hành:** [trung-binh.html](trung-binh.html) · **Yêu cầu và lời giải chung:** [BAI_TAP.md](BAI_TAP.md).

## Bai nay dang lam gi

Ba trang sản phẩm được mở bằng Chromium; dữ liệu từ cây Accessibility của Chrome DevTools Protocol. Không mặc định mọi header/footer lồng trong bài đều là landmark cấp tài liệu.

## Kien thuc chinh

Dùng header, nav, main, section, article và footer theo vai trò; heading phản ánh cấp nội dung.

## Doc ma theo thu tu

1. Đọc `head`: tên trang, mã hóa và tài nguyên đi kèm.
2. Tìm `main` rồi so sánh nội dung trong trình duyệt với các thẻ trong mã.
3. Chú ý các thành phần thực sự có trong tệp dưới đây.

| Thẻ có trong bài | Vai trò cần hiểu |
| --- | --- |
| `nav` | Nhóm các liên kết điều hướng. |
| `section` | Một mục nội dung có chủ đề. |
| `table` | Trình bày dữ liệu có hàng và cột. |

## Cach hoc va tu kiem tra

- Mở `trung-binh.html` bằng **Open with Live Server**. Các ảnh và CSS dùng chung nằm trong `../assets/`.
- Sửa một giá trị hoặc một thẻ, lưu rồi quan sát thay đổi. Sau đó giải thích vì sao giao diện hoặc hành vi đổi.
- Thử ở màn hình hẹp, dùng Tab để đi qua liên kết và ô nhập; quan sát nội dung có đọc được không.
- Đọc thêm [TOM_TAT.md](TOM_TAT.md) và [ON_TAP.md](ON_TAP.md), tự trả lời trước khi xem lại lời giải.

## Pham vi cap nhat

Đây là bài thực hành trong giáo trình. Dự án Nhà sách và các trang liên kết thuộc `du-an/` hiện giữ trên máy, chưa xuất bản cùng tiến độ bài nộp. Những liên kết sang dự án chỉ dùng được khi chạy bản đầy đủ trên máy.
