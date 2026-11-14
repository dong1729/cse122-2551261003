# Chương 3 — Văn bản và ngữ nghĩa inline

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/5/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Đúng / Sai

Đúng hay sai: b và strong thay thế được nhau trong mọi trường hợp vì cùng thường in đậm?

**Đáp án:**

- Sai

**Giải thích:** Strong thể hiện tầm quan trọng; b không có cùng ý nghĩa đó.

## Câu 2 — Sắp xếp thứ tự

Nêu thứ tự biến một đoạn trích chưa rõ nguồn thành blockquote có liên kết nguồn nhìn thấy được.

**Đáp án:**

1. Xác thực đoạn trích và URL gốc.
2. Đặt đoạn trong blockquote, dùng cite ghi URL.
3. Thêm liên kết nguồn để người đọc bấm được.
4. Thử liên kết và kiểm nguồn đích.

**Giải thích:** Thuộc tính cite không tự tạo một liên kết nguồn nhìn thấy được.

## Câu 3 — Trả lời ngắn / chọn đáp án

Tên tác phẩm được nhắc trong một trích dẫn nên dùng phần tử nào?

**Đáp án:**

- `cite`

**Giải thích:** Cite dùng cho tên tác phẩm, không đơn thuần tên người.

## Câu 4 — Trả lời ngắn / chọn đáp án

Trong `<time ___="2026-02-14">14/2/2026</time>`, thuộc tính còn thiếu là gì?

**Đáp án:**

- `datetime`

**Giải thích:** Datetime chuẩn hóa ngày, tách khỏi cách viết cho người đọc.

## Câu 5 — Trả lời ngắn / chọn đáp án

Một mã dài chỉ nên ngắt tại vài vị trí nếu không đủ chỗ. Nên dùng phần tử nào?

**Đáp án:**

- `wbr`

**Giải thích:** Wbr chỉ cho phép ngắt; br yêu cầu xuống dòng.

## Câu 6 — Đúng / Sai

Đúng hay sai: pre giữ khoảng trắng nhưng các thẻ nằm trong nó vẫn được trình duyệt phân tích?

**Đáp án:**

- Đúng

**Giải thích:** Muốn hiện ký tự mở thẻ trong ví dụ mã cần mã hóa ký tự.

## Câu 7 — Sắp xếp thứ tự

Nêu các bước thêm giá trị thời gian máy đọc cho ngày phát hành đang viết bằng chữ.

**Đáp án:**

1. Đọc chính xác ngày đang hiển thị.
2. Chuẩn hóa thành năm-tháng-ngày.
3. Gắn vào datetime của time bao ngày đó.
4. So giá trị máy đọc với ngày hiển thị.

**Giải thích:** Ngày chuẩn hóa phải khớp ngày thật đang trình bày.

## Câu 8 — Trả lời ngắn / chọn đáp án

Điền thẻ chỉ số dưới để viết công thức nước: `H<___>2</___>O`.

**Đáp án:**

- `sub`

**Giải thích:** Sub là chỉ số dưới; sup dành cho chỉ số trên.

## Câu 9 — Nhiều đáp án

Ghép cảnh báo quan trọng, nhấn giọng và nội dung bổ sung với strong, em, ins như thế nào?

**Đáp án:**

- Cảnh báo nguy hiểm có tầm quan trọng cao — strong
- Nhấn giọng một từ làm thay đổi sắc thái câu — em
- Đánh dấu nội dung được bổ sung trong bản sửa — ins

**Giải thích:** Không dùng nhiều br để tạo khoảng cách bố cục.

## Câu 10 — Nhiều đáp án

Trong time, data, abbr và p, những khai báo nào gắn được dữ liệu hoặc diễn giải chuyên biệt với chữ hiển thị?

**Đáp án:**

- `<time datetime="2026-02-14">14 tháng 2 năm 2026</time>`
- `<data value="9786041234567">978-604-123-456-7</data>`
- `<abbr title="HyperText Markup Language">HTML</abbr>`

**Giải thích:** Trong đề này phải chọn cả abbr có title, ngoài time và data.
