# KN TOYS – Cloudflare Pages Profile

Trang link-in-bio độc lập cho KN TOYS, thiết kế theo phong cách Beacons nhưng chạy trực tiếp trên Cloudflare Pages.

## File
- `index.html`
- `style.css`
- `logo.png`
- `zalo-qr.png`

## Deploy từ GitHub lên Cloudflare Pages
1. Tạo repository GitHub mới, ví dụ `kntoys-profile`.
2. Upload toàn bộ file trong thư mục này vào root repository.
3. Cloudflare → Workers & Pages → Create → Pages → Connect to Git.
4. Chọn repository `kntoys-profile`.
5. Framework preset: `None`.
6. Build command: để trống hoặc `exit 0`.
7. Build output directory: `/`.
8. Deploy và kiểm tra địa chỉ `*.pages.dev`.

## Domain dự kiến
Trang được chuẩn bị cho `https://kntoys.vn/profile`.

Lưu ý: nếu `kntoys.vn` hiện đang redirect toàn domain sang Facebook, cần cấu hình routing riêng cho `/profile` để trang này được phục vụ trước redirect chung.
