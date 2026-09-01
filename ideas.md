# Ý tưởng thiết kế — HUY Hoàng và Khu Vườn Tri Thức

## Ba hướng thẩm mỹ ban đầu

### Hướng 1: Vườn Nắng Kể Chuyện
**Very Brief Intro:** Minh họa sách tranh 2D với giấy màu, nét vẽ mềm và ánh nắng ấm. Cảm giác như một cuốn truyện gia đình có thể chạm vào.

**Probability:** 0.07

### Hướng 2: Bản Đồ Màu Nước
**Very Brief Intro:** Khu vườn được thể hiện như bản đồ màu nước với các con đường, nhãn dán và mảng màu loang nhẹ. Trải nghiệm yên tĩnh, giàu khám phá và có chiều sâu thủ công.

**Probability:** 0.04

### Hướng 3: Xưởng Khám Phá Sắc Màu
**Very Brief Intro:** Giao diện vui nhộn như bàn thủ công, dùng hình khối giấy cắt, màu tương phản và chuyển động bật nảy có kiểm soát. Năng lượng cao hơn nhưng vẫn giữ nhịp học nhẹ nhàng.

**Probability:** 0.09

## Hướng được chọn: Vườn Nắng Kể Chuyện

### Design Movement
Minh họa **storybook editorial** kết hợp paper-cut collage và gouache mềm, lấy cảm hứng từ sách tranh thiếu nhi hiện đại và bảng hoạt động thủ công trong lớp mầm non.

### Core Principles
1. Mỗi màn hình phải giống một trang truyện có thể chạm, không phải bảng điều khiển khô cứng.
2. Nhân vật và vật thể có silhouette rõ, màu sắc dễ phân biệt và thao tác chạm lớn.
3. Phản hồi luôn ấm áp, khuyến khích thử lại, không làm trẻ xấu hổ.
4. Chi tiết trang trí chỉ hỗ trợ việc học; không cạnh tranh với nhiệm vụ chính.

### Color Philosophy
Nền kem giấy tạo cảm giác an toàn; xanh lá là màu của tiến bộ; xanh trời là màu của tập trung; vàng nắng dành cho phần thưởng; coral ấm đánh dấu tương tác. Signature brand color là **Mầm Xanh #4F9D69**, một xanh lá dịu nhưng đủ riêng để nhận diện khu vườn.

### Layout Paradigm
Bố cục dạng **trang truyện mở rộng**: nhiệm vụ chính nằm trên một tấm thẻ giấy lớn lệch nhẹ khỏi trung tâm, nhân vật đứng ở rìa như đang đồng hành, còn tiến độ chạy thành con đường chấm tròn quanh khu vườn. Tránh lưới thẻ đều tăm tắp và các khối bo tròn lặp lại.

### Signature Elements
- Các mảnh giấy xé mềm làm nền cho nhiệm vụ và lời thoại.
- Con đường chấm tròn dẫn tới ba cánh cửa, mỗi mốc là một hạt giống hoặc ngôi sao.
- Chim Xanh và các nét vẽ nhỏ như tia nắng, lá cây, dấu chấm âm thanh.

### Interaction Philosophy
Chạm là một lời mời khám phá. Kéo–thả có lực hút nhẹ khi gần đúng vị trí; vật thể sai trở về bằng chuyển động mềm; nút nghe lại luôn ở cùng một vị trí; không dùng rung mạnh, âm báo thất bại hoặc màu đỏ cảnh báo.

### Animation
Nhân vật thở rất nhẹ ở trạng thái chờ. Khi nghe, các vòng âm thanh lan chậm quanh biểu tượng loa. Khi đúng, vật thể nhún một lần, một ngôi sao vẽ ra bằng nét vàng rồi tan vào sổ tiến bộ. Khi thử lại, vật thể trượt về vị trí cũ với easing mềm. Chuyển cảnh giữa các khu vực dùng parallax lá cây và giấy, thời lượng ngắn, có thể giảm chuyển động trong Góc của bố mẹ.

### Typography System
Dùng **Baloo 2** hoặc fallback rounded display cho tiêu đề lớn, kết hợp **Nunito Sans** cho hướng dẫn và nội dung. Tiêu đề khu vực đậm, chữ nhiệm vụ lớn và ngắn; không để câu hướng dẫn vượt quá hai dòng trên tablet. Nếu font mạng không tải được, fallback là system sans-serif với trọng lượng rõ ràng.

### Brand Essence
**Bé Học Vui là khu vườn riêng của HUY Hoàng, nơi mỗi lần chạm biến một nỗ lực nhỏ thành một khám phá mới.**

Tính cách: **ấm áp, tò mò, kiên nhẫn**.

### Brand Voice
Headline nói như người thân đang mở một trang truyện: cụ thể, gần gũi và có nhịp nghỉ. CTA dùng động từ nhẹ nhàng, không ra lệnh gấp.

Ví dụ: “Mình mở cánh cửa màu xanh nhé.” và “Nghe một lần, thử một lần, con sẽ tìm ra.”

### Wordmark & Logo
Biểu tượng là một hạt mầm hình giọt nước nằm trong vòng cung như cánh cửa khu vườn; hai chiếc lá tạo thành dấu mở sách. Logo không dùng chữ mặc định, đặt cạnh wordmark viết tay mềm “Bé Học Vui” khi cần.

### Signature Brand Color
**Mầm Xanh #4F9D69** — màu xanh của hạt giống vừa nhú, đại diện cho tiến bộ từng bước và được dùng nhất quán ở nút chính, đường tiến độ và các chi tiết nhận diện.

## Quyết định phạm vi bản đầu

Bản đầu là game web 2D tương tác, ưu tiên màn hình ngang tablet Android nhưng co giãn được. Nội dung gồm khu vườn trung tâm, ba khu học, 10 bài số 1–10, 5 bài cộng trong phạm vi 5, 5 bài chữ/ghép tiếng mẫu có thể thay thế, phần thưởng hạt giống/ngôi sao, lời nhắc nghỉ và Góc của bố mẹ.

Ảnh gia đình chỉ dùng làm tham chiếu để tạo nhân vật hoạt hình 2D; không đưa ảnh gốc vào game. Phần giọng đọc sẽ dùng nội dung có thể thay thế, không coi bản demo là bản phát âm chính thức cho đến khi phụ huynh hoặc giáo viên duyệt.

> Câu hỏi kiểm định xuyên suốt: “Lựa chọn này có làm HUY Hoàng hiểu nhiệm vụ và muốn thử thêm một lần không?”

## Style Decisions

- Tất cả nhân vật gia đình và người đồng hành phải là minh họa 2D gouache/paper-cut với silhouette rõ; không dùng ảnh thật hoặc hiệu ứng checkerboard trong thế giới trẻ em.
- Các lựa chọn học tập được trình bày như cánh cửa, mảnh giấy và vật thể trong câu chuyện; không dùng ba dashboard card đồng đều.
- Biểu tượng, phần thưởng và vật trang trí dùng cùng một ngôn ngữ minh họa thủ công; không dùng emoji làm asset chính.
