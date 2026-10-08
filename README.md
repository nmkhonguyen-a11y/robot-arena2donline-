# Mech Arena 2D Online

## Chạy thử trên máy
    npm install
    npm start
Mở http://localhost:3000 (cần Node.js 18 trở lên).

## Đưa lên Render.com
1. Đẩy thư mục này lên GitHub.
2. Render > New > Web Service > chọn repo. Build: `npm install`, Start: `npm start`.
3. QUAN TRỌNG - lưu tài khoản: server ghi tài khoản vào file `data/accounts.json`.
   Ổ đĩa của gói miễn phí bị xóa mỗi lần khởi động lại/triển khai lại, tài khoản (kể cả 5 tài khoản @ đầu tiên) sẽ MẤT.
   Hãy gắn Persistent Disk (gói trả phí), mount vào ví dụ `/var/data` và đặt biến môi trường `DATA_DIR=/var/data`,
   hoặc đổi phần lưu trữ trong `server.js` sang một cơ sở dữ liệu (MongoDB Atlas, Supabase...).
4. Gửi địa chỉ Render cho bạn bè (game và server chung một địa chỉ).

## Tài khoản
- Tên chỉ gồm chữ và số (3-16 ký tự), không phân biệt hoa thường, không trùng nhau.
- 5 tài khoản đăng ký đầu tiên có dấu @ trước tên và Credits / A-Coins vô hạn.
