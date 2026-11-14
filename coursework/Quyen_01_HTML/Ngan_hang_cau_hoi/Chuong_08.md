# Chương 8 — Khả năng truy cập

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/10/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Thông báo giỏ hàng cần chờ trình đọc màn hình đọc xong câu hiện tại. aria-live nên là gì?

**Đáp án:**

- `polite`

**Giải thích:** Polite chờ thời điểm thích hợp thay vì ngắt ngay nội dung đang nghe.

## Câu 2 — Sắp xếp thứ tự

Nêu trình tự đo và sửa cặp màu của nhãn khó đọc trên nền.

**Đáp án:**

1. Lấy màu chữ và nền thực tế.
2. Đo tỉ lệ tương phản.
3. Chọn cặp màu khác khi chưa đạt.
4. Đo lại để kiểm hiệu quả thay đổi.

**Giải thích:** Tương phản cần được đo bằng công cụ.

## Câu 3 — Đúng / Sai

Đúng hay sai: chữ nhìn thấy và tên truy cập của cùng một điều khiển cần thống nhất chức năng?

**Đáp án:**

- Đúng

**Giải thích:** Một điều khiển nên được nhận diện nhất quán bằng mắt và công nghệ hỗ trợ.

## Câu 4 — Nhiều đáp án

Khả năng tiếp cận, kích hoạt, nhìn thấy focus và thoát thành phần cần được kiểm thế nào bằng bàn phím?

**Đáp án:**

- Có thể tới và kích hoạt điều khiển
- Thấy rõ tiêu điểm hiện tại
- Thoát được khỏi thành phần sau khi đi vào

**Giải thích:** Trang trí không cần bị đưa hết vào thứ tự Tab.

## Câu 5 — Trả lời ngắn / chọn đáp án

Thuộc tính ARIA nào nối trường nhập với một đoạn hướng dẫn hoặc lỗi thông qua id?

**Đáp án:**

- `aria-describedby`

**Giải thích:** Giá trị thuộc tính trỏ tới id của đoạn mô tả.

## Câu 6 — Đúng / Sai

Đúng hay sai: người dùng phải có cách rời thành phần đã đi vào bằng bàn phím để tránh bẫy?

**Đáp án:**

- Đúng

**Giải thích:** Hộp thoại phải có cách đóng và trả focus phù hợp.

## Câu 7 — Nhiều đáp án

Khi cập nhật nội dung động, cần chuẩn bị vùng live và chọn thông báo thế nào để tránh quá tải?

**Đáp án:**

- Tạo vùng live trước khi cập nhật nội dung cần thông báo
- Dùng polite cho cập nhật thông thường
- Chỉ thông báo thay đổi có ích với người dùng

**Giải thích:** Chỉ thông báo thay đổi hữu ích; tránh assertive cho sự kiện vụn.

## Câu 8 — Trả lời ngắn / chọn đáp án

Điền aria-live cho thông báo thông thường không ngắt ngay lời đang đọc.

**Đáp án:**

- `polite`

**Giải thích:** Cập nhật thường ngày phù hợp với polite.

## Câu 9 — Sắp xếp thứ tự

Nêu trình tự tái hiện, tìm nguyên nhân và kiểm lại bẫy bàn phím của hộp thoại tự tạo.

**Đáp án:**

1. Ghi chuỗi phím gây kẹt focus.
2. Tìm đoạn xử lý phím hoặc focus gây ra lỗi.
3. Sửa cơ chế đó, thêm cách đóng phù hợp.
4. Lặp lại chuỗi phím để kiểm có thể đóng và thoát.

**Giải thích:** Cần tái hiện được lỗi trước khi tìm và sửa nguyên nhân.

## Câu 10 — Trả lời ngắn / chọn đáp án

Cần script đưa focus tới tóm tắt lỗi nhưng không thêm vùng này vào chuỗi Tab. Dùng tabindex nào?

**Đáp án:**

- `-1`

**Giải thích:** Giá trị âm cho phép script focus nhưng bỏ khỏi chuỗi Tab thông thường.
