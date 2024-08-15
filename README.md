# proxyv6

Áp dụng cho linux

1. Cài net-tools (nếu vps chưa có)
2. tải file install.sh về máy với lệnh
   - wget -O install.sh https://raw.githubusercontent.com/khoihien/proxyv6/main/install.sh"
   - chạy lệnh sudo bash /install.sh => enter
3. Gõ lệnh ifconfig => enter => xem tên card mạng là gì
4. Sửa enp1s0 thành tên card mạng của bạn đã lấy được ở bước 3 (dòng 84) => lưu lại
5. chạy lệnh sudo bash /install.sh và làm theo thứ tự
