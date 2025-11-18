Hệ thống cảnh báo thời tiết được thiết kế để kết nối với các dịch vụ dự báo thời tiết, cung cấp thông tin thời tiết theo thời gian thực cũng như dự báo chính xác cho người dùng. Hệ thống này không chỉ cảnh báo về các hiện tượng thời tiết xấu như mưa lớn, bão, hay nhiệt độ cực đoan, mà còn gợi ý các biện pháp bảo vệ cho cây trồng và tài sản trước những điều kiện thời tiết khắc nghiệt.


Nguyên lý hoạt động và mô phỏng:

Mô hình sử dụng Arduino Uno làm trung tâm điều khiển để thu thập dữ liệu từ các cảm biến và điều khiển các thiết bị ngoại vi. Cảm biến nhiệt độ và độ ẩm (DHT22) đo thông số môi trường và gửi tín hiệu đến Arduino. Dữ liệu sau đó được xử lý để hiển thị trên màn hình LCD. Dựa trên dữ liệu đo được và các ngưỡng thiết lập trước, Arduino điều khiển các rơ-le để bật hoặc tắt các thiết bị như quạt hoặc động cơ. Các nút nhấn được sử dụng để điều chỉnh chế độ hoạt động, trong khi biến trở điều chỉnh các tham số đầu vào như độ sáng màn hình. Toàn bộ hệ thống hoạt động nhờ nguồn điện cấp từ Arduino và các linh kiện hỗ trợ.

<img width="1298" height="843" alt="image" src="https://github.com/user-attachments/assets/b1f24b5f-c869-47c6-b575-6c2c0baf39db" />



