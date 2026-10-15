# Đếm Doanh Thu — GitHub Pages PWA

## Tải lên GitHub
1. Tạo một repository mới, ví dụ `dem-doanh-thu`.
2. Mở repository → **Add file** → **Upload files**.
3. Kéo thả NỘI DUNG của thư mục này (không tải ZIP lên nguyên dạng): `index.html`, `manifest.webmanifest`, `service-worker.js`, `.nojekyll`, và thư mục `icons`.
4. Nhấn **Commit changes**.
5. Vào **Settings → Pages**.
6. Ở **Build and deployment**, chọn **Deploy from a branch**; Branch `main`, folder `/(root)`; nhấn **Save**.
7. Đợi GitHub Actions triển khai xong, rồi mở URL được hiển thị ở Settings → Pages.

## Cài trên điện thoại
- iPhone: mở URL bằng Safari → Share → Add to Home Screen.
- Android: mở URL bằng Chrome → menu ⋮ → Install app hoặc Add to Home screen.

## Ghi chú
- Repository public là lựa chọn phù hợp với GitHub Free. Nội dung website sẽ công khai trên Internet; không đưa thông tin nhạy cảm vào repository.
- Dữ liệu đếm được lưu cục bộ trong trình duyệt của từng thiết bị; không tự đồng bộ giữa thiết bị.
- Bản HTML gốc sử dụng Tailwind CDN, Font Awesome CDN và Google Fonts. Vì vậy, lần đầu mở và một số kiểu chữ/biểu tượng cần Internet; phần khung trang được cache nhưng không cam kết trải nghiệm ngoại tuyến hoàn toàn.
