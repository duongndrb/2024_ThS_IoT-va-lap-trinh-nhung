# 2024_ThS_IoT-va-lap-trinh-nhung
Đây là nơi lưu trữ code 2 App (app full kết nối và app chỉ hiển thị) trong bài tập project cuối kì môn học.

App Full kết nối có các chức năng: 
- Tìm, quét và kết nối thiết bị Module BLE HM-10 có kết nối tới mạch điều khiển STM32.
- Kết nối với Cloud và đẩy dữ liệu từ mạch lên Cloud thông qua mạng Wifi/Di động (Cloud sử dụng Realtime Database của Google Firebase).
- Sau khi kết nối tới Cloud, lấy dữ liệu thời gian thực từ trên Cloud và hiển thị lên app.

App chỉ có chức năng hiển thị dữ liệu từ Cloud giúp theo dõi dữ liệu thời gian thực từ xa khi được kết nối tới Cloud.
