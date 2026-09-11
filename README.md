# Jumpy Hop — Privacy Policy

Trang chính sách quyền riêng tư công khai của app **Jumpy Hop**
(`com.tien.jumpyhop`), bắt buộc phải có để nộp lên Google Play.

👉 https://tienld235.github.io/jumpy-hop-privacy/

Repo này CÔNG KHAI có chủ đích — Google và người dùng phải mở được link.
Nó chỉ chứa đúng một trang HTML tĩnh, không có mã nguồn game.

Mã nguồn game nằm ở repo riêng tư `jumpy-hop`.

## Năm thứ tiếng

Trang có đủ **en, vi, es, pt, id** — đúng bằng số thứ tiếng niêm yết trên
cửa hàng. Có thanh nút chuyển ngôn ngữ ở đầu trang, và trang tự mở sẵn đúng
thứ tiếng của máy người đọc (`navigator.language`).

Gửi thẳng link tới một bản cụ thể bằng phần neo: `.../#es`, `.../#pt`…

**Cả năm bản đều nằm hiện trong HTML, JavaScript chỉ có nhiệm vụ ẩn bớt.**
Nên nếu JS không chạy, người đọc vẫn thấy đủ nội dung (chỉ là phải cuộn),
chứ không bao giờ gặp trang trắng. Thanh nút chuyển thì ngược lại — mặc định
ẩn, chỉ hiện khi JS chạy, vì không có JS thì nút đó bấm cũng vô ích.

Sửa nội dung: sửa `index.html` rồi commit, GitHub Pages tự cập nhật sau
khoảng một phút. Nhớ **tải trang thật về kiểm**, đừng tin lệnh push chạy xong:

```bash
curl -s https://tienld235.github.io/jumpy-hop-privacy/ | grep -c 'data-ma='
```
