# Bai 01 - Trang tho Bon mua

> **Mã nguồn:** [ex01/bai01.html](ex01/bai01.html) · **Nội dung:** thuyết minh bài thực hành HTML/CSS.

## Bai nay lam gi

Hiển thị bài thơ Bốn mùa với ba khổ: khổ đầu và cuối màu xanh, khổ giữa màu đỏ. Tiêu đề nằm trên nền hồng, cả bài nằm trong khung vàng nhạt.

## Cac the HTML dang dung

| Thẻ | Dùng để làm gì trong bài? |
| --- | --- |
| `div` | Gom tiêu đề và ba khổ thơ vào một khung. |
| `h1` | Tiêu đề chính BỐN MÙA. |
| `p` | Mỗi thẻ là một khổ thơ. |
| `br` | Xuống dòng trong cùng một khổ. |
| `hr` | Kẻ đường phân cách giữa hai khổ. |

`head` chứa thông tin về trang; `body` chứa nội dung hiển thị. `meta charset="UTF-8"` giúp hiển thị tiếng Việt đúng dấu.

## Doc CSS theo thu tu

1. **body:** chọn phông chữ và căn khung giữa trang. `justify-content: center` căn ngang; `align-items: center` căn dọc. `min-height: 100vh` giúp trang cao ít nhất bằng cửa sổ trình duyệt.
2. **.khung-tho:** rộng 640px, có đệm 24px, viền xám và nền vàng nhạt. Dấu chấm trước tên nghĩa là chọn phần tử có class tương ứng.
3. **h1:** cỡ chữ 26px, chữ đỏ và nền hồng. Thẻ h1 mặc định đã in đậm.
4. **p:** cả ba khổ mặc định màu xanh, chữ nghiêng và giãn dòng 1.7.
5. **.do:** ghi đè màu chữ cho khổ giữa. Chỉ khổ thứ hai có `class="do"`.
6. **hr:** đường kẻ màu xanh, rộng 55% khung.

## Vi du de hieu class

```html
<p>Khổ này nhận màu xanh từ CSS của p.</p>
<p class="do">Khổ này đổi sang đỏ nhờ class do.</p>
```

`class="do"` là tên do mình đặt, không phải thẻ HTML mới. Có thể đặt tên khác, nhưng phải sửa cả HTML lẫn CSS cho khớp.

## Margin va padding

- `margin`: khoảng cách bên ngoài phần tử, ví dụ khoảng cách sau tiêu đề.
- `padding`: khoảng trống bên trong, giúp chữ không dính sát viền khung.
- Với khung hiện tại, chiều rộng ngoài khi đủ chỗ là `640 + 24 × 2 + 1 × 2 = 690px`. Flexbox có thể co khung lại khi cửa sổ hẹp.

## Cach mo va tu kiem tra

1. Mở `ex01/bai01.html` trong VS Code rồi chọn **Open with Live Server**, hoặc mở trực tiếp bằng trình duyệt.
2. Kiểm tra đủ 9 câu, 3 khổ và 2 đường kẻ ngang.
3. Thử đổi màu của `p`: khổ đầu và cuối đổi màu, khổ giữa vẫn đỏ vì có class riêng.
4. Thử bỏ một thẻ `br` rồi quan sát hai câu thơ có còn xuống dòng không; sau đó khôi phục.
