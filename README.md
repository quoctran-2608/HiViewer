# HiViewer - Phần mềm Điều khiển Máy tính Từ xa

<p align="center">
  <img src="screenshots/hiviewer.jpg" alt="HiViewer Banner" width="100%">
</p>

**HiViewer** là phần mềm điều khiển máy tính từ xa qua Internet, tương tự TeamViewer và UltraViewer. Được phát triển hoàn toàn bằng C# .NET 8.

## ✨ Tính năng

- 🖥️ **Điều khiển từ xa qua Internet** - Kết nối và điều khiển máy tính từ bất kỳ đâu
- 🖱️ **Điều khiển chuột** - Di chuyển, click, cuộn hoàn toàn mượt mà
- ⌨️ **Điều khiển bàn phím** - Gõ phím, phím tắt hoạt động đầy đủ
- 🔒 **Bảo mật** - Mỗi phiên có ID và Password riêng
- 🖼️ **Chất lượng cao** - JPEG 75% với adaptive quality tự động
- 🛡️ **Hỗ trợ UAC** - Có thể thấy và điều khiển UAC prompts
- 🔄 **Tự động kết nối lại** - Khi mất kết nối sẽ tự động thử kết nối lại
- 🎨 **Giao diện đẹp** - Thiết kế hiện đại theo phong cách TeamViewer

## 📥 Tải về

| Phiên bản | Tải về | Kích thước | Ghi chú |
|-----------|--------|------------|---------|
| **v1.2.2** (Mới nhất) | [HiViewer_Setup_v1.2.2.exe](HiViewer_Setup_v1.2.2.exe) | ~2.6 MB | **Kết nối nhanh + Chất lượng cao** |

**Yêu cầu hệ thống:**
- Windows 10/11 (64-bit)
- .NET 8 Runtime ([Tải tại đây](https://dotnet.microsoft.com/download/dotnet/8.0))
- **Quyền Administrator** (để capture UAC prompts)

## 🆕 Có gì mới trong v1.2.2

### Kết nối nhanh hơn
- **Bỏ delay STUN** - Gửi answer ngay lập tức
- **Pre-initialize capture** - Capture sẵn sàng khi app khởi động
- **Frame đầu tiên tức thì** - GDI capture ngay khi connect
- **Trước: 2-5 giây, Sau: ~100ms**

### Từ v1.2.1
- **JPEG 75%** - Sắc nét hơn nhiều (trước là 45%)
- **Adaptive quality** - Tự động điều chỉnh 40-85% theo bandwidth
- **Target ~80KB/frame** - Cân bằng chất lượng và băng thông
- **Cached encoder** - Nén nhanh hơn

### Hiệu suất tối ưu
- **30 FPS** - Cân bằng tốt hơn 60 FPS
- **Full frame/giây** - Đồng bộ thường xuyên hơn

### Từ v1.2.0
- Hỗ trợ UAC/Secure Desktop
- Yêu cầu quyền Admin

## 🚀 Hướng dẫn sử dụng

### Cài đặt

1. Tải file `HiViewer_Setup_v1.2.1.exe`
2. Chạy file và làm theo hướng dẫn cài đặt
3. Khởi động HiViewer từ Desktop hoặc Start Menu
4. **Chấp nhận UAC prompt** khi được hỏi

### Cho phép người khác điều khiển máy bạn

1. Mở HiViewer (chấp nhận UAC)
2. Ghi nhớ **ID** và **Mật khẩu** hiển thị ở phần "Cho phép điều khiển"
3. Gửi ID và Mật khẩu cho người muốn điều khiển máy bạn

### Điều khiển máy tính khác

1. Mở HiViewer
2. Nhập **ID đối tác** vào ô ở phần "Điều khiển máy khác"
3. Nhấn **Kết nối**
4. Nhập **Mật khẩu** khi được yêu cầu
5. Bắt đầu điều khiển!

## 📸 Ảnh màn hình

<p align="center">
  <img src="screenshots/Screenshot.png" alt="Giao diện chính" width="500">
</p>

## ❓ Câu hỏi thường gặp

### Tại sao cần quyền Administrator?

Để capture UAC prompts và điều khiển các ứng dụng elevated.

### Hình ảnh bị mờ?

- **Cài v1.2.1** - chất lượng JPEG cao hơn (75%)
- Adaptive quality sẽ tự điều chỉnh theo bandwidth

### Điều khiển bị lag?

- Kiểm tra kết nối Internet ổn định
- Delay phụ thuộc vào tốc độ mạng

## 👨‍💻 Tác giả

- **TranQuoc** - [tduyquoc@gmail.com](mailto:tduyquoc@gmail.com)

## 🙏 Tri ân

Cảm ơn thầy **Nguyễn Tiến Dũng** đã hướng dẫn và hỗ trợ trong quá trình phát triển.

## 📄 Giấy phép

Phần mềm này được phát hành miễn phí cho mục đích cá nhân và giáo dục.

---

<p align="center">
  Made with ❤️ in Vietnam
</p>
