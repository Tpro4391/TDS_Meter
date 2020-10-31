# TDS_Meter
Dự án đo chất lượng nước máy lọc nước 3 điểm đo
<img src="https://github.com/Tpro4391/TDS_Meter/blob/main/Anh-3TDS.png">
## Thông số đo:
- TDS1: Chất lượng nước vào sơ cấp
- TDS2: Chất lượng nước vào sau 3 lõi lọc
- TDS3: Chất lượng nước sau lọc RO
- Số ngày đã vận hành
## Chức năng
- Do chất lượng nước tại các cấp lọc để thay thế lõi lọc
- Set up ngưỡng cảnh báo
- Thực hiện cảnh báo bằng còi khi vượt ngưỡng hoặc lỗi cảm biến
- Thực hiện hiệu chỉnh / hiệu chuẩn trực tiếp trên web
- Thiêt lập kết nối wifi, kết nối blynk, kết nối MQTT
- Tương thích, tích hợp vàp Hass io và các hệ ioT khác qua MQTT server
- tự động kết nối wifi, server
## Phiên bản
### V1.0
    - Khởi điểm phiên bản thương mại
    - Loại bỏ đo lưu lượng và lượng nước
    
### V1.1
    - Fix Tab Connect cho phép kết nối wifi dễ dàng hơn
    - Fix Lỗi hiệu chỉnh kiểm định
    - Check DNS web local: http://twater.local/ và http://twater/ đều hoạt động OK

### V1.2
    - Cho phép TDS R0=0 mà không cảnh báo
    
### V1.3
    - Giới hạn min chu kỳ setup đọc cảm biến là 30s
    - Loại bỏ setup tài khoản đăng nhập

### V1.4
    - Update trạng thái lên V10, IP V0 của blynk
    - MAP data:
    <img src="https://github.com/Tpro4391/TDS_Meter/blob/main/pin_map_V1.4.png">
