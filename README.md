#Cài đặt Ubuntu server 14.04-4 64 bit trên VMware Worksation 12
==========

-[Mục lục ] (#content)
<ul>
<li> [1.giới thiệu Ubuntu Server] (#gt)</li>
	
<li> [2.Hướng dẫn cài đặt Ubuntu Server 14.04 64-bit] (#hd)</li>
	<ul>
	<li> [2.1 Yêu cầu cấu hình] (#yc)</li>
	<li> [2.2 Các bước cài đặt] (#cb)</li>
	</ul>
	
<li> [3.Lời cảm ơn] (#tks)</li>
</ul>

#Note: 
- Phiên Bản VMware được giới thiệu trong bài là VMware Workstation 10
- Host cài đặt: Win 8.1- 64bit

<a name="gt"></a>
## 1.Giới thiệu Ubuntu Server 

-Ubuntu là một trong những bản phân phối (distro) Linux phổ biến nhất hiện nay do Mark Shuttleworth sáng lập và công ty Canonical của ông tài trợ.

-Ubuntu là phần mềm mã nguồn mở tự do, có nghĩa là người dùng được tự do chạy, sao chép, phân phối, nghiên cứu, thay đổi và cải tiến phần mềm theo điều khoản của giấy phép GNU GPL.

-Ubuntu kết hợp những đặc điểm nổi bật chung của hệ điều hành nhân Linux, như tính bảo mật trước mọi virus và malware, khả năng tùy biến cao, tốc độ, hiệu suất làm việc, và những đặc điểm riêng tiêu biểu của Ubuntu như giao diện bắt mắt, bóng bẩy, cài đặt ứng dụng đơn giản, sự dễ dàng trong việc sao lưu dữ liệu và sự hỗ trợ của một cộng đồng người dùng khổng lồ.

-Ubuntu sử dụng giao diện đồ họa thân thiện GNOME, qua đó hướng đến sự đơn giản hóa trong quá trình sử dụng. Đặc điểm có thể nhận thấy rõ ở giao diện mặc định của Ubuntu là các màu chuyển giữa nâu và cam.

-Ubuntu là sự lựa chọn tuyệt vời cho máy tính của bạn. Bạn không cần phải bỏ ra một số tiền lớn hoặc vi phạm bản quyền để mua hoặc dùng lậu Windows mà vẫn có thể làm mọi việc với chiếc máy tính của mình, không phải lo lắng về virus...

<a name="hd"></a>
## 2.Hướng dẫn cài đặt Ubuntu Server 14.04 64-bit 

### 2.1 Yêu cầu cấu hình:
**cấu hình tối thiểu:** 

|           | Server      | 
|--------------|-------|
| CPU       |300 MHz (x86) | 
| RAM       | 64 MB        | 
| Bộ nhớ    | 500 MB       |
|VIDEO CARD | VGA @ 640×480|

**cấu hình áp dụng trong bài**

|           | Server      | 
|--------------|-------|
| CPU       |300 MHz (x86) | 
| RAM       | 1 GB         | 
| Bộ nhớ    | 20 GB        |
|VIDEO CARD | VGA @ 640×480|

<a name="cb"></a>
### 2.2 Các bước cài đặt:

**Bước 1:** Chọn ngôn ngữ cho Ubuntu Server 

<img src=http://i.imgur.com/vxH3NlF.png>

**Bước 2:** Chọn Install để bắt đầu cài đặt

<img src=http://i.imgur.com/E78ePNi.png>

**Bước 3:** Chọn ngôn ngữ hiển thị 

<img src=http://i.imgur.com/RYUpA9x.png>

**Bước 4:** Chọn **NO** nếu muốn tự cài đặt bàn phím

<img src=http://i.imgur.com/D37UKd0.png>

**Bước 5:** Có thể chọn dịch vụ DHCP hoặc tự configure network

<img src=http://i.imgur.com/K9oFjO1.png>

**Bước 6:** Cấu hình địa chỉ IP, gateway, name server, hostname, domain name,tài khoản và password ( Một số phần có thể để trống nếu không cài đặt ).

<img src=http://i.imgur.com/3eIg7AZ.png>

<img src=http://i.imgur.com/idO9fcE.png>

<img src=http://i.imgur.com/Y0xF3i5.png>

<img src=http://i.imgur.com/miO7COv.png>

<img src=http://i.imgur.com/DNp2Kdi.png>

<img src=http://i.imgur.com/yUKilXB.png>

<img src=http://i.imgur.com/d4nCqyJ.png>

<img src=http://i.imgur.com/tXDW0XY.png>

**Bước 7:** Chia ổ đĩa

<img src=http://i.imgur.com/Qxbv4YJ.png>

<img src=http://i.imgur.com/Z6uhCkN.png>

Bạn có thể tham khảo cách chia ổ đĩa này

<img src=http://i.imgur.com/r9cLtO9.png>

<img src=http://i.imgur.com/w5ouSj4.png>

**Bước 8:** Quản lý việc update hệ thống 

<img src=http://i.imgur.com/f7uZGj3.png>

**Bước 9:** Chọn các gói cài đặt cho Server

<img src=http://i.imgur.com/KTct6IF.png>

**Bước 10:** Cài đặt GRUB

<img src=http://i.imgur.com/a8J2GOi.png>

**Bước 11:** Hoàn thành cài đặt Ubuntu Server 14-04

<img src=http://i.imgur.com/6YDA96H.png>

<img src=http://i.imgur.com/5WCcE5T.png>

<a name="tks"></a>
## 3.Lời cảm ơn
Cảm ơn các bạn đã đọc hết bài viết này. Tôi hoan nghênh mọi ý kiến đóng.
