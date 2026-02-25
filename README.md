# Mạch LED đổi màu MKE-M22 WS2812B RGB LED Module

## Giới thiệu sản phẩm
MKE-M22 WS2812B RGB LED Module là mạch LED đổi màu với 3 đèn led RGB WS2812B trên mạch sử dụng giao tiếp 1-Wire. Sản phẩm rất phù hợp để làm đèn giao thông, mô hình robot, sản phẩm STEM, đồ án học tập và trang trí sáng tạo. mạch có 2 cổng DI (Data In) và DO (Data Out) giúp nối tiếp thêm các module led để tạo thành dải led trang trí linh hoạt.

Mạch LED đổi màu MKE-M22 WS2812B RGB LED Module hỗ trợ điện áp điều khiển 3.3/5VDC, cho phép kết nối trực tiếp và an toàn với hầu hết các bo mạch điều khiển phổ biến hiện nay như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,… Mạch đi kèm cáp kết nối 3P XH2.54–Dupont đảm bảo chắc chắn, ổn định và linh hoạt khi kết nối.

## Thông số kỹ thuật
- Điện áp cấp nguồn: 5VDC
- Chuẩn tín hiệu điều khiển: Digital 1-Wire
- Điện áp giao tiếp: TTL 3.3/5VDC
- Màu sắc: RGB (kết hợp để tạo ra nhiều màu)
- Khả năng tương thích:
  - Arduino
  - Raspberry Pi
  - Jetson Nano
  - Micro:bit
  - Và các board điều khiển 3.3/5VDC khác
- Thiết kế mạch:
  - Ổn định, chống nhiễu
  - Phù hợp cho ứng dụng học tập và thực tế
- Đi kèm cáp kết nối: 3P XH2.54–Dupont

## Các chân tín hiệu
<table><thead>
  <tr>
    <th>MKE-M22</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>DI</td>
    <td>Chân tín hiệu Data In</td>
  </tr>
  <tr>
    <td>DO</td>
    <td>Chân tín hiệu Data Out</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân GND và 5V.
- Kết nối chân DI (Data In) của Module với chân điều khiển được khai báo trong chương trình.
- Kết cổng DO (Data Out) của Module với cổng DI (Data In) của các module kế tiếp để tạo thành dải Led RGB nếu cần.
### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno / ESP32
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu **"MKE_M22_RGB_WS2812B_Serial_XXX"** tại **File / Examples / MAKEREDU / Module / MKE_M22_RGB_WS2812B**
- Cấu hình board mạch tương ứng là **Arduino Uno / ESP32**, chọn đúng cổng **COM Port** của mạch và nhấn **Upload** để nạp chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân DI (Data In) của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động [Microsoft MakeCode](https://makecode.microbit.org/) và **Import** chương trình theo đường link sau: `https://github.com/makereduvn/mke_m22_rgb_ws2812b_microbit/`
- Kết nối mạch Micro:bit và **Download** chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân DI (Data In) của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

Nếu bắt đầu tự án mới cần cài đặt Extension **MKE_ONE_MICROBIT** trên [Microsoft MakeCode](https://makecode.microbit.org/) theo [hướng dẫn tại đây](https://github.com/makereduvn/MKE_ONE_MICROBIT). Sau khi cài đặt thành công, các khối lệnh của Extension **MKE_ONE_MICROBIT** sẽ xuất hiện trong danh sách block và sẵn sàng để sử dụng.

## Kích thước sản phẩm
![MKE-M22 RGB_WS2812](/extras/MKE-M22_1.jpg)

## Hình ảnh sản phẩm
![MKE-M22 RGB_WS2812](/extras/MKE-M22_2.png)
![MKE-M22 RGB_WS2812](/extras/MKE-M22_3.png)

