# HiViewer - Phần mềm Điều khiển Máy tính Từ xa

<p align="center">
  <img src="screenshots/hiviewer.jpg" alt="HiViewer Banner" width="100%">
</p>

**HiViewer** là phần mềm điều khiển máy tính từ xa qua Internet, tương tự TeamViewer và UltraViewer. Được phát triển hoàn toàn bằng C# .NET 8.

## ✨ Tính năng

- 🖥️ **Điều khiển từ xa qua Internet** - Kết nối và điều khiển máy tính từ bất kỳ đâu
- 🖱️ **Điều khiển chuột** - Di chuyển, click, cuộn hoàn toàn mượt mà
- ⌨️ **Điều khiển bàn phím** - Gõ phím, phím tắt hoạt động đầy đủ
- 🔒 **Bảo mật** - Mỗi phiên có ID và Password riêng, chống tấn công timing
- 🚀 **Hiệu suất cực cao** - 60 FPS, Binary WebSocket, tối ưu triệt để
- 🛡️ **Hỗ trợ UAC** - Có thể thấy và điều khiển UAC prompts
- 🔄 **Tự động kết nối lại** - Khi mất kết nối sẽ tự động thử kết nối lại
- 🎨 **Giao diện đẹp** - Thiết kế hiện đại theo phong cách TeamViewer

## 📥 Tải về

| Phiên bản | Tải về | Kích thước | Ghi chú |
|-----------|--------|------------|---------|
| **v1.2.0** (Mới nhất) | [HiViewer_Setup_v1.2.0.exe](HiViewer_Setup_v1.2.0.exe) | ~2.6 MB | **Hỗ trợ UAC/Secure Desktop** |

**Yêu cầu hệ thống:**
- Windows 10/11 (64-bit)
- .NET 8 Runtime ([Tải tại đây](https://dotnet.microsoft.com/download/dotnet/8.0))
- **Quyền Administrator** (để capture UAC prompts)

## 🆕 Có gì mới trong v1.2.0

### Hỗ trợ UAC/Secure Desktop
- **Chạy với quyền Admin** - Ứng dụng yêu cầu quyền Admin để capture Secure Desktop
- **Thấy được UAC dialog** - Có thể thấy và điều khiển UAC prompts khi remote
- **Phục hồi nhanh hơn** - Phát hiện và khôi phục nhanh hơn khi chuyển đổi desktop

### Lưu ý quan trọng
Khi chạy HiViewer, Windows sẽ hiện thông báo UAC yêu cầu quyền Admin. Điều này là bình thường và cần thiết để:
- Capture màn hình khi có UAC dialog
- Điều khiển các ứng dụng elevated
- Remote control đầy đủ chức năng

## 🚀 Hướng dẫn sử dụng

### Cài đặt

1. Tải file `HiViewer_Setup_v1.2.0.exe`
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

Windows có tính năng bảo mật gọi là "Secure Desktop" để cô lập UAC prompts. Chỉ các ứng dụng chạy với quyền Admin mới có thể:
- Capture màn hình khi UAC dialog hiển thị
- Điều khiển các ứng dụng elevated
- Truy cập Secure Desktop

### Tại sao không kết nối được?

- Kiểm tra kết nối Internet của cả 2 máy
- Đảm bảo nhập đúng ID và Mật khẩu
- Thử tắt tường lửa (Firewall) tạm thời

### Màn hình bị đen khi có UAC?

- Đảm bảo HiViewer được **chạy với quyền Admin**
- Nếu vẫn đen, đợi vài giây để ứng dụng tự phục hồi

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
