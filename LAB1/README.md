# LAB 1.2: BẮT GÓI TIN TELNET - SSH

## Thông tin sinh viên
- Họ và tên: Lê Thị Mỹ Hằng
- MSSV: 1150070011
- Lớp: 11_ĐH_TMĐT

## Nội dung đã thực hiện
- Cài đặt Telnet Server và SSH Server trên Kali Linux.
- Sử dụng Wireshark bắt gói tin Telnet (cổng 23) và SSH (cổng 22) trên interface lo.
- Thực hiện đăng nhập, chạy lệnh ls, pwd, mkdir qua cả hai giao thức.
- Phân tích kết quả bắt gói tin.

## Kết quả thực hiện
- Telnet: Dữ liệu truyền dạng plaintext, Wireshark hiển thị rõ username, password và các lệnh đã gõ.
- SSH: Dữ liệu được mã hóa hoàn toàn, Wireshark chỉ thấy handshake, không đọc được nội dung.

## Lưu ý để giảng viên kiểm tra
- Môi trường: Kali Linux trên VMware Workstation.
- Bắt gói tin trên interface lo (loopback).
- File báo cáo Word và 2 ảnh minh chứng nằm trong cùng thư mục LAB1.

## Link video
https://youtu.be/sHqDfsbtOIU
