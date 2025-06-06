# 🎬 YouTube App - React Native

Một ứng dụng YouTube đơn giản được xây dựng bằng React Native, cho phép người dùng tìm kiếm và xem video trực tiếp từ YouTube thông qua YouTube Data API.

## 🚀 Tính năng

- 🔍 Tìm kiếm video theo từ khóa
- 🎥 Xem thông tin video (tiêu đề, kênh, số lượt xem, ngày đăng)
- ▶️ Phát video bằng YouTube Player
- 🧭 Giao diện thân thiện và tối ưu cho thiết bị di động

## 🛠 Công nghệ sử dụng

- **React Native**
- **React Navigation**
- **Axios** – để gọi API
- **YouTube Data API v3**
- **Expo hoặc React Native CLI**

## 🔑 Lấy API Key từ Google Cloud

1. Truy cập: [Google Cloud Console](https://console.cloud.google.com/)
2. Tạo project mới hoặc chọn project hiện tại.
3. Bật YouTube Data API v3.
4. Tạo API key tại mục "Credentials".
5. Gán key vào file `.env` hoặc trực tiếp trong file gọi API.

```env
YOUTUBE_API_KEY=your_api_key_here
▶️ Hướng dẫn chạy ứng dụng
bash
Sao chép
Chỉnh sửa
git clone https://github.com/your-username/yt-app.git
cd yt-app
npm install
npm start
Hoặc nếu dùng Expo:

bash
Sao chép
Chỉnh sửa
npx expo start
📁 Cấu trúc thư mục
arduino
Sao chép
Chỉnh sửa
/components     // Các component như VideoCard, SearchBar
/screens        // Các màn hình: Home, VideoPlayer
/utils          // Cấu hình axios, API helpers
