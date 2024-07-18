Thành Viên: Võ Lê Vũ - 20522170
            Phạm Kiên - 20521490

## Chưa kết nối với máy tính từ xa được.

# EYERemoteDeskptopApp

EYERemoteDeskptopApp là một ứng dụng Windows Forms sử dụng giao diện Metro để điều khiển máy tính từ xa qua Remote Desktop Protocol (RDP).

## Chức năng

- **Hiển thị địa chỉ IP của máy cục bộ:** Hiển thị địa chỉ IP của máy cục bộ khi ứng dụng khởi động.
- **Kết nối tới máy tính từ xa:** Cho phép người dùng nhập địa chỉ IP và kết nối đến máy tính từ xa thông qua RDP. 
- **Ngắt kết nối:** Cho phép ngắt kết nối RDP từ máy tính từ xa.
- **Kiểm tra kết nối:** Kiểm tra kết nối đến địa chỉ IP từ xa bằng `TcpClient`.
- **Hiển thị tên hệ thống:** Hiển thị tên hệ thống của địa chỉ IP từ xa.


## Yêu cầu hệ thống

- .NET Framework
- MetroFramework
- MSTSCLib

## Hướng dẫn sử dụng
1. Hiển thị địa chỉ IP:

* Mở ứng dụng, địa chỉ IP của máy cục bộ sẽ được hiển thị tự động trong ô 'Your IP'.

2. Kết nối tới máy tính từ xa:

* Nhập địa chỉ IP của máy tính từ xa vào ô 'Client IP'.
* Nhấn nút "Connect" để kết nối.

3. Kiểm tra kết nối:
* Nhập địa chỉ IP của máy tính từ xa vào ô Client IP.
* Nhấn nút "Ping" để kiểm tra kết nối.

