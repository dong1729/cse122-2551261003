# Chương 4 — Liên kết, URL và điều hướng

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/6/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Điều khiển chỉ mở hộp xem nhanh, không chuyển trang, nên dùng cấu trúc HTML nào?

**Đáp án:**

- `<button type="button">Xem nhanh</button>`

**Giải thích:** Hành động tại chỗ nên dùng button, không giả liên kết.

## Câu 2 — Đúng / Sai

Đúng hay sai: :target có thể tạo kiểu cho phần tử được fragment của URL trỏ tới?

**Đáp án:**

- Đúng

**Giải thích:** Fragment chọn một phần tử làm đích trong tài liệu.

## Câu 3 — Đúng / Sai

Đúng hay sai: a không có href vẫn giữ đầy đủ hành vi liên kết khi dùng bàn phím?

**Đáp án:**

- Sai

**Giải thích:** Không có href thì a không còn đầy đủ hành vi liên kết gốc.

## Câu 4 — Trả lời ngắn / chọn đáp án

Muốn liên kết tới `id="thong-so"` trong cùng tài liệu thì href là gì?

**Đáp án:**

- `#thong-so`

**Giải thích:** Dấu # mở đầu phần fragment của URL.

## Câu 5 — Sắp xếp thứ tự

Nêu trình tự tạo skip link khi trang chưa có vùng đích được định danh.

**Đáp án:**

1. Chọn vùng main cần đi tới.
2. Gắn id duy nhất cho vùng này.
3. Tạo liên kết đầu trang trỏ tới id.
4. Dùng bàn phím kích hoạt và kiểm đích.

**Giải thích:** Đích phải có trước để liên kết trỏ đúng nơi.

## Câu 6 — Trả lời ngắn / chọn đáp án

Liên kết tới trang kết quả tiếp theo cần giá trị rel nào?

**Đáp án:**

- `next`

**Giải thích:** Next mô tả quan hệ với trang kế tiếp.

## Câu 7 — Nhiều đáp án

Breadcrumb, skip link và phân trang giải quyết ba nhu cầu điều hướng nào?

**Đáp án:**

- Breadcrumb — thể hiện vị trí trong cấu trúc website
- Skip link — bỏ qua các khối lặp để tới nội dung chính
- Phân trang — di chuyển giữa các phần của danh sách kết quả

**Giải thích:** Ba thành phần giải quyết vị trí, bỏ khối lặp và chia kết quả.

## Câu 8 — Trả lời ngắn / chọn đáp án

Tại `https://sach.example/kho/chi-tiet.html`, không có base, `../gio-hang.html` trỏ tới đâu?

**Đáp án:**

- `https://sach.example/gio-hang.html`

**Giải thích:** Dấu .. lùi một cấp thư mục từ URL hiện tại.

## Câu 9 — Sắp xếp thứ tự

Nêu thứ tự sửa liên kết neo đang tới sai vùng vì có nhiều id trùng nhau.

**Đáp án:**

1. Tìm các phần tử trùng id với fragment.
2. Chọn vùng đúng và đặt id duy nhất.
3. Sửa href theo id mới.
4. Thử liên kết, kiểm vùng được đưa tới.

**Giải thích:** Mỗi id cần duy nhất để fragment không trỏ nhầm.

## Câu 10 — Nhiều đáp án

Các dạng mailto:, tel: và đường dẫn bắt đầu bằng / được dùng vào việc gì?

**Đáp án:**

- mailto:hotro@sach.example — liên hệ qua ứng dụng email
- tel:+84912345678 — gọi số điện thoại trên thiết bị hỗ trợ
- /gio-hang.html — tính đường dẫn từ gốc của origin

**Giải thích:** Đường dẫn có / đầu tính từ origin; ../ là đường dẫn tương đối.
