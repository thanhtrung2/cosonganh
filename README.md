# cosonganh

## Giới thiệu
Mô tả ngắn gọn về dự án của bạn - dự án làm gì, giải quyết vấn đề gì.

## Công nghệ sử dụng
- Ngôn ngữ lập trình: JavaScript
- Framework: Tailwind CSS
- API: JSON Server

## Yêu cầu hệ thống
- Phiên bản Node.js
.

## Cài đặt

1. Clone dự án
Clone dự án về máy:

git clone https:https://github.com/thanhtrung2/CSN-DA22TTC-NguyenThanhTrung-Webgioithieuoto

2. Di chuyển vào thư mục dự án

3. Mở project
- Mở thư mục project bằng text editor
- Với VS Code: File > Open Folder > Chọn thư mục project

4. Cài đặt Live Server (VS Code)
- Mở VS Code Extensions
- Tìm "Live Server"
- Nhấn Install

5.khởi động API
-vào Terminal 
-chọn New Terminal 
-gõ npm start để khởi động API

6.Mở trang Web 
- Click chuột phải vào file index.html
- Chọn "Open with Live Server"
- Website sẽ tự động mở trên trình duyệt mặc định


## Cấu hình

1. Tạo file `.env` từ file `.env.example` ở thư mục `backend`

2. Cập nhật các biến môi trường trong file `.env` (ví dụ: `MONGODB_URI`)

## Chạy dự án

### Môi trường development
   - Chạy JSON Server: `json-server --watch db.json --port 3000` ở thư mục `json-server-api`
   - Chạy backend: `npm run dev` ở thư mục `backend`
   - Mở file `index.html` hoặc các file HTML khác trực tiếp bằng trình duyệt để chạy frontend

### Môi trường production
   - Làm theo hướng dẫn deploy (ví dụ: deploy backend lên server, frontend có thể deploy tĩnh)

## Chạy dự án trên máy khác

1. **Sao chép dự án:** Copy toàn bộ thư mục dự án sang máy mới.
2. **Cài đặt môi trường:** Đảm bảo máy mới có đầy đủ các yêu cầu hệ thống (Node.js) và các dependencies cần thiết.
3. **Cấu hình:** Thực hiện các bước cấu hình như hướng dẫn (tạo file `.env`, cập nhật biến môi trường).
4. **Chạy dự án:** Chạy dự án theo hướng dẫn cho môi trường development hoặc production.

## API Documentation
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
    - `GET /cars`: Lấy danh sách tất cả xe.
    - `GET /cars/:id`: Lấy thông tin chi tiết của một xe dựa trên ID.
    - `POST /cars/:id/reviews`: Thêm đánh giá cho một xe.
    - `GET /cars/:id/reviews`: Lấy danh sách đánh giá của một xe.

## Đóng góp
Hướng dẫn cách đóng góp vào dự án

## Giấy phép
Thông tin về giấy phép sử dụng