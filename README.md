# RSA Encryption/Decryption Web Application

## Giới thiệu
Đây là một ứng dụng web được xây dựng bằng Flask để thực hiện mã hóa và giải mã RSA. Ứng dụng cung cấp giao diện web đơn giản và dễ sử dụng để thực hiện các thao tác mã hóa/giải mã RSA.

## Tính năng
- Tạo cặp khóa RSA
- Mã hóa văn bản sử dụng khóa công khai
- Giải mã văn bản sử dụng khóa riêng tư
- Giao diện web thân thiện với người dùng

## Yêu cầu hệ thống
- Python 3.6 trở lên
- Các thư viện Python (được liệt kê trong requirements.txt):
  - Flask 2.0.1
  - cryptography 36.0.1
  - PyJWT 2.3.0
  - python-dotenv 0.19.0
  - requests 2.26.0

## Cài đặt
1. Clone repository này về máy local của bạn
2. Tạo môi trường ảo Python (khuyến nghị):
   ```
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
3. Cài đặt các thư viện cần thiết:
   ```
   pip install -r requirements.txt
   ```

## Sử dụng
1. Khởi động ứng dụng:
   ```
   python app.py
   ```
2. Mở trình duyệt web và truy cập địa chỉ: `http://localhost:5000`

## Bảo mật
- Ứng dụng sử dụng thư viện cryptography để đảm bảo an toàn cho các thao tác mã hóa/giải mã
- Khóa riêng tư được bảo vệ và không được lưu trữ trên server
- Tất cả các giao tiếp được thực hiện qua HTTPS

## Đóng góp
Mọi đóng góp đều được hoan nghênh! Vui lòng tạo issue hoặc pull request để đóng góp cho dự án.

## Liên hệ
Để biết thêm thông tin hoặc hỗ trợ, vui lòng liên hệ qua email: minhquangts2004@gmail.com 