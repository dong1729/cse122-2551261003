# Web Development · CSE122

**Nguyễn Hòa Đông** · Mã sinh viên **2551261003**  
Học phần **Phát triển ứng dụng Web cơ bản**

> Kho bài tập theo tiến độ giảng viên. Mỗi bài có mã nguồn và ghi chú để đọc lại, hiểu cách làm và tự ôn tập.

[Tong quan](#tong-quan) · [Tien do](#tien-do) · [Bai tap](#bai-tap) · [Cach su dung](#cach-su-dung)

---

## Tong quan

Mục tiêu của việc học là tự viết được một trang web có cấu trúc rõ ràng, trình bày đúng đề và giải thích được từng phần trong mã nguồn.

| Phần đang học | Nội dung thực hành |
| :--- | :--- |
| **HTML** | Cấu trúc trang, tiêu đề, đoạn văn, xuống dòng và liên kết. |
| **CSS** | Màu chữ, màu nền, viền, khoảng cách, căn chỉnh và phông chữ. |
| **Thói quen làm bài** | Đọc đề → viết từng phần → chạy thử → đối chiếu → ghi chú. |
| **Git & GitHub** | Lưu các lần sửa và chỉ cập nhật bài tập được chọn. |

## Tien do

**1 / 3 bài đang mở đã có mã nguồn.** Đây là tiến độ làm bài, không phải điểm số hoặc xác nhận đã nộp trên LMS.

| Bài | Nội dung | Mã nguồn | Ghi chú |
| :---: | :--- | :--- | :--- |
| **01** | Trang thơ **Bốn mùa** | **Đã có** | Đã viết lại theo cách cơ bản, có hướng dẫn đọc mã. |
| **02** | Quảng cáo tour du lịch **Hành trình Trung Hoa** | Chưa có | Đã xác nhận tên bài và quy định nộp; cần đọc đề chi tiết. |
| **03** | Giới thiệu **Di sản Vịnh Hạ Long** | Chưa có | Đã xác nhận tên bài; cần đọc đề và quy định đường dẫn. |

**Về việc nộp bài:** chưa có xác nhận nộp thành công trên LMS trong quá trình làm việc này. Đẩy lên GitHub và nộp trên LMS là hai bước riêng.

## Bai tap

### Bai 01 · Bon mua

[Mở mã nguồn](bai01/ex01/bai01.html) · [Đọc hướng dẫn](bai01/README.md)

**Bài đang làm gì?** Trình bày bài thơ gồm ba khổ trong một khung vàng nhạt: tiêu đề trên nền hồng, khổ đầu và cuối màu xanh, khổ giữa màu đỏ.

**Kiến thức chính:** `div`, `h1`, `p`, `br`, `hr` và CSS cơ bản. Màu được viết trực tiếp; mã chia dòng, thụt lề để dễ đọc.

**Tự kiểm tra:** giải thích được vai trò của từng thẻ, phân biệt `margin` và `padding`, hiểu vì sao chỉ khổ giữa đổi màu.

### Bai 02 · Hanh trinh Trung Hoa

**Đang chuẩn bị.** Chưa có lời giải được đưa lên kho. Khi có đủ đề và bài làm, sẽ bổ sung đường dẫn mã nguồn và ghi chú.

### Bai 03 · Di san Vinh Ha Long

**Đang chuẩn bị.** Chưa có lời giải được đưa lên kho. Cần đối chiếu yêu cầu trước khi tạo cấu trúc bài.

## Cau truc repo

```text
cse122-2551261003/
├── README.md                 # Tổng quan và tiến độ
├── SECURITY.md               # Chính sách bảo mật của kho
└── bai01/
    ├── README.md             # Mục tiêu, giải thích và cách tự kiểm tra
    └── ex01/
        └── bai01.html        # Mã nguồn Bài 01
```

Tên tệp và thư mục của từng bài được điều chỉnh theo yêu cầu giảng viên. Bài 02–03 sẽ xuất hiện khi được chọn để cập nhật.

## Cach su dung

1. Mở thư mục **cse122-2551261003** trong VS Code.
2. Chọn bài muốn làm, đọc `README.md` của bài trước rồi mở tệp HTML.
3. Mở HTML trong trình duyệt hoặc dùng **Open with Live Server**.
4. Sửa từng phần nhỏ, lưu và so sánh với đề.
5. Bấm **Push Web…**, chỉ chọn bài tập cần cập nhật.
6. Khi bài sẵn sàng, kiểm tra lại yêu cầu rồi thực hiện bước nộp trên LMS.

## Pham vi cap nhat

| Nội dung | Hiện tại |
| :--- | :--- |
| Bài tập giảng viên giao | Đẩy từng bài được chọn. |
| Bài tập và ghi chú theo chương | Giữ trên máy, sẽ cập nhật sau. |
| Dự án tự học | Giữ trên máy, chưa cập nhật. |

Thư mục `coursework/` không nằm trong bản hiện tại của kho. Các lần cập nhật trước vẫn có trong lịch sử Git.

---

**Repository:** [dong1729/cse122-2551261003](https://github.com/dong1729/cse122-2551261003)  
Kho được giữ **riêng tư**. Khi nộp bài, cần bảo đảm giảng viên hoặc hệ thống chấm bài có quyền đọc kho.
