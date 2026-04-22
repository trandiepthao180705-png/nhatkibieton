# 🌸 Nhật Ký Biết Ơn (Gratitude Journal)

> Một ứng dụng web nhỏ gọn (chỉ với 1 file HTML duy nhất) giúp bạn ghi lại những khoảnh khắc tích cực và tươi đẹp mỗi ngày với giao diện pastel bo góc nhẹ nhàng và tràn đầy cảm xúc.

## 📸 Ảnh chụp màn hình

*(Bạn hãy chụp ảnh trang web chạy trên máy của bạn và thay thế tên file `screenshot.png` dưới đây nhé)*

![Giao diện Nhật Ký Biết Ơn](screenshot.png)

## 🚀 Phương pháp sử dụng

Dự án này cực kỳ dễ cài đặt và sử dụng, hoàn toàn không yêu cầu môi trường phức tạp (không cần NodeJS, không cần cài đặt Database hay thao tác qua server).

1. **Tải mã nguồn:** Bạn chỉ cần tải file `index.html` trong repository này về máy tính cá nhân (hoặc `git clone` repo này).
2. **Khởi chạy ứng dụng:** Mở trực tiếp file `index.html` bằng bất kỳ trình duyệt web nào bạn có trên máy (Google Chrome, Safari, Microsoft Edge,...).
3. **Trải nghiệm ghi chép:**
   - Điền một điều khiến bạn mỉm cười hôm nay vào ô nhập liệu.
   - Chọn biểu tượng cảm xúc (Emoji) tương ứng (😊, 🥰, 🌿, ⭐).
   - Bấm **Lưu Lại**. Nhật ký sẽ được lưu tự động trên bộ nhớ trình duyệt và luôn ở đó ngay cả khi bạn tắt máy tĩnh hay khởi động lại trang.
   - Nhấn vào dấu `x` trên mỗi thẻ nếu bạn muốn xóa kỷ niệm đó đi (Có tích hợp hộp thoại xác nhận an toàn).

## ✨ Tính năng nổi bật & Kiến trúc hệ thống
- **Single-file Application**: Toàn bộ cấu trúc (HTML), phong cách (CSS) và logic (JS) đều được viết theo dạng Native/Vanilla và gói gọn vào một file duy nhất, phù hợp cho bài tập lớn nhỏ gọn gọn tại trường học.
- **Hệ lưu trữ LocalStorage**: Thao tác thêm, xóa dữ liệu mượt mà ở phía Client.
- **UX/UI Cảm xúc**: Lấy cảm hứng từ thiết kế Vibrant Palette (Màu hồng pastel, Typography to rõ, thao tác báo lỗi và modal confirm tinh tế tránh giật mình cho người dùng).
