# k58ltp_baitap2web

-Cài đặt Apache r extract vào ổ D/Apache24
<img width="1918" height="1080" alt="image" src="https://github.com/user-attachments/assets/577517b1-beb1-43fe-89f2-13140fb91569" />

- cấu hình htppd.conf
<img width="1061" height="741" alt="image" src="https://github.com/user-attachments/assets/b040b996-f335-431e-98a4-01c75f14e4d7" />
<img width="361" height="47" alt="image" src="https://github.com/user-attachments/assets/43d7f985-cd80-4310-aa6e-a72931e8b806" />
<img width="463" height="67" alt="image" src="https://github.com/user-attachments/assets/68338c09-52cb-4df5-9ca8-82f472c3ae77" />
cấp quyền thư mục web
<img width="486" height="118" alt="image" src="https://github.com/user-attachments/assets/d940625d-57c5-4fc7-ae6e-de54a5808c4d" />
- cấu hình vhosts
<img width="602" height="323" alt="image" src="https://github.com/user-attachments/assets/6ace91dc-8e8a-4b14-bd1f-77ca92c3b149" />

-tạo folder theo tên sinh viên 'nguyen giang long'
<img width="1916" height="1080" alt="image" src="https://github.com/user-attachments/assets/d0573b78-83ac-425d-9f41-ffa08fc5870a" />
-khởi động apache
<img width="1100" height="632" alt="image" src="https://github.com/user-attachments/assets/76fab851-8c8e-417e-95b8-065792ddf062" />
 <img width="1920" height="1022" alt="image" src="https://github.com/user-attachments/assets/6a990362-f2e4-4537-bd94-e7c6497b4a0c" />

2, 
Cài đặt nodejs
<img width="1077" height="843" alt="image" src="https://github.com/user-attachments/assets/ec1158ad-b89a-44dd-8833-07d519a4c3ff" />
Cài đặt nodejs, nssm.exe, tạo file run nodejs cmd
<img width="1075" height="677" alt="image" src="https://github.com/user-attachments/assets/16e93fd2-2134-4689-8ee1-b4f98996f68d" />

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/13f222c8-3ce2-4236-a60f-a61f5898665e" />

3, 
-download extension cần thieetss 
<img width="1912" height="961" alt="image" src="https://github.com/user-attachments/assets/4e2a997e-2727-4b03-bccc-b78233bcd924" />
-thay chuỗi mã hóa mật khẩu
<img width="962" height="210" alt="image" src="https://github.com/user-attachments/assets/dc76881e-d57c-4609-a719-df159f792b8a" />
-nodered đã đòi mật khẩu
<img width="1920" height="1028" alt="image" src="https://github.com/user-attachments/assets/f6090c80-4618-4a8a-b2e4-c0d0a47c1714" />

4, cài CSDL SQL

5, cài đặt api nodered
<img width="1920" height="965" alt="image" src="https://github.com/user-attachments/assets/42bd5777-ab92-4c56-bfe9-8e5f41f2411c" />

6, TỔng kết:
Đã hiểu cach làm:
- Apache: xử lý được các cảnh báo ServerName, vHost, và đặc biệt là lỗi chiếm cổng 80 (đọc netstat, tìm PID, hiểu nguyên nhân).
- Node.js + Node-RED: cài đúng phiên bản, hiểu vì sao phải tạo run-nodered.cmd, hiểu cơ chế --prefix (sau khi sửa) và dùng NSSM để chạy service
- MSSQL: tạo DB/table riêng, nắm được thông số kết nối cần lưu (server, port, user, pass, db, table).
- Cài đc tất cả các thư viện nodered cần thiết
- PATH/npm --prefix khiến không thấy node-red.cmd (đã hiểu lý do và chạy trực tiếp red.js).
