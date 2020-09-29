# Tom Cat (100 point)
<img src="https://i.imgur.com/57ZtMDY.png" />
<p>Vào web site thấy đây là một apache tomcat 9.0.30</p>
<img src="https://i.imgur.com/eITQB7L.png" />
Ở phiên bản <9.0.31 tồn tại lỗ hổng GhostCat (CVE-2020-1938) <br>
Đọc thêm: http://m.antoanthongtin.gov.vn/lo-hong-attt/ghostcat---lo-hong-nghiem-trong-anh-huong-den-cac-may-chu-apache-tomcat-105913 <br>
Mình dùng tool nmapAutomator.sh ( lên mạng có trên gith mình tải về để dò quét tìm ra lỗ hổng đó)<br>
<img src="https://i.imgur.com/sJNh5Z3.png" />
<img src="https://i.imgur.com/P7WCeNl.png" />
<img src="https://i.imgur.com/RzEJ8LW.png" />
Mặc định nó nằm ở cổng 8009 nhưng ở đây là 7009 lưu ý nhé<br>
Sau đó mình dùng bộ công cụ Ajp Shooter để dò tìm thông tin cờ nhé. Theo kinh nghiệm của anh hay chơi CTF bảo mình dùng kỹ thuật fuzzing để dò đoán 
<img src="https://i.imgur.com/Z8RwqkS.png" />
