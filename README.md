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

Dự án này hiện thực một hệ thống ổ khóa điện tử trên kit phát triển FPGA Arty Z7, sử dụng ngôn ngữ mô tả phần cứng Verilog. Mục tiêu là xây dựng một hệ thống bảo mật đơn giản nhưng hiệu quả, cho phép người dùng mở khóa bằng mã số bí mật được nhập thông qua bàn phím ma trận mềm.

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
