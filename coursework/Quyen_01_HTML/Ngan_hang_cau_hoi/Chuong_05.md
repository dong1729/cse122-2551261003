# Chương 5 — Danh sách và bảng dữ liệu

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/7/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Điền thuộc tính để danh sách có thứ tự bắt đầu ở số 5: `<ol ___="5">`.

**Đáp án:**

- `start`

**Giải thích:** Start đặt số bắt đầu cho ol.

## Câu 2 — Đúng / Sai

Đúng hay sai: mỗi dt chỉ được phép có đúng một dd đi theo?

**Đáp án:**

- Sai

**Giải thích:** Danh sách mô tả có thể nhóm nhiều mô tả thích hợp với thuật ngữ.

## Câu 3 — Nhiều đáp án

Khi nào dùng ol, ul và phải đặt danh sách con ở đâu để cấu trúc đúng?

**Đáp án:**

- Danh sách con nằm bên trong li của danh sách cha
- ol dùng cho các bước mà đổi thứ tự làm đổi ý nghĩa
- ul dùng cho tập hợp mục không có thứ tự ngữ nghĩa

**Giải thích:** Danh sách con phải thuộc li, không dùng nó thay cho li.

## Câu 4 — Nhiều đáp án

Caption, thead và tfoot lần lượt làm nhiệm vụ gì trong bảng?

**Đáp án:**

- caption — tên hoặc mô tả bảng
- thead — nhóm hàng tiêu đề
- tfoot — nhóm hàng tổng kết

**Giải thích:** Phân nhóm đúng giúp đọc và hiểu cấu trúc bảng.

## Câu 5 — Trả lời ngắn / chọn đáp án

Phần tử nào đặt tên hoặc mô tả trực tiếp cho một bảng dữ liệu?

**Đáp án:**

- `caption`

**Giải thích:** Caption là tên/mô tả trực tiếp thuộc bảng.

## Câu 6 — Sắp xếp thứ tự

Danh sách con đang đặt trực tiếp dưới ul thay vì thuộc một li. Nêu các bước sửa và kiểm lại.

**Đáp án:**

1. Tìm li cha phù hợp nội dung danh sách con.
2. Đưa danh sách con vào trong li ấy.
3. Chạy kiểm cấu trúc HTML.
4. Đọc kết quả, xác nhận lỗi lồng đã hết.

**Giải thích:** Kiểm định giúp xác nhận cấu trúc sau khi chuyển vị trí.

## Câu 7 — Trả lời ngắn / chọn đáp án

Một hàng có bốn vị trí cột; ô đầu chiếm colspan=3, không có rowspan. Cần thêm mấy ô thường?

**Đáp án:**

- `1`

**Giải thích:** Ba vị trí đã chiếm cộng một vị trí còn lại bằng bốn.

## Câu 8 — Đúng / Sai

Đúng hay sai: reversed đổi chiều đánh số của ol nhưng không đảo thứ tự li trong DOM?

**Đáp án:**

- Đúng

**Giải thích:** Số hiển thị đổi chiều, thứ tự nguồn vẫn giữ nguyên.

## Câu 9 — Sắp xếp thứ tự

Đã biết số cột chuẩn, hãy nêu cách tìm và sửa một hàng lệch do colspan.

**Đáp án:**

1. Liệt kê ô và colspan trong hàng lỗi.
2. Cộng tổng vị trí cột các ô chiếm.
3. So với số cột chuẩn để tìm thừa hoặc thiếu.
4. Sửa cấu trúc hàng rồi rà lại lưới.

**Giải thích:** Colspan biểu thị số vị trí lưới mà ô chiếm.

## Câu 10 — Trả lời ngắn / chọn đáp án

Thông số sách gồm tên thuộc tính và giá trị tương ứng nên dùng cấu trúc danh sách nào?

**Đáp án:**

- dl chứa dt và dd

**Giải thích:** Dt là tên/thuật ngữ, dd là mô tả hoặc giá trị.
