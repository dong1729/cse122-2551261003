# 80 câu hỏi và đáp án — chương 1–8

## Chương 1 — Tài liệu HTML và metadata

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/3/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Trong cấu hình viewport, `width` cần nhận giá trị nào để khổ bố cục theo thiết bị?

**Đáp án:**

- `device-width`

**Giải thích:** Viewport nói về kích thước bố cục, không phải định dạng tệp.

### Câu 2 — Đúng / Sai

Đúng hay sai: thêm `lang="vi"` có thể sửa một tệp đang lưu sai bảng mã?

**Đáp án:**

- Sai

**Giải thích:** lang mô tả ngôn ngữ; charset và dữ liệu byte là việc khác.

### Câu 3 — Sắp xếp thứ tự

Từ hồ sơ sách mới, hãy nêu thứ tự tạo và kiểm tra title, description riêng cho trang sách.

**Đáp án:**

1. Lấy tên sách và ý chính từ hồ sơ.
2. Viết title và description theo nội dung đó.
3. Đưa metadata vào head.
4. Mở trang, so lại với hồ sơ sách.

**Giải thích:** Metadata phải xuất phát từ chính cuốn sách đang hiển thị.

### Câu 4 — Đúng / Sai

Đúng hay sai: tài liệu thiếu DOCTYPE vẫn có thể hiển thị nhưng dùng chế độ tương thích ngược?

**Đáp án:**

- Đúng

**Giải thích:** Trang hiển thị được chưa chứng minh đang dựng theo chuẩn.

### Câu 5 — Sắp xếp thứ tự

Muốn kiểm chứng tác dụng của DOCTYPE trên một bản sao HTML, cần làm các bước nào?

**Đáp án:**

1. Đo document.compatMode khi bản sao còn thiếu DOCTYPE.
2. Chèn `<!DOCTYPE html>` ở đầu bản sao.
3. Tải lại và đọc compatMode lần nữa.
4. So sánh trước và sau thay đổi.

**Giải thích:** Chỉ thay DOCTYPE để phép so sánh có ý nghĩa.

### Câu 6 — Nhiều đáp án

Khi sửa head của nhà sách, nên xử lý charset, title và viewport như thế nào?

**Đáp án:**

- Đặt charset sớm trong head
- Đặt title mô tả riêng từng trang
- Khai báo khung nhìn theo bề rộng thiết bị

**Giải thích:** Charset sớm, tên trang riêng và viewport đúng giải quyết các vấn đề khác nhau.

### Câu 7 — Trả lời ngắn / chọn đáp án

Dùng khai báo nào để đề xuất một URL chính cho nhiều URL theo dõi có cùng nội dung?

**Đáp án:**

- `<link rel="canonical" href="https://sach.example/sach/web">`

**Giải thích:** Canonical đề xuất bản đại diện, không tự chuyển hướng.

### Câu 8 — Trả lời ngắn / chọn đáp án

Trang chính bằng tiếng Việt có đoạn “Read more”. Đánh dấu ngôn ngữ đoạn này ra sao?

**Đáp án:**

- `<span lang="en">Read more</span>`

**Giải thích:** Ngôn ngữ có thể được ghi đè ở phần tử con.

### Câu 9 — Nhiều đáp án

Ngôn ngữ tài liệu có ích cho phát âm, chính tả và ngắt từ như thế nào?

**Đáp án:**

- Lựa chọn phát âm của trình đọc màn hình
- Kiểm tra chính tả theo ngôn ngữ
- Ngắt từ tự động theo ngôn ngữ

**Giải thích:** Ngôn ngữ ảnh hưởng cách xử lý chữ, không tự đổi bảng mã.

### Câu 10 — Trả lời ngắn / chọn đáp án

Thẻ nào đặt tên trang xuất hiện trên tab trình duyệt?

**Đáp án:**

- `title`

**Giải thích:** title nằm trong head và khác tiêu đề h1 ở phần nội dung.

## Chương 2 — Cấu trúc nội dung và heading

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/4/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Đúng / Sai

Đúng hay sai: một article được phép có header giới thiệu riêng?

**Đáp án:**

- Đúng

**Giải thích:** Header có thể thuộc phạm vi bài viết, không chỉ toàn trang.

### Câu 2 — Trả lời ngắn / chọn đáp án

Một bài đánh giá có thể xuất bản độc lập nên được bọc bằng phần tử nào?

**Đáp án:**

- `article`

**Giải thích:** Nội dung độc lập phù hợp article.

### Câu 3 — Sắp xếp thứ tự

Nêu trình tự thay div bằng một phần tử ngữ nghĩa dựa trên nội dung thực.

**Đáp án:**

1. Đọc nội dung, nhận diện vai trò của khối.
2. Chọn thẻ phù hợp vai trò.
3. Thay div, giữ nội dung.
4. Rà DOM và vai trò trong cây trợ năng.

**Giải thích:** Chọn thẻ sau khi hiểu chức năng nội dung.

### Câu 4 — Sắp xếp thứ tự

Từ đề cương bài viết, cần làm gì trước và sau khi gán cấp heading?

**Đáp án:**

1. Liệt kê mục và mục con.
2. Xác định quan hệ cha–con.
3. Gán cấp heading từ quan hệ đó.
4. Đọc lại cây heading, sửa chỗ sai cấp.

**Giải thích:** Cấp heading phản ánh quan hệ nội dung.

### Câu 5 — Trả lời ngắn / chọn đáp án

Khối chính sách vận chuyển có tiêu đề nhưng không phải bài độc lập nên dùng thẻ gì?

**Đáp án:**

- `section`

**Giải thích:** Section gom chủ đề, thường có heading phù hợp.

### Câu 6 — Nhiều đáp án

Menu chính, mục lục bài dài và phân trang có phù hợp đặt trong nav không?

**Đáp án:**

- Menu chính tới các khu vực của website
- Mục lục liên kết tới các phần trong bài dài
- Thanh điều hướng phân trang danh mục

**Giải thích:** Nav dành cho nhóm liên kết điều hướng có ý nghĩa.

### Câu 7 — Đúng / Sai

Đúng hay sai: đổi h2 thành h4 chỉ vì muốn chữ nhỏ hơn là lựa chọn ngữ nghĩa đúng?

**Đáp án:**

- Sai

**Giải thích:** Dùng CSS để đổi cỡ chữ, giữ cấp heading đúng.

### Câu 8 — Trả lời ngắn / chọn đáp án

Phần tử nào đánh dấu nội dung chính, riêng của một trang?

**Đáp án:**

- `main`

**Giải thích:** Main giúp xác định và đi thẳng tới nội dung cốt lõi.

### Câu 9 — Nhiều đáp án

Vai trò trợ năng thông thường của nav, main và aside lần lượt là gì?

**Đáp án:**

- nav — navigation
- main — main
- aside — complementary

**Giải thích:** Các thẻ này có vai trò ngầm định tương ứng.

### Câu 10 — Trả lời ngắn / chọn đáp án

Thông tin liên hệ của tác giả hoặc đơn vị phụ trách tài liệu dùng phần tử nào?

**Đáp án:**

- `address`

**Giải thích:** Address là thông tin liên hệ, không phải mọi địa chỉ nhắc trong bài.

## Chương 3 — Văn bản và ngữ nghĩa inline

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/5/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Đúng / Sai

Đúng hay sai: b và strong thay thế được nhau trong mọi trường hợp vì cùng thường in đậm?

**Đáp án:**

- Sai

**Giải thích:** Strong thể hiện tầm quan trọng; b không có cùng ý nghĩa đó.

### Câu 2 — Sắp xếp thứ tự

Nêu thứ tự biến một đoạn trích chưa rõ nguồn thành blockquote có liên kết nguồn nhìn thấy được.

**Đáp án:**

1. Xác thực đoạn trích và URL gốc.
2. Đặt đoạn trong blockquote, dùng cite ghi URL.
3. Thêm liên kết nguồn để người đọc bấm được.
4. Thử liên kết và kiểm nguồn đích.

**Giải thích:** Thuộc tính cite không tự tạo một liên kết nguồn nhìn thấy được.

### Câu 3 — Trả lời ngắn / chọn đáp án

Tên tác phẩm được nhắc trong một trích dẫn nên dùng phần tử nào?

**Đáp án:**

- `cite`

**Giải thích:** Cite dùng cho tên tác phẩm, không đơn thuần tên người.

### Câu 4 — Trả lời ngắn / chọn đáp án

Trong `<time ___="2026-02-14">14/2/2026</time>`, thuộc tính còn thiếu là gì?

**Đáp án:**

- `datetime`

**Giải thích:** Datetime chuẩn hóa ngày, tách khỏi cách viết cho người đọc.

### Câu 5 — Trả lời ngắn / chọn đáp án

Một mã dài chỉ nên ngắt tại vài vị trí nếu không đủ chỗ. Nên dùng phần tử nào?

**Đáp án:**

- `wbr`

**Giải thích:** Wbr chỉ cho phép ngắt; br yêu cầu xuống dòng.

### Câu 6 — Đúng / Sai

Đúng hay sai: pre giữ khoảng trắng nhưng các thẻ nằm trong nó vẫn được trình duyệt phân tích?

**Đáp án:**

- Đúng

**Giải thích:** Muốn hiện ký tự mở thẻ trong ví dụ mã cần mã hóa ký tự.

### Câu 7 — Sắp xếp thứ tự

Nêu các bước thêm giá trị thời gian máy đọc cho ngày phát hành đang viết bằng chữ.

**Đáp án:**

1. Đọc chính xác ngày đang hiển thị.
2. Chuẩn hóa thành năm-tháng-ngày.
3. Gắn vào datetime của time bao ngày đó.
4. So giá trị máy đọc với ngày hiển thị.

**Giải thích:** Ngày chuẩn hóa phải khớp ngày thật đang trình bày.

### Câu 8 — Trả lời ngắn / chọn đáp án

Điền thẻ chỉ số dưới để viết công thức nước: `H<___>2</___>O`.

**Đáp án:**

- `sub`

**Giải thích:** Sub là chỉ số dưới; sup dành cho chỉ số trên.

### Câu 9 — Nhiều đáp án

Ghép cảnh báo quan trọng, nhấn giọng và nội dung bổ sung với strong, em, ins như thế nào?

**Đáp án:**

- Cảnh báo nguy hiểm có tầm quan trọng cao — strong
- Nhấn giọng một từ làm thay đổi sắc thái câu — em
- Đánh dấu nội dung được bổ sung trong bản sửa — ins

**Giải thích:** Không dùng nhiều br để tạo khoảng cách bố cục.

### Câu 10 — Nhiều đáp án

Trong time, data, abbr và p, những khai báo nào gắn được dữ liệu hoặc diễn giải chuyên biệt với chữ hiển thị?

**Đáp án:**

- `<time datetime="2026-02-14">14 tháng 2 năm 2026</time>`
- `<data value="9786041234567">978-604-123-456-7</data>`
- `<abbr title="HyperText Markup Language">HTML</abbr>`

**Giải thích:** Trong đề này phải chọn cả abbr có title, ngoài time và data.

## Chương 4 — Liên kết, URL và điều hướng

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/6/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Điều khiển chỉ mở hộp xem nhanh, không chuyển trang, nên dùng cấu trúc HTML nào?

**Đáp án:**

- `<button type="button">Xem nhanh</button>`

**Giải thích:** Hành động tại chỗ nên dùng button, không giả liên kết.

### Câu 2 — Đúng / Sai

Đúng hay sai: :target có thể tạo kiểu cho phần tử được fragment của URL trỏ tới?

**Đáp án:**

- Đúng

**Giải thích:** Fragment chọn một phần tử làm đích trong tài liệu.

### Câu 3 — Đúng / Sai

Đúng hay sai: a không có href vẫn giữ đầy đủ hành vi liên kết khi dùng bàn phím?

**Đáp án:**

- Sai

**Giải thích:** Không có href thì a không còn đầy đủ hành vi liên kết gốc.

### Câu 4 — Trả lời ngắn / chọn đáp án

Muốn liên kết tới `id="thong-so"` trong cùng tài liệu thì href là gì?

**Đáp án:**

- `#thong-so`

**Giải thích:** Dấu # mở đầu phần fragment của URL.

### Câu 5 — Sắp xếp thứ tự

Nêu trình tự tạo skip link khi trang chưa có vùng đích được định danh.

**Đáp án:**

1. Chọn vùng main cần đi tới.
2. Gắn id duy nhất cho vùng này.
3. Tạo liên kết đầu trang trỏ tới id.
4. Dùng bàn phím kích hoạt và kiểm đích.

**Giải thích:** Đích phải có trước để liên kết trỏ đúng nơi.

### Câu 6 — Trả lời ngắn / chọn đáp án

Liên kết tới trang kết quả tiếp theo cần giá trị rel nào?

**Đáp án:**

- `next`

**Giải thích:** Next mô tả quan hệ với trang kế tiếp.

### Câu 7 — Nhiều đáp án

Breadcrumb, skip link và phân trang giải quyết ba nhu cầu điều hướng nào?

**Đáp án:**

- Breadcrumb — thể hiện vị trí trong cấu trúc website
- Skip link — bỏ qua các khối lặp để tới nội dung chính
- Phân trang — di chuyển giữa các phần của danh sách kết quả

**Giải thích:** Ba thành phần giải quyết vị trí, bỏ khối lặp và chia kết quả.

### Câu 8 — Trả lời ngắn / chọn đáp án

Tại `https://sach.example/kho/chi-tiet.html`, không có base, `../gio-hang.html` trỏ tới đâu?

**Đáp án:**

- `https://sach.example/gio-hang.html`

**Giải thích:** Dấu .. lùi một cấp thư mục từ URL hiện tại.

### Câu 9 — Sắp xếp thứ tự

Nêu thứ tự sửa liên kết neo đang tới sai vùng vì có nhiều id trùng nhau.

**Đáp án:**

1. Tìm các phần tử trùng id với fragment.
2. Chọn vùng đúng và đặt id duy nhất.
3. Sửa href theo id mới.
4. Thử liên kết, kiểm vùng được đưa tới.

**Giải thích:** Mỗi id cần duy nhất để fragment không trỏ nhầm.

### Câu 10 — Nhiều đáp án

Các dạng mailto:, tel: và đường dẫn bắt đầu bằng / được dùng vào việc gì?

**Đáp án:**

- mailto:hotro@sach.example — liên hệ qua ứng dụng email
- tel:+84912345678 — gọi số điện thoại trên thiết bị hỗ trợ
- /gio-hang.html — tính đường dẫn từ gốc của origin

**Giải thích:** Đường dẫn có / đầu tính từ origin; ../ là đường dẫn tương đối.

## Chương 5 — Danh sách và bảng dữ liệu

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/7/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Điền thuộc tính để danh sách có thứ tự bắt đầu ở số 5: `<ol ___="5">`.

**Đáp án:**

- `start`

**Giải thích:** Start đặt số bắt đầu cho ol.

### Câu 2 — Đúng / Sai

Đúng hay sai: mỗi dt chỉ được phép có đúng một dd đi theo?

**Đáp án:**

- Sai

**Giải thích:** Danh sách mô tả có thể nhóm nhiều mô tả thích hợp với thuật ngữ.

### Câu 3 — Nhiều đáp án

Khi nào dùng ol, ul và phải đặt danh sách con ở đâu để cấu trúc đúng?

**Đáp án:**

- Danh sách con nằm bên trong li của danh sách cha
- ol dùng cho các bước mà đổi thứ tự làm đổi ý nghĩa
- ul dùng cho tập hợp mục không có thứ tự ngữ nghĩa

**Giải thích:** Danh sách con phải thuộc li, không dùng nó thay cho li.

### Câu 4 — Nhiều đáp án

Caption, thead và tfoot lần lượt làm nhiệm vụ gì trong bảng?

**Đáp án:**

- caption — tên hoặc mô tả bảng
- thead — nhóm hàng tiêu đề
- tfoot — nhóm hàng tổng kết

**Giải thích:** Phân nhóm đúng giúp đọc và hiểu cấu trúc bảng.

### Câu 5 — Trả lời ngắn / chọn đáp án

Phần tử nào đặt tên hoặc mô tả trực tiếp cho một bảng dữ liệu?

**Đáp án:**

- `caption`

**Giải thích:** Caption là tên/mô tả trực tiếp thuộc bảng.

### Câu 6 — Sắp xếp thứ tự

Danh sách con đang đặt trực tiếp dưới ul thay vì thuộc một li. Nêu các bước sửa và kiểm lại.

**Đáp án:**

1. Tìm li cha phù hợp nội dung danh sách con.
2. Đưa danh sách con vào trong li ấy.
3. Chạy kiểm cấu trúc HTML.
4. Đọc kết quả, xác nhận lỗi lồng đã hết.

**Giải thích:** Kiểm định giúp xác nhận cấu trúc sau khi chuyển vị trí.

### Câu 7 — Trả lời ngắn / chọn đáp án

Một hàng có bốn vị trí cột; ô đầu chiếm colspan=3, không có rowspan. Cần thêm mấy ô thường?

**Đáp án:**

- `1`

**Giải thích:** Ba vị trí đã chiếm cộng một vị trí còn lại bằng bốn.

### Câu 8 — Đúng / Sai

Đúng hay sai: reversed đổi chiều đánh số của ol nhưng không đảo thứ tự li trong DOM?

**Đáp án:**

- Đúng

**Giải thích:** Số hiển thị đổi chiều, thứ tự nguồn vẫn giữ nguyên.

### Câu 9 — Sắp xếp thứ tự

Đã biết số cột chuẩn, hãy nêu cách tìm và sửa một hàng lệch do colspan.

**Đáp án:**

1. Liệt kê ô và colspan trong hàng lỗi.
2. Cộng tổng vị trí cột các ô chiếm.
3. So với số cột chuẩn để tìm thừa hoặc thiếu.
4. Sửa cấu trúc hàng rồi rà lại lưới.

**Giải thích:** Colspan biểu thị số vị trí lưới mà ô chiếm.

### Câu 10 — Trả lời ngắn / chọn đáp án

Thông số sách gồm tên thuộc tính và giá trị tương ứng nên dùng cấu trúc danh sách nào?

**Đáp án:**

- dl chứa dt và dd

**Giải thích:** Dt là tên/thuật ngữ, dd là mô tả hoặc giá trị.

## Chương 6 — Hình ảnh và đa phương tiện

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/8/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Ảnh co giãn được khai báo width=400 và height=600 để làm gì trước khi tải xong?

**Đáp án:**

- Cho trình duyệt biết tỉ lệ để dự trữ không gian trước khi ảnh tải

**Giải thích:** Tỉ lệ 2:3 giúp dành chỗ trước và giảm dịch chuyển bố cục.

### Câu 2 — Trả lời ngắn / chọn đáp án

Phần tử nào chứa chú thích nằm trong figure?

**Đáp án:**

- `figcaption`

**Giải thích:** Figcaption là chú thích của cả khối figure.

### Câu 3 — Đúng / Sai

Đúng hay sai: không có alt và có alt rỗng luôn mang cùng ý nghĩa trợ năng?

**Đáp án:**

- Sai

**Giải thích:** Alt rỗng chủ động bỏ qua ảnh trang trí; thiếu alt không nói điều đó.

### Câu 4 — Đúng / Sai

Đúng hay sai: srcset 1x/2x phù hợp khi cùng nội dung và kích thước hiển thị nhưng khác mật độ điểm ảnh?

**Đáp án:**

- Đúng

**Giải thích:** Mô tả x dùng cho mật độ; không trộn với w trong cùng srcset.

### Câu 5 — Sắp xếp thứ tự

Nêu thứ tự sửa lỗi nội dung bị dịch chuyển vì ảnh chưa được dành chỗ.

**Đáp án:**

1. Dùng tải chậm để nhận diện ảnh gây nhảy bố cục.
2. Đọc kích thước gốc của ảnh.
3. Khai báo width/height đúng tỉ lệ.
4. Tải chậm lại để kiểm ảnh đã có chỗ trước khi về.

**Giải thích:** Kích thước cần đúng tỉ lệ nội tại, không chỉ thêm con số bất kỳ.

### Câu 6 — Trả lời ngắn / chọn đáp án

Muốn màn hình hẹp dùng ảnh cắt cận, màn hình rộng dùng ảnh toàn cảnh, nên dùng cơ chế nào?

**Đáp án:**

- picture với source có media

**Giải thích:** Đây là art direction: thay cách cắt/bố cục ảnh theo media.

### Câu 7 — Sắp xếp thứ tự

Nêu quy trình tạo phụ đề tiếng Việt có mốc thời gian rồi gắn vào video.

**Đáp án:**

1. Chép lời và xác định thời điểm từng đoạn.
2. Tạo WebVTT từ lời và mốc đã ghi.
3. Gắn `<track>` tới tệp, đặt srclang="vi".
4. Phát video, so phụ đề với lời thoại.

**Giải thích:** Phụ đề phải có cả văn bản lẫn mốc thời gian đúng.

### Câu 8 — Nhiều đáp án

Video có lời thoại cần những thành phần nào để người dùng điều khiển và đọc phụ đề?

**Đáp án:**

- controls để người dùng điều khiển
- track với src trỏ tệp WebVTT
- srclang để chỉ ngôn ngữ phụ đề

**Giải thích:** Poster là ảnh chờ, không tự sinh nội dung lời thoại.

### Câu 9 — Nhiều đáp án

Ảnh đầu trang và ảnh ở xa khung nhìn ban đầu nên được ưu tiên hoặc tải chậm như thế nào?

**Đáp án:**

- Tránh lazy-load ảnh chủ đạo cần xuất hiện ngay
- Cân nhắc loading="lazy" cho ảnh xa khung nhìn ban đầu
- Khai báo kích thước để giữ chỗ

**Giải thích:** Chỉ ưu tiên ảnh quan trọng; ảnh bên dưới có thể trì hoãn.

### Câu 10 — Trả lời ngắn / chọn đáp án

Phần mở rộng của tệp phụ đề WebVTT là gì, viết không kèm dấu chấm?

**Đáp án:**

- `vtt`

**Giải thích:** Tệp phụ đề dùng định dạng WebVTT.

## Chương 7 — Biểu mẫu chuyên sâu

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/9/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Thuộc tính input nào trở thành tên khóa của dữ liệu gửi lên máy chủ?

**Đáp án:**

- `name`

**Giải thích:** Id nhận diện phần tử; name quyết định tên khóa gửi đi.

### Câu 2 — Trả lời ngắn / chọn đáp án

Thuộc tính nào trên một nút submit cho phép riêng lượt gửi đó bỏ kiểm tra ràng buộc?

**Đáp án:**

- `formnovalidate`

**Giải thích:** Formnovalidate áp cho nút đó, novalidate áp cả form.

### Câu 3 — Trả lời ngắn / chọn đáp án

Form tìm sách chỉ truy vấn dữ liệu và cần URL kết quả chia sẻ được nên dùng method nào?

**Đáp án:**

- `get`

**Giải thích:** Get đưa truy vấn vào URL để chia sẻ và đánh dấu.

### Câu 4 — Trả lời ngắn / chọn đáp án

Input có id=email và name=lien_he. Label cần for=email hay for=lien_he?

**Đáp án:**

- `email`

**Giải thích:** For phải khớp id, không phải name.

### Câu 5 — Nhiều đáp án

Nêu các biện pháp giúp nhập form thuận tiện, rõ lỗi nhưng vẫn phải kiểm dữ liệu ở máy chủ.

**Đáp án:**

- autocomplete với token phù hợp loại thông tin
- Thông báo lỗi bằng văn bản gắn với trường
- Dùng type="email" cho email

**Giải thích:** Ràng buộc phía trình duyệt hỗ trợ nhập đúng nhưng có thể bị vượt qua.

### Câu 6 — Đúng / Sai

Đúng hay sai: các radio trong cùng nhóm có thể có id khác nhau và dùng chung name?

**Đáp án:**

- Đúng

**Giải thích:** Name chung tạo nhóm lựa chọn loại trừ.

### Câu 7 — Nhiều đáp án

Radio, fieldset/legend và optgroup nên được dùng thế nào để nhóm và đặt nhãn đúng?

**Đáp án:**

- fieldset và legend cho nhóm trường cùng chủ đề
- Các radio cùng nhóm dùng chung name
- optgroup nhóm các option theo chủ đề trong select

**Giải thích:** Placeholder không thay được nhãn bền vững.

### Câu 8 — Sắp xếp thứ tự

Trong mỗi lượt nhập, nêu thứ tự kiểm hai mật khẩu và cập nhật lỗi tùy chỉnh.

**Đáp án:**

1. Lấy hai giá trị mật khẩu hiện tại.
2. So sánh hai giá trị.
3. Dùng setCustomValidity để đặt lỗi hoặc xóa bằng chuỗi rỗng.
4. Gọi reportValidity để báo trạng thái mới.

**Giải thích:** Lỗi tùy chỉnh phải được xóa khi hai giá trị đã khớp.

### Câu 9 — Đúng / Sai

Đúng hay sai: POST tự mã hóa nội dung nên dữ liệu nhạy cảm không cần HTTPS?

**Đáp án:**

- Sai

**Giải thích:** HTTPS cung cấp mã hóa đường truyền; POST chỉ đổi cách gửi.

### Câu 10 — Sắp xếp thứ tự

Form gửi POST nhưng mất dữ liệu tệp ảnh. Nêu thứ tự kiểm và bổ sung kiểu mã hóa cần thiết.

**Đáp án:**

1. Xem yêu cầu lỗi trong Network để xác nhận phần tệp thiếu.
2. Đối chiếu form và input file, tìm enctype chưa đúng.
3. Đặt enctype="multipart/form-data".
4. Chọn tệp lại, gửi và kiểm phần tệp trong yêu cầu.

**Giải thích:** Chỉ chuyển method sang post chưa đủ để gửi dữ liệu tệp.

## Chương 8 — Khả năng truy cập

Nguồn đối chiếu: [kết quả đề đã làm](https://vietcodedi.id.vn/textbooks/1/chapters/10/quiz).

Đủ 10 câu của đề đã xuất hiện. Câu hỏi được diễn đạt lại ngắn gọn; đáp án dùng nội dung thay vì chữ cái để không phụ thuộc thứ tự lựa chọn ngẫu nhiên.

### Câu 1 — Trả lời ngắn / chọn đáp án

Thông báo giỏ hàng cần chờ trình đọc màn hình đọc xong câu hiện tại. aria-live nên là gì?

**Đáp án:**

- `polite`

**Giải thích:** Polite chờ thời điểm thích hợp thay vì ngắt ngay nội dung đang nghe.

### Câu 2 — Sắp xếp thứ tự

Nêu trình tự đo và sửa cặp màu của nhãn khó đọc trên nền.

**Đáp án:**

1. Lấy màu chữ và nền thực tế.
2. Đo tỉ lệ tương phản.
3. Chọn cặp màu khác khi chưa đạt.
4. Đo lại để kiểm hiệu quả thay đổi.

**Giải thích:** Tương phản cần được đo bằng công cụ.

### Câu 3 — Đúng / Sai

Đúng hay sai: chữ nhìn thấy và tên truy cập của cùng một điều khiển cần thống nhất chức năng?

**Đáp án:**

- Đúng

**Giải thích:** Một điều khiển nên được nhận diện nhất quán bằng mắt và công nghệ hỗ trợ.

### Câu 4 — Nhiều đáp án

Khả năng tiếp cận, kích hoạt, nhìn thấy focus và thoát thành phần cần được kiểm thế nào bằng bàn phím?

**Đáp án:**

- Có thể tới và kích hoạt điều khiển
- Thấy rõ tiêu điểm hiện tại
- Thoát được khỏi thành phần sau khi đi vào

**Giải thích:** Trang trí không cần bị đưa hết vào thứ tự Tab.

### Câu 5 — Trả lời ngắn / chọn đáp án

Thuộc tính ARIA nào nối trường nhập với một đoạn hướng dẫn hoặc lỗi thông qua id?

**Đáp án:**

- `aria-describedby`

**Giải thích:** Giá trị thuộc tính trỏ tới id của đoạn mô tả.

### Câu 6 — Đúng / Sai

Đúng hay sai: người dùng phải có cách rời thành phần đã đi vào bằng bàn phím để tránh bẫy?

**Đáp án:**

- Đúng

**Giải thích:** Hộp thoại phải có cách đóng và trả focus phù hợp.

### Câu 7 — Nhiều đáp án

Khi cập nhật nội dung động, cần chuẩn bị vùng live và chọn thông báo thế nào để tránh quá tải?

**Đáp án:**

- Tạo vùng live trước khi cập nhật nội dung cần thông báo
- Dùng polite cho cập nhật thông thường
- Chỉ thông báo thay đổi có ích với người dùng

**Giải thích:** Chỉ thông báo thay đổi hữu ích; tránh assertive cho sự kiện vụn.

### Câu 8 — Trả lời ngắn / chọn đáp án

Điền aria-live cho thông báo thông thường không ngắt ngay lời đang đọc.

**Đáp án:**

- `polite`

**Giải thích:** Cập nhật thường ngày phù hợp với polite.

### Câu 9 — Sắp xếp thứ tự

Nêu trình tự tái hiện, tìm nguyên nhân và kiểm lại bẫy bàn phím của hộp thoại tự tạo.

**Đáp án:**

1. Ghi chuỗi phím gây kẹt focus.
2. Tìm đoạn xử lý phím hoặc focus gây ra lỗi.
3. Sửa cơ chế đó, thêm cách đóng phù hợp.
4. Lặp lại chuỗi phím để kiểm có thể đóng và thoát.

**Giải thích:** Cần tái hiện được lỗi trước khi tìm và sửa nguyên nhân.

### Câu 10 — Trả lời ngắn / chọn đáp án

Cần script đưa focus tới tóm tắt lỗi nhưng không thêm vùng này vào chuỗi Tab. Dùng tabindex nào?

**Đáp án:**

- `-1`

**Giải thích:** Giá trị âm cho phép script focus nhưng bỏ khỏi chuỗi Tab thông thường.