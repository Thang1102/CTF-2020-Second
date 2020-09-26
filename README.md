# CTF-2020-Second-Easy
CTF Changllenges KMA Second Easey
## Android RE (25 Point)
Tải file app.apk 
<img src="https://i.imgur.com/vChmoth.png" />
Cài phần mềm giả lập android ví dụ: LDPlayer
Cài đặt app.apk đó lên trình giả lập đó
<img src="https://i.imgur.com/UpzCMHI.png" />
Ta thấy đây là một hình ảnh với nội dung thông báo là "**This is not the active....**" --> Bí ẩn nằm trong tấm ảnh này chúng ta cần giải mã
Cài đặt công cụ apktool trên kali https://ibotpeaches.github.io/Apktool/install/
Chạy công cụ apktool để giải mã file app.apk trên
<img src="https://i.imgur.com/nmMOXPS.png" />
Vào thư mục app vừa giải mã, chúng ta sẽ quan tâm đến thư mục **smali** nơi chứa thông tin về đoạn code chương trình để gọi đến file tài nguyên(theo ý hiểu của mình). 
<img src="https://i.imgur.com/X8hsj4V.png" />
Tiếp theo đó vào thư mục **com/example/blink/** nơi có chứa thông tin mà chúng ta cần tìm.
Bạn chạy lệnh tìm kiếm : 
<p>``` cat * | grep -i "ctf" ```</p>
<img src="https://i.imgur.com/aKKBOlW.png" />
copy đoạn code đó và sử dụng trình base64 decode 
Kết quả: **KMACTF{blink_blink}**

<p></p>
 **Hello_KMA ( 5 point)**
 Đăng ký tài khoản  trên trang decord: https://discord.gg/2QeBsgt
 Nó ở ngay trên đầu nhé
<img src="https://i.imgur.com/FNuspLQ.png" />

<p> </p>
**Miku (20 point)**
Kiểm tra mã nguồn trang vào mục Application (f12)
<img src="https://i.imgur.com/raaZwwB.png" />
