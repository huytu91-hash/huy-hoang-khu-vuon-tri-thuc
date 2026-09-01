# STRUCTURE — HUY Hoàng và Khu Vườn Tri Thức

## Giao diện
`client/src/App.tsx` là khung game và điều phối trạng thái khu vực, nhiệm vụ, phần thưởng và Góc của bố mẹ. `client/src/styles.css` chứa toàn bộ ngôn ngữ hình ảnh storybook, responsive layout và touch targets.

## Nội dung
Các mảng `numberTasks`, `addTasks` và `soundTasks` nằm tách ở đầu App để dễ thay bằng bộ nội dung/giọng đọc đã được phụ huynh hoặc giáo viên duyệt.

## Tài sản
Các nhân vật HUY Hoàng, Ba Tú, Mẹ Tiền, logo, nền khu vườn và minh họa hoạt động dùng URL `/manus-storage/...`, không dùng ảnh gốc gia đình trong giao diện.

## Luồng trạng thái
`garden` hiển thị ba cánh cửa. `numbers`, `addition` và `sounds` là ba màn chơi tương ứng. Mỗi câu trả lời đúng tăng thống kê, sao và hạt giống; câu trả lời chưa đúng chỉ thay lời nhắc và không trừ điểm.

## Riêng tư
Bản hiện tại không có tài khoản, backend, tải ảnh lên hay nhận diện giọng nói. Góc của bố mẹ chỉ hiển thị thống kê trong phiên hiện tại.
