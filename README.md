# Project_2

## Cài đặt môi trường
-  Sử dụng ngôn ngữ lập trình Python và môi trường Jupiter Notebook ( Google Colab hoặc Visual Studio Code)
- Sử dụng trình quản lý [pip](https://pip.pypa.io/en/stable/) để cài đặt các thư viện
```bash
Sử dụng pip để cài đặt các thư viện cần thiết
```
## Tổng quan
- Dự án này nhằm mục đích phát triển một mô hình học máy có thể nhận diện các ký tự toán học trong văn bản. Mô hình này có thể được sử dụng trong các ứng dụng như:
*Tự động đánh dấu bài tập về nhà hoặc bài kiểm tra toán học
*Tạo các công cụ hỗ trợ học tập toán học
*Tạo các ứng dụng dịch văn bản có chứa ký tự toán học
- Sử dụng dữ liệu gồm các ảnh kích thước 25x25 được vẽ bằng ứng dụng và đã được gán nhãn
- Ứng dụng có thể tạo và thay đổi tập dữ liệu, huấn luyện mô hình trực tiếp nhằm mục đích giúp người dùng có thể huấn luyện mô hình nhận diện với ký tự bất kỳ cũng như hiệu chỉnh lại mô hình với những dự đoán sai
- Có thể thay đổi qua lại giữa 3 mô hình CNN, SVM, KNN
## Đánh giá
- Độ chính xác của mô hình CNN cao nhất 85%
- Độ chính xác của SVM, KNN thấp hơn khoảng tầm 70% (Phụ thuộc vào dữ liệu cũng như sự huấn luyện từng lần khác nhau)
## Chạy ứng dụng
- Sau khi đã cài đặt môi trường và thư viện, mở workspace là thư mục GUI và chạy file draw2.py để sử dụng


