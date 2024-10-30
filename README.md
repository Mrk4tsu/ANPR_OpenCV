# 🚗 Automatic Number Plate Recognition (ANPR)

## 📖 Giới thiệu
**Automatic Number Plate Recognition (ANPR)** là dự án nhận diện biển số xe tự động, sử dụng kỹ thuật xử lý ảnh từ OpenCV. Dự án có thể nhận diện biển số xe từ hình ảnh hoặc video qua Camera, ứng dụng được trong giám sát giao thông, đỗ xe tự động, và nhiều tình huống khác. 

> **Tham khảo chính**: [ANPR with OpenCV by wasiongit](https://github.com/wasiongit/ANPR_with_opencv.git)

## 💡 Ý tưởng dự án
Dự án này được xây dựng nhằm phát triển một hệ thống có thể tự động:
- Phát hiện biển số trong khung hình
- Trích xuất và nhận diện ký tự trên biển số xe

## 🛠️ Cài đặt

### Yêu cầu hệ thống
- Python
- Các thư viện Python: OpenCV

### Cài đặt
1. Clone repository này về máy:
   ```bash
   git clone https://github.com/Mrk4tsu/ANPR_OpenCV.git
2. Cấp quyền và kích hoạt môi trường ảo:
  ```bash
  python -m venv myvenv
  ```
  ```bash
  .\myvenv\Scripts\activate
  ```
3. Cài đặt các thư viện cần thiết:
  ```bash
  pip install opencv-python
  ```

## 🚀 Sử dụng
### Chạy nhận diện biển số trên ảnh

Đảm bảo bạn có ảnh biển số, yêu cầu sử dụng camera và biển số xe phải xuất hiện trong khung hình.

### 📊 Kết quả
Chương trình sẽ khoanh vùng cho biển số xe, 1 cửa sổ nhỏ hiện lên hiển thị biển số xe

### 🙏 Lời cảm ơn
Cảm ơn đến wasiongit vì các ý tưởng và mã nguồn tham khảo cho dự án này.
