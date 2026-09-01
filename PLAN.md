# PLAN — HUY Hoàng và Khu Vườn Tri Thức

## Mục tiêu
Bản game web 2D tương tác, ưu tiên tablet Android màn hình ngang, dùng nhân vật hoạt hình tham chiếu từ ảnh HUY Hoàng, Ba Tú và Mẹ Tiền.

## Risk slices
- Touch-first navigation giữa khu vườn và ba khu học.
- Nhiệm vụ chọn đáp án với phản hồi không trừng phạt.
- Phát âm tạm thời bằng SpeechSynthesis, nội dung tách khỏi UI để thay bản thu đã duyệt.
- Hiển thị nhân vật PNG và nền minh họa từ xa, không commit asset lớn vào mã nguồn.
- Góc của bố mẹ và báo cáo mô tả không chẩn đoán.

## Tiêu chí kiểm tra
- Có thể mở ba khu học bằng thao tác chạm lớn.
- Có nút nghe lại ở màn hình chính và từng nhiệm vụ.
- Đúng nhận sao/hạt giống; sai chỉ hướng dẫn thử lại.
- Bố cục co giãn trên tablet và mobile.
- Ảnh gia đình chỉ xuất hiện dưới dạng nhân vật minh họa 2D.
- `pnpm check` không có lỗi TypeScript.
