# 🌸 Nhật Ký Biết Ơn (Gratitude Journal)

< Một ứng dụng web nhỏ gọn giúp bạn ghi lại những khoảnh khắc tích cực và tươi đẹp mỗi ngày với giao diện pastel bo góc nhẹ nhàng và tràn đầy cảm xúc.

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
     
## 🌿Tính minh bạch AI 
Ứng dụng web này được thực hiện bởi sự hỗ trợ của Google AI Studio
- Phần tôi trực tiếp thực hiện : thiết kế logic UX, viết câu lệnh Prompt theo cấu trúc CRAFT+CoT, kiểm tra mã nguồn dựa trên lăng kính 3P và yêu cầu chỉnh sửa
- Phần AI thực hiện : tạo cấu trúc HTML/CSS hiện thực hóa logic và xử lí dữ liệu localStorage bằng Javascript, thiết kế phong cách 

## ⭐ Quá trình thực hiện 
1. **Logic UX**:
   - Khi người dùng viết nội dung nhật kí chọn emoji và nhấn nút lưu thì nhật kí đó sẽ được thêm vào danh sách
   - Khi người dùng bấm xóa nhật kí nhật kí sẽ bị xóa 
   - Khi load lại trang , trang vẫn xuất hiện dữ liệu

2. **Prompt CRAFT+CoT**:
-  Context : tôi là sinh viên năm 2 đang học môn công nghệ SW tại trường.
-  Role : bạn là chuyên gia lập trình, nhà thiết kế UX/UI cảm xúc và là nhà phát triển front-end
- Action : tạo web " Nhật kí biết ơn " trong một file HTML duy nhất
- Format: HTML,CSS, JS chung 1 file , giao diện thích ứng với điện thoại
- Tone : sử dụng phong màu fastel ( màu hồng) , có các góc bo tròn tạo cảm giác nhẹ nhàng
- Các bước thực hiện CoT:
1. Tự động hiển thị ngày tháng ở trên cùng
2. Tạo ô nhập, có 4 nút chọn imoji nút lưu
2. Dùng localstorage để lưu và hiển thị danh sách nhật kí bên dưới
4. Hiển thị các mục nhật kí đã lưu, cho phép xóa từng mục
5. Xử lí lỗi nếu người dùng bỏ trống ô nhập

3. **Nội dung chỉnh sửa 3P** :
   - Frompt chỉnh sửa : khi xóa hiển thị câu hỏi có muốn xóa không
   - So sánh trước và sau : trước: khi xóa là nhật kí mất luôn, sau : khi xóa có câu hỏi xác nhận
 
