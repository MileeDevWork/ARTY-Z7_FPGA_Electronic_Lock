# Arty Z7 FPGA Electronic Lock

## Thành viên nhóm

| NAME             |
| ---------------- |
| NGUYỄN TUẤN ANH  |
| NGUYỄN KHẮC DUY  |
| DƯƠNG MINH HIẾU  |
| TRỊNH THỊ MỸ LỆ   |


## Vai trò

Trong dự án này, tôi đảm nhận vai trò:

* **Phát triển module hiển thị:** Hiện thực module hiển thị số trên LED 7 đoạn trên Extension board for Arty Z7.
* **Xử lý dữ liệu:** Hiện thực module dịch dữ liệu 10-bit sang 16-bit.
* **Mở rộng phương thức nhập liệu:** Nghiên cứu và tích hợp bàn phím ma trận mềm 4x4 để nhập mật khẩu, mang lại trải nghiệm người dùng trực quan và tiện lợi hơn so với phương pháp nhập liệu bằng switch truyền thống.

## Mô tả đề tài

Trong bối cảnh nhu cầu về các hệ thống bảo mật an ninh linh hoạt và có khả năng thích ứng cao ngày càng gia tăng, dự án "Hệ thống ổ khóa điện tử" được xây dựng nhằm khám phá và ứng dụng tiềm năng của FPGA trong lĩnh vực này. Ổ khóa điện tử, với khả năng sử dụng mật khẩu thay thế cho chìa khóa truyền thống, đang dần trở nên phổ biến trong cuộc sống hiện đại.

Đề tài này tập trung vào việc thiết kế và phát triển một hệ thống khóa điện tử đơn giản nhưng hiệu quả trên kit phát triển FPGA Arty-Z7 kết hợp với Extension board. Việc sử dụng FPGA Arty-Z7 không chỉ tận dụng khả năng xử lý song song và tái cấu hình mạnh mẽ của nó, mà còn mở ra cơ hội tích hợp các tính năng mở rộng trong tương lai.

Mục tiêu nghiên cứu chính của đề tài bao gồm:

Xây dựng hệ thống khóa điện tử cơ bản với các thành phần như LED 7 đoạn (hiển thị), công tắc chọn số (đã được thay thế bằng bàn phím ma trận mềm 4x4 trong quá trình phát triển), các nút bấm (cho tương tác) và đèn LED RGB (hiển thị trạng thái).
Triển khai các tính năng bảo mật nâng cao, bao gồm cơ chế xác thực mật khẩu với giới hạn số lần nhập sai và khóa thao tác khi vượt quá số lần cho phép.
Cung cấp chức năng quản lý mật khẩu linh hoạt, cho phép người dùng đặt lại mật khẩu sau khi xác thực thành công.
Hướng đến phát triển giao diện thân thiện và dễ sử dụng, với định hướng mở rộng các tính năng như hiển thị trạng thái trên màn hình LCD, cảnh báo bằng buzzer để hiển thị trạng thái hoạt động và thông báo lỗi.

## Phần cứng sử dụng

* **FPGA:** Board Arty Z7 
* **Extension board for Arty Z7**
* **Bàn phím ma trận mềm 4x4**
* **Màn hình LCD**

## Phần mềm/Công cụ sử dụng

* **Ngôn ngữ mô tả phần cứng (HDL):** Verilog HDL
* **Công cụ phát triển:** Vivado Design Suite (Sử dụng cho viết code, mô phỏng waveform, tổng hợp mạch và triển khai trên FPGA)


## Video demo
[Video demo dự án](https://youtu.be/7lwEYay7SU0)
