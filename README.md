# Nguyen Dinh Vu · Portfolio

Static personal portfolio (English / Vietnamese): one `index.html` and black-and-white SEMD screenshots in `img/`.
The SEMD demo plays inline from YouTube when the poster is clicked.

## Đưa lên GitHub Pages

1. Tạo repo **public** trên GitHub tên đúng là `Dinhvu114.github.io`.
2. Đưa toàn bộ thư mục này (`index.html`, `img/`, `README.md`) vào repo:
   - Cách nhanh: trong repo vừa tạo, bấm **Add file → Upload files**, kéo các file vào, bấm **Commit changes**.
   - Hoặc bằng git:
     ```bash
     git init
     git add .
     git commit -m "Add portfolio"
     git branch -M main
     git remote add origin https://github.com/Dinhvu114/Dinhvu114.github.io.git
     git push -u origin main
     ```
3. Vào **Settings → Pages**, phần *Build and deployment* chọn **Deploy from a branch**, branch `main`, thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, trang chạy ở **https://dinhvu114.github.io**.

## Sửa nội dung

- Mọi chữ nằm trong `index.html`. Mỗi đoạn có bản tiếng Anh (nội dung thẻ) và bản tiếng Việt (thuộc tính `data-vi`).
- Đổi video: sửa `data-yt="h-FgXLegwfc"` và link `https://youtu.be/...` ở thẻ `#semd-video`.
- Video YouTube phải để **Công khai** hoặc **Không công khai (Unlisted)** thì mới nhúng được.
