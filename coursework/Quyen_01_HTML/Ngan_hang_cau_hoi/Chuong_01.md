# Chương 1 — Tài liệu HTML và metadata

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/3/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Trong cấu hình viewport, `width` cần nhận giá trị nào để khổ bố cục theo thiết bị?

**Đáp án:**

- `device-width`

**Giải thích:** Viewport nói về kích thước bố cục, không phải định dạng tệp.

## Câu 2 — Đúng / Sai

Đúng hay sai: thêm `lang="vi"` có thể sửa một tệp đang lưu sai bảng mã?

**Đáp án:**

- Sai

**Giải thích:** lang mô tả ngôn ngữ; charset và dữ liệu byte là việc khác.

## Câu 3 — Sắp xếp thứ tự

Từ hồ sơ sách mới, hãy nêu thứ tự tạo và kiểm tra title, description riêng cho trang sách.

**Đáp án:**

1. Lấy tên sách và ý chính từ hồ sơ.
2. Viết title và description theo nội dung đó.
3. Đưa metadata vào head.
4. Mở trang, so lại với hồ sơ sách.

**Giải thích:** Metadata phải xuất phát từ chính cuốn sách đang hiển thị.

## Câu 4 — Đúng / Sai

Đúng hay sai: tài liệu thiếu DOCTYPE vẫn có thể hiển thị nhưng dùng chế độ tương thích ngược?

**Đáp án:**

- Đúng

**Giải thích:** Trang hiển thị được chưa chứng minh đang dựng theo chuẩn.

## Câu 5 — Sắp xếp thứ tự

Muốn kiểm chứng tác dụng của DOCTYPE trên một bản sao HTML, cần làm các bước nào?

**Đáp án:**

1. Đo document.compatMode khi bản sao còn thiếu DOCTYPE.
2. Chèn `<!DOCTYPE html>` ở đầu bản sao.
3. Tải lại và đọc compatMode lần nữa.
4. So sánh trước và sau thay đổi.

**Giải thích:** Chỉ thay DOCTYPE để phép so sánh có ý nghĩa.

## Câu 6 — Nhiều đáp án

Khi sửa head của nhà sách, nên xử lý charset, title và viewport như thế nào?

**Đáp án:**

- Đặt charset sớm trong head
- Đặt title mô tả riêng từng trang
- Khai báo khung nhìn theo bề rộng thiết bị

**Giải thích:** Charset sớm, tên trang riêng và viewport đúng giải quyết các vấn đề khác nhau.

## Câu 7 — Trả lời ngắn / chọn đáp án

Dùng khai báo nào để đề xuất một URL chính cho nhiều URL theo dõi có cùng nội dung?

**Đáp án:**

- `<link rel="canonical" href="https://sach.example/sach/web">`

**Giải thích:** Canonical đề xuất bản đại diện, không tự chuyển hướng.

## Câu 8 — Trả lời ngắn / chọn đáp án

Trang chính bằng tiếng Việt có đoạn “Read more”. Đánh dấu ngôn ngữ đoạn này ra sao?

**Đáp án:**

- `<span lang="en">Read more</span>`

**Giải thích:** Ngôn ngữ có thể được ghi đè ở phần tử con.

## Câu 9 — Nhiều đáp án

Ngôn ngữ tài liệu có ích cho phát âm, chính tả và ngắt từ như thế nào?

**Đáp án:**

- Lựa chọn phát âm của trình đọc màn hình
- Kiểm tra chính tả theo ngôn ngữ
- Ngắt từ tự động theo ngôn ngữ

**Giải thích:** Ngôn ngữ ảnh hưởng cách xử lý chữ, không tự đổi bảng mã.

## Câu 10 — Trả lời ngắn / chọn đáp án

Thẻ nào đặt tên trang xuất hiện trên tab trình duyệt?

**Đáp án:**

- `title`

**Giải thích:** title nằm trong head và khác tiêu đề h1 ở phần nội dung.
