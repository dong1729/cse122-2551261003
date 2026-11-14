# Chương 7 — Biểu mẫu chuyên sâu

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/9/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Thuộc tính input nào trở thành tên khóa của dữ liệu gửi lên máy chủ?

**Đáp án:**

- `name`

**Giải thích:** Id nhận diện phần tử; name quyết định tên khóa gửi đi.

## Câu 2 — Trả lời ngắn / chọn đáp án

Thuộc tính nào trên một nút submit cho phép riêng lượt gửi đó bỏ kiểm tra ràng buộc?

**Đáp án:**

- `formnovalidate`

**Giải thích:** Formnovalidate áp cho nút đó, novalidate áp cả form.

## Câu 3 — Trả lời ngắn / chọn đáp án

Form tìm sách chỉ truy vấn dữ liệu và cần URL kết quả chia sẻ được nên dùng method nào?

**Đáp án:**

- `get`

**Giải thích:** Get đưa truy vấn vào URL để chia sẻ và đánh dấu.

## Câu 4 — Trả lời ngắn / chọn đáp án

Input có id=email và name=lien_he. Label cần for=email hay for=lien_he?

**Đáp án:**

- `email`

**Giải thích:** For phải khớp id, không phải name.

## Câu 5 — Nhiều đáp án

Nêu các biện pháp giúp nhập form thuận tiện, rõ lỗi nhưng vẫn phải kiểm dữ liệu ở máy chủ.

**Đáp án:**

- autocomplete với token phù hợp loại thông tin
- Thông báo lỗi bằng văn bản gắn với trường
- Dùng type="email" cho email

**Giải thích:** Ràng buộc phía trình duyệt hỗ trợ nhập đúng nhưng có thể bị vượt qua.

## Câu 6 — Đúng / Sai

Đúng hay sai: các radio trong cùng nhóm có thể có id khác nhau và dùng chung name?

**Đáp án:**

- Đúng

**Giải thích:** Name chung tạo nhóm lựa chọn loại trừ.

## Câu 7 — Nhiều đáp án

Radio, fieldset/legend và optgroup nên được dùng thế nào để nhóm và đặt nhãn đúng?

**Đáp án:**

- fieldset và legend cho nhóm trường cùng chủ đề
- Các radio cùng nhóm dùng chung name
- optgroup nhóm các option theo chủ đề trong select

**Giải thích:** Placeholder không thay được nhãn bền vững.

## Câu 8 — Sắp xếp thứ tự

Trong mỗi lượt nhập, nêu thứ tự kiểm hai mật khẩu và cập nhật lỗi tùy chỉnh.

**Đáp án:**

1. Lấy hai giá trị mật khẩu hiện tại.
2. So sánh hai giá trị.
3. Dùng setCustomValidity để đặt lỗi hoặc xóa bằng chuỗi rỗng.
4. Gọi reportValidity để báo trạng thái mới.

**Giải thích:** Lỗi tùy chỉnh phải được xóa khi hai giá trị đã khớp.

## Câu 9 — Đúng / Sai

Đúng hay sai: POST tự mã hóa nội dung nên dữ liệu nhạy cảm không cần HTTPS?

**Đáp án:**

- Sai

**Giải thích:** HTTPS cung cấp mã hóa đường truyền; POST chỉ đổi cách gửi.

## Câu 10 — Sắp xếp thứ tự

Form gửi POST nhưng mất dữ liệu tệp ảnh. Nêu thứ tự kiểm và bổ sung kiểu mã hóa cần thiết.

**Đáp án:**

1. Xem yêu cầu lỗi trong Network để xác nhận phần tệp thiếu.
2. Đối chiếu form và input file, tìm enctype chưa đúng.
3. Đặt enctype="multipart/form-data".
4. Chọn tệp lại, gửi và kiểm phần tệp trong yêu cầu.

**Giải thích:** Chỉ chuyển method sang post chưa đủ để gửi dữ liệu tệp.
