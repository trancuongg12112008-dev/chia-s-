# 🖥️ Chia Sẻ Màn Hình - Screen Sharing App

Ứng dụng chia sẻ màn hình web với tính năng chat, camera và audio real-time sử dụng WebRTC.

## ✨ Tính năng

- 🖥️ **Chia sẻ màn hình** - Share màn hình với mã 4 chữ số
- 💬 **Chat real-time** - Nhắn tin trực tiếp với người xem
- 🪟 **Chat Popup** - Cửa sổ chat riêng để theo dõi khi chia sẻ
- 📹 **Camera** - Bật camera để người khác thấy bạn
- 🎤 **Microphone** - Truyền âm thanh qua WebRTC
- 👥 **Đếm người xem** - Hiển thị số người đang xem
- 📱 **Responsive** - Hoạt động trên cả desktop và mobile
- 🎨 **Giao diện đẹp** - UI hiện đại với gradient màu tím

## 🚀 Cách sử dụng

### Người chia sẻ:
1. Nhập tên của bạn
2. Nhấn "Bắt Đầu Chia Sẻ"
3. Chọn màn hình muốn chia sẻ
4. Chia sẻ mã 4 chữ số cho người xem
5. (Tùy chọn) Bật camera, micro, hoặc mở chat popup

### Người xem:
1. Nhập tên của bạn
2. Nhập mã 4 chữ số
3. Nhấn "Kết Nối"
4. Xem màn hình được chia sẻ
5. (Tùy chọn) Bật camera, micro để tương tác

## 🛠️ Công nghệ

- **WebRTC** - Peer-to-peer video/audio streaming
- **LocalStorage** - Signaling giả lập (demo only)
- **Vanilla JavaScript** - Không cần framework
- **CSS3** - Responsive design với media queries

## 📦 Cài đặt

```bash
# Clone repository
git clone https://github.com/[your-username]/screen-sharing-app.git

# Mở file index.html trong trình duyệt
# Không cần build hay install gì cả!
```

## 🌐 Demo

Mở file `index.html` trực tiếp trong trình duyệt. Để test:
1. Mở 2 tab/cửa sổ trình duyệt
2. Tab 1: Chọn "Chia Sẻ"
3. Tab 2: Chọn "Xem" và nhập mã

## ⚠️ Lưu ý

- **LocalStorage signaling**: Chỉ hoạt động trên cùng một máy (demo purpose)
- **Production**: Cần WebSocket server cho signaling thực tế
- **Mobile**: Một số trình duyệt mobile không hỗ trợ screen sharing
- **HTTPS**: WebRTC yêu cầu HTTPS trong production

## 🔧 Nâng cấp cho Production

Để sử dụng thực tế, cần:
1. **WebSocket Server** - Thay thế localStorage signaling
2. **TURN Server** - Cho NAT traversal
3. **Backend** - Quản lý sessions và users
4. **Database** - Lưu trữ lịch sử và analytics

## 📝 License

MIT License - Tự do sử dụng và chỉnh sửa

## 👨‍💻 Tác giả

Được tạo với ❤️ bởi [Your Name]

## 🤝 Đóng góp

Pull requests được chào đón! Đối với thay đổi lớn, vui lòng mở issue trước.

## 📸 Screenshots

[Thêm screenshots của ứng dụng ở đây]

---

**Lưu ý**: Đây là demo project sử dụng localStorage. Để deploy production, cần implement WebSocket signaling server.
