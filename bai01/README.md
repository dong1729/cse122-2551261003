# Bai 01 - Trang tho Bon mua

> **Trạng thái:** đã có bài làm. **Tệp chính:** [ex01/index.html](ex01/index.html).

## Muc tieu

Trình bày bài thơ ba khổ bằng HTML có cấu trúc rõ ràng, dùng CSS để căn giữa, tô màu và ngắt dòng đúng đề. Bài này không cần JavaScript hay ảnh ngoài.

## Duong dan nop bai

```text
cse122-2551261003/
└── bai01/
    ├── README.md
    └── ex01/
        └── index.html
```

Nộp URL gốc `https://github.com/dong1729/cse122-2551261003` tại bài 01 trên LMS. Tên và chữ hoa/thường của `bai01/ex01/index.html` phải chính xác. Repo đang riêng tư; giảng viên/hệ thống cần có quyền đọc. Đẩy GitHub chưa có nghĩa là đã bấm nộp trên LMS.

## Doc code theo thu tu

| Phần | Ý nghĩa trong bài |
| --- | --- |
| `head` | UTF-8 giữ dấu tiếng Việt, viewport hỗ trợ màn hình nhỏ, title đặt tên thẻ trình duyệt. |
| `:root` | Lưu các màu vào biến CSS như `--mau-do` và `--mau-xanh`, giúp đổi một chỗ dùng nhiều nơi. |
| `body` | Flexbox đưa khung thơ ra giữa trang theo hai chiều. |
| `article.khung-tho` | Gom một bài thơ hoàn chỉnh; rộng nội dung 640px, đệm 24px, viền 1px. |
| `h1` | Tiêu đề BỐN MÙA, cỡ 26px, chữ đỏ trên nền hồng. |
| `p.kho` | Mỗi đoạn là một khổ thơ; chữ nghiêng, giãn dòng 1.7. |
| `br` | Xuống dòng trong cùng khổ thơ. |
| `hr` | Phân cách hai khổ, rộng 55%, màu xanh. |

## Thong so can nho

- Nền khung: `#FFFDE7`; viền: `#9E9E9E`.
- Nền tiêu đề: `#FFD9E6`; chữ đỏ: `#D40000`; chữ xanh: `#0033CC`.
- Khổ 1 và 3 dùng `class="kho xanh"`; khổ 2 dùng `class="kho do"`.
- Theo CSS content-box, chiều rộng ngoài trên màn hình lớn là `640 + 24 × 2 + 1 × 2 = 690px`.

## Cach mo va tu kiem tra

1. Mở `ex01/index.html` trong VS Code, chọn **Open with Live Server** hoặc mở trực tiếp trong trình duyệt.
2. Đọc đủ 9 câu thơ; đối chiếu ba khổ và hai đường kẻ.
3. Thu nhỏ cửa sổ: khung không tràn ngang, chữ vẫn đọc được.
4. Mở mã nguồn và thử giải thích vì sao dùng `p` để chia khổ, còn `br` để chia câu.

## Tu on lai

- Vì sao `article` phù hợp với một bài thơ độc lập?
- `padding` khác `margin` ở đâu trong khung này?
- Vì sao thay màu trong `:root` giúp sửa bài dễ hơn?

Bản `bai01.html` ở thư mục ngoài đã được bỏ vì trùng nội dung với tệp nộp. Chỉ sửa **một bản chính** tại `ex01/index.html`.
