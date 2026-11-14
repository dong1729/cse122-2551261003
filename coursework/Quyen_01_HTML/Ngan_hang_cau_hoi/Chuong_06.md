# Chương 6 — Hình ảnh và đa phương tiện

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/8/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

## Câu 1 — Trả lời ngắn / chọn đáp án

Ảnh co giãn được khai báo width=400 và height=600 để làm gì trước khi tải xong?

**Đáp án:**

- Cho trình duyệt biết tỉ lệ để dự trữ không gian trước khi ảnh tải

**Giải thích:** Tỉ lệ 2:3 giúp dành chỗ trước và giảm dịch chuyển bố cục.

## Câu 2 — Trả lời ngắn / chọn đáp án

Phần tử nào chứa chú thích nằm trong figure?

**Đáp án:**

- `figcaption`

**Giải thích:** Figcaption là chú thích của cả khối figure.

## Câu 3 — Đúng / Sai

Đúng hay sai: không có alt và có alt rỗng luôn mang cùng ý nghĩa trợ năng?

**Đáp án:**

- Sai

**Giải thích:** Alt rỗng chủ động bỏ qua ảnh trang trí; thiếu alt không nói điều đó.

## Câu 4 — Đúng / Sai

Đúng hay sai: srcset 1x/2x phù hợp khi cùng nội dung và kích thước hiển thị nhưng khác mật độ điểm ảnh?

**Đáp án:**

- Đúng

**Giải thích:** Mô tả x dùng cho mật độ; không trộn với w trong cùng srcset.

## Câu 5 — Sắp xếp thứ tự

Nêu thứ tự sửa lỗi nội dung bị dịch chuyển vì ảnh chưa được dành chỗ.

**Đáp án:**

1. Dùng tải chậm để nhận diện ảnh gây nhảy bố cục.
2. Đọc kích thước gốc của ảnh.
3. Khai báo width/height đúng tỉ lệ.
4. Tải chậm lại để kiểm ảnh đã có chỗ trước khi về.

**Giải thích:** Kích thước cần đúng tỉ lệ nội tại, không chỉ thêm con số bất kỳ.

## Câu 6 — Trả lời ngắn / chọn đáp án

Muốn màn hình hẹp dùng ảnh cắt cận, màn hình rộng dùng ảnh toàn cảnh, nên dùng cơ chế nào?

**Đáp án:**

- picture với source có media

**Giải thích:** Đây là art direction: thay cách cắt/bố cục ảnh theo media.

## Câu 7 — Sắp xếp thứ tự

Nêu quy trình tạo phụ đề tiếng Việt có mốc thời gian rồi gắn vào video.

**Đáp án:**

1. Chép lời và xác định thời điểm từng đoạn.
2. Tạo WebVTT từ lời và mốc đã ghi.
3. Gắn `<track>` tới tệp, đặt srclang="vi".
4. Phát video, so phụ đề với lời thoại.

**Giải thích:** Phụ đề phải có cả văn bản lẫn mốc thời gian đúng.

## Câu 8 — Nhiều đáp án

Video có lời thoại cần những thành phần nào để người dùng điều khiển và đọc phụ đề?

**Đáp án:**

- controls để người dùng điều khiển
- track với src trỏ tệp WebVTT
- srclang để chỉ ngôn ngữ phụ đề

**Giải thích:** Poster là ảnh chờ, không tự sinh nội dung lời thoại.

## Câu 9 — Nhiều đáp án

Ảnh đầu trang và ảnh ở xa khung nhìn ban đầu nên được ưu tiên hoặc tải chậm như thế nào?

**Đáp án:**

- Tránh lazy-load ảnh chủ đạo cần xuất hiện ngay
- Cân nhắc loading="lazy" cho ảnh xa khung nhìn ban đầu
- Khai báo kích thước để giữ chỗ

**Giải thích:** Chỉ ưu tiên ảnh quan trọng; ảnh bên dưới có thể trì hoãn.

## Câu 10 — Trả lời ngắn / chọn đáp án

Phần mở rộng của tệp phụ đề WebVTT là gì, viết không kèm dấu chấm?

**Đáp án:**

- `vtt`

**Giải thích:** Tệp phụ đề dùng định dạng WebVTT.
