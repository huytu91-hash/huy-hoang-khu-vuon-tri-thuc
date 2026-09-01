# HUY Hoàng và Khu Vườn Tri Thức — GitHub Pages

## Chạy trên máy
Cài Node.js 22 và pnpm hoặc npm. Trong thư mục này chạy `npm install`, sau đó `npm run dev` để xem bản phát triển.

## Đưa lên GitHub
Tạo repository mới, giải nén gói này, mở terminal tại thư mục gốc rồi chạy `git init`, `git add .`, `git commit -m "Add HUY Hoang learning game"`, `git branch -M main`, `git remote add origin https://github.com/USERNAME/REPOSITORY.git`, và `git push -u origin main`.

## Bật game online
Workflow `.github/workflows/deploy-pages.yml` sẽ tự build và deploy khi push lên nhánh `main`. Trong GitHub mở Settings → Pages, ở mục Build and deployment chọn Source là GitHub Actions. Sau khi workflow hoàn tất, mở đường link Pages được GitHub cung cấp.

Ảnh game đã nằm trong `client/public/assets`, nên không phụ thuộc vào kho lưu trữ WebDev. Các nhân vật là minh họa 2D; ảnh gốc gia đình không có trong gói.
