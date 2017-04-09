# _**MBH++**_  - *Anonymous* <h1> 
 *created by GitHub Classroom* 
 
 [_Trang chủ Dự án_](https://nmcntt2-anonymous.github.io/)
 
 
## **Danh sách thành viên**

Họ và tên | Mã số sinh viên | Vai trò trong dự án
----------|-----------------|---------------------
Mai Nguyễn Anh Vũ | 1612904 | Quản lý dự án
Vương Hy | 1612864 | Thiết kế mũ và ứng dụng di động
Hồ Minh Huấn | 1612224 | Thiết kế web và poster
Trần Hoài Nam | 1612403 | Thiết kế mũ

## **Dự án**
Sản phẩm của nhóm là mũ bảo hiểm thông minh có khả năng gửi tín hiệu cho người thân khi xảy ra sự cố, bên cạnh đó còn tích hợp camera hành trình và có thể kết nối với điện thoại thông minh để thực hiện một số các chức năng đặc biệt khác.

### **Thực trạng**
Hiện nay, tai nạn giao thông là một vấn đề nhức nhối trong xã hội. Trong năm 2016, nước ta xảy ra **21 094 vụ tai nạn**,    làm   **chết     8685 người**, **bị thương 19 280 người**. Có nhiều vụ tai nạn nếu được cấp cứu kịp thời, nạn nhân đã có thể được cứu sống. Vì vậy cần có một giải pháp để giảm thiểu thiệt hại bằng việc thông báo ngay lập tức cho người thân để hỗ trợ kịp thời.

<p align="center">
  <img src=http://www.hvcsnd.edu.vn/Uploaded/xuanthanh/2017/thang%201/Thong%20ke%20TNGT/bd2.png>  
<p align="center">
<b>Hình 1: Biểu đồ phân tích tuyến đường xảy ra TNGT năm 2015 - 2016</b><br>
</p>

<p align="center">
  <img src=http://www.hvcsnd.edu.vn/Uploaded/xuanthanh/2017/thang%201/Thong%20ke%20TNGT/bd5.png>
<p align="center">
<b>Hình 2: Biểu đồ phân tích phương tiện gây tai nạn giao thông 2015 - 2016</b><br>
</p>

<p align="center">
  <img src=http://www.hvcsnd.edu.vn/Uploaded/xuanthanh/2017/thang%201/Thong%20ke%20TNGT/bd1.png>
<p align="center">
<b>Hình 3: Biểu đồ so sánh TNGT năm 2015 - 2016</b><br>
</p>


### **Mục đích**
Hạn chế tình trạng phát hiện sự cố quá trễ dẫn đến thiệt hại về con người. Đồng thời hỗ trợ người điều khiển xe trong quá trình tham gia giao thông.

### **Đối tượng hướng đến**
* **Người dùng phổ thông:** Thích hợp với loại ½ head hoặc ¾ head. Họ thường xuyên di chuyển quảng đường từ ngắn đến trung bình. Những người này cần loại mũ gọn nhẹ, có những chức năng cơ bản, giá thành vừa phải vì họ thường có thu nhập khoảng 5 triệu đến 15 triệu một tháng. 
* **Những người sử dụng moto, đi phượt hoặc thường xuyên di chuyển bằng xe gán máy trên đoạn đường dài:** Thích hợp với loại mũ Full Head. Tuy giá thành cao nhưng với thu nhập của họ cùng tính năng của mũ khiến họ yên tâm hơn trên những chuyến đi xa.
* **Người thân của người đi xe gán máy:** Những người này tuy không có nhu cầu sử dụng nhưng họ có khả năng mua để tặng, thậm chí tác động đến người thân đang dùng xe máy của mình sử dụng mũ bảo hiểm thông minh. Thông thường những người này thuộc tầng lớp trung lưu đến thương lưu, thu nhập từ 10 triệu một tháng trở lên.

### **Chức năng**

<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17792412_646130398908109_1859550620_n.jpg?oh=af9d3199b995b42dde876ebcc62e8569&oe=58EAAC3D">  
<p align="center">
<b>Hình 4: Các chức năng</b><br>
</p>

### **Chi tiết về các chức năng**
#### **I.	Nhận diện người dùng**
*	Mũ được trang bị cảm biến giúp nhận dạng người dùng. Khi mũ ở chế độ chờ, người dùng đội mũ, tất cả các chứng năng sẽ tự động bật.

#### **II.	Phát hiện va chạm**
*	Khi có va chạm xảy ra, bộ cảm biến sẽ gửi tín hiệu đến trung tâm xử lý.
* Cách xác định va chạm:
  - Va chạm 1 lần với lực xác định.
  - Va chạm nhiều lần với lực xác định.

#### **III.	 Định vị mũ**
*	Mũ được kết hợp với thiết bị định vị GPS. Định vị và tự động ghi lại vị trí sau một khoảng thời gian, thông qua đó biết được vị trí xe khi cần thiết.

#### **IV.	Gửi tín hiệu khẩn cấp**
*	Trung tâm xử lý sẽ gửi tin nhắn đến các số điện thoại đã được đăng kí khi nhận được tìn hiệu từ cảm biến va chạm.
* Nội dung tin nhắn sẽ bao gồm:
  - Vị trí của người sử dụng gặp sự cố theo GPS.
  - Thời gian thực được lưu lại.
  - S.O.S.
  - Chỉ số HIC và tốc độ xe tại thời điểm đó.
  -	Hình ảnh cắt từ camera (nếu có Internet).

#### **V.	Cảnh báo tốc độ**
* Khi người điều khiển xe chạy đến một tốc độ nguy hiểm (do người dùng đặt) thì mũ sẽ cảnh báo người dùng.

#### **VI.	Trợ lý giao thông**
##### **1. Tìm đường**
*	Kết nối với điện thoại thông qua BLUETOOTH. Chiếc mũ sẽ như một trợ lý ảo chỉ đường cho người dùng thông qua loa trên mũ khi người dùng sử dụng "Bản đồ" trên ứng dụng điện thoại để tìm đường đi.

##### **2. Tự động trả lời điện thoại và đọc tin nhắn.**
*	Do được kết nối với điện thoại, khi điện thoại nhận được cuộc gọi, loa gắn trên mũ sẽ thông báo cho người đội mũ biết. Người dùng có thể nói vào mic để trả lời hoặc từ chối cuộc gọi thông qua một số câu lệnh có sẵn. Tương tự, khi có tin nhắn, người đội mũ sẽ được thông báo. Người đội mũ có thể sử dụng chức năng đọc tin nhắn đến của mũ để nghe tin nhắn. Hiện tại, mũ chỉ mới đáp ứng 2 ngôn ngữ: Tiếng Việt và Tiếng Anh. 
* **Đối với 3/4 Head:** Chỉ có chức năng thông báo có điện thoại và đọc tin nhắn. Có nút trên mũ để nhận lệnh thực thi. 

#### **VIII.	Camera hành trình**
*	Camera được tích hợp để ghi lại 5 phút sau cùng. Nếu có sự cố xảy ra, camera tự động ghi cho đến khi đầy bộ nhớ.  Người dùng có thể thay đổi thẻ nhớ. Camera có tầm mở rộng 120 độ. 

### **Bản thiết kế**


<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17821308_1920834234841037_1910131649_n.png?oh=86a72eb633b43f562e86256ff96966e0&oe=58EBBEF7">  
<p align="center">
<b>Mô hình 1: 1/2 Head</b><br>
</p>



<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17820858_1920834251507702_278900940_n.png?oh=f734a70b2858386eb7a10ca58af430c9&oe=58ECA7A5">   
<p align="center">
<b>Mô hình 2: 3/4 Head</b><br>
</p>



<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17842233_1920834261507701_330001824_n.png?oh=6be1597d3e667b087798184edce25e96&oe=58EC8CC3">  
<p align="center">
<b>Mô hình 3: Full Head</b><br>
</p>



<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17821015_1920834271507700_41689950_n.png?oh=8916aa83c7b53f6bff4d425b1b54d609&oe=58ECB68A">    
<p align="center">
<b>Mô hình 4: Full Head</b><br>
</p>





### **Thông số kĩ thuật**

**Thông số chung:**
* Pin Lithium Polymer   10,000mAh cho thời gian hoạt động trên 10 tiếng.
* SIM: hoạt động trên 2 dải tần 900/ 1800 MHz.
* Tín hiệu đèn LED: hoạt động, đang sạc, pin yếu
* Tương thích: Bluetooth 4.0 trờ lên, iOS 8.4 trở lên, Android 3.2.1 trở lên.

**Thông số riêng:**

Loại mũ | Thông số 
--------|----------------
1/2 Head |* Kích thước 16x21x12cm <br>* Cân nặng: 0,6kg
3/4 Head |* Kích thước: 25 x 24 x 23 cm. <br>* Cân nặng: 1.0kg. <br>* Độ nhạy loa: 100 dB.<br>* Camera hồng ngoại 8 Mpx, góc quay 120 độ, ống kính tiêu cự cố định, quay phim HD, chụp ảnh 3280 x 2464.
Full Head |* Kích thước: 29 x 25 x 27 cm. <br>* Cân nặng: 1.3kg. <br>* Độ nhạy loa: 100 dB.<br>* Dải tần Microphone: 100Hz - 20KHz <br>* Camera hồng ngoại 8 Mpx, góc quay 120 độ, ống kính tiêu cự cố định, quay phim HD, chụp ảnh 3280 x 2464.

          
           
           
### **Quy trình vận hành**
### **Sơ lược về ứng dụng điện thoại**
<p align="center">
<b>Một số hình ảnh về ứng dụng điện thoại</b><br>
</p>

<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17857956_610536882482385_928776943_n.jpg?oh=2c3141fd1b115217f0e85ce02ae113b2&oe=58EBC371">
</p>





### **Hướng dẫn sử dụng**
**Các chế độ hoạt động**

* Mũ có 3 chế độ: 
  - Tắt 
  - Chờ 
  - Hoạt động 

* Khi mới mua về thì mũ ở chế độ tắt, nếu người dùng muốn bật mũ từ chế độ này chỉ cần giữ nút nguồn 3s thì mũ sẽ chuyển sang chế độ chờ. 

* Khi ở chế độ chờ mũ chỉ chạy cảm biến nhận diện người dùng, khi đó nếu người dùng đội mũ lên thì lập tức mũ sẽ chuyển sang chế độ hoạt động. Ở chế độ này sẽ có một đèn LED trên nón sáng  nhấp nháy để báo là đang ở chế độ chờ.

* Ngược lại thì khi mũ đang hoạt động người dùng có thể chuyển sang chế độ chờ bằng cách cởi mũ ra. Tuy nhiên để tránh tình huống khi tai nạn xảy ra mũ bị văng ra rồi mới đập thì mũ sẽ đợi khoảng 100ms rồi mới chuyển sang chế độ chờ hoặc nếu mũ đang thực hiện một số chức năng (như gửi tín hiệu khẩn cấp) thì mũ sẽ thực hiện cho xong rồi mới chuyển sang chế độ chờ. 

* Nếu muốn tắt mũ thì người dùng sẽ nhấn nút nguồn khoảng 5s nếu mũ đang thực hiện gửi tín hiệu khẩn cấp thì mũ sẽ thực hiện cho xong mới tắt.

* Ở chế độ chờ mũ vẫn sẽ dùng pin nhưng ở một mức rất thấp nên, người dùng không nên chuyển về chế độ tắt vì khi mũ khởi động sẽ khá lâu và người dùng phải khởi động nón một cách thủ công. 

#### **I. Thiết đặt lần đầu**
* **Bước 1:** Bật mũ bảo hiểm (bằng cách bấm nút Power trên mũ). 
* **Bước 2:** Bật Bluetooth trên điện thoại. 
* **Bước 3:** Mở app trên điện thoại, mở hambergur menu (hình 3 gạch ở góc trái trên). 
* **Bước 4:** Chọn nút thêm (hình dấu cộng). 
* **Bước 5:** Nhập mã PIN (được ghi bên trong mũ). 
* **Bước 6:** Thiết lập: đặt tên mũ, các chức năng khác (theo hướng dẫn của app). 
* **Bước 7 (tùy chọn):** Chỉnh lại mã PIN. 

##### **II. Sử  dụng chức năng cảnh báo tốc độ:**
* Cần bật chức năng cảnh báo tốc độ (trong phần cài đặt). 
* Khi người dùng đội mũ bảo hiểm và chạy quá tốc độ được quy định (tùy thuộc người dùng đang ở đường nào và chỉnh tốc độ tối đa là bao nhiêu) thì mũ tự động thông báo mỗi 3 phút một lần đến khi người đó chạy đúng tốc độ. 

##### **III. Phát hiện va chạm và gửi tín hiệu khẩn cấp**
* Luôn bật, có thể chỉnh một vài thông số trong phần cài đặt như là: 
  - Mức độ để mũ kích hoạt việc gửi tín hiệu khẩn cấp. 
  - Số điện thoại người nhận tín hiệu khẩn cấp. 
  - Gửi tín hiệu khẩn cấp qua kênh nào. Có 2 kênh cho người dùng tự chọn. 
* Khi có va chạm thì mũ sẽ tự động thực hiện các bước: 
  - **Bước 1:** Đánh giá va chạm (dựa vào các dữ liệu thu được từ cảm biến gia tốc kế, vận tốc,...). 
  - **Bước 2:** Nếu va chạm nguy hiểm (lớn hơn hoặc bằng mức độ được cài đặt) thì mũ sẽ gửi tín hiệu theo các kênh được thiết đặt (và mũ sẽ sáng đèn đỏ để báo hiệu là bước gửi tín hiệu sắp được thực hiện). 
  - **Bước 3:** Trong 10 giây, nếu người dùng không gặp nguy hiểm thì người dùng có thể bấm vào nút nguồn 2 lần liên tiếp, khi đó mũ sẽ không gửi tín hiệu. 
  - **Bước 4:** Mũ sẽ gửi tín hiệu S.O.S. theo thứ tự danh sách người nhận trong cài đặt. 
 * Người dùng cũng có thể gửi tín hiệu bằng cách nhấn nút nguồn 2 lần.
 
##### **IV. Trợ lý giao thông**
###### **1. Chỉ đường:**
* **Bước 1:** Kết nối mũ với điện thoại, mở app điện thoại, vào chức năng bản đồ. 
* **Bước 2:** Chọn địa điểm đến, ứng dụng sẽ đưa ra những lộ trình để người dùng lựa chọn. 
* **Bước 3:** Sau khi chọn lộ trình chọn nút bắt đầu di chuyển, khi đó lộ trình sẽ được gửi qua mũ và mũ sẽ ra hiệu cách di chuyển. 

###### **2. Nghe điện thoại:**
* Trong phần cài đặt sẽ có 2 chế độ: 
  - Tự động trả lời (bằng một tin nhắn hoặc một đoạn ghi âm sẵn, lưu lại thông điệp của người gửi). 
  - Hỏi người dùng xem muốn trả lời hay không (dùng giọng nói hoặc nút bấm trên mũ). 
* Khi có cuộc gọi tới thì nếu người dùng đang đội mũ và bật chức năng tự động trả lời thì app trên điện thoại sẽ giúp trả lời tự động và có thể lấy thông điệp nếu cần. Còn khi người dùng chọn chức năng thứ 2 thì mũ sẽ đọc tên người gọi (hoặc số) rồi hỏi là muốn nghe hay không. Nếu không thì nói “không” để ra lệnh cho mũ ngắt cuộc gọi (hoặc trả lời tự động), và nếu muốn nghe thì nói “có”. Hoặc ngoài ra có thể bấm nút 2 lần để không nghe máy và 1 lần để nghe máy. Khi nghe điện thoại nên ngừng xe lại. 

###### **3. Đọc tin nhắn:**
* Trong phần cài đặt, người dùng có thể chọn bật chế độ nhận tín hiệu khi có tin nhắn tới.  
* Lúc đó, nếu có tin nhắn, mũ sẽ đọc thông tin người gửi. Người dùng có thể chọn nghe hoặc bỏ qua thông qua giọng nói hoặc nút bấm trên mũ. Hoặc người dùng có thể tắt chức năng này trong phần cài đặt bằng cách chọn không đọc tin nhắn.

###### **4. Nhắc nhở:**

**Cách đặt nhắc nhở:**

* **Bước 1:** Mở app, và phần nhắc nhở, chọn nút thêm (hình dấu “+”).
* **Bước 2:** Chọn địa điểm, thời gian, và nội dung công việc cần nhắc nhở.
* **Bước 3:** Đợi đồng bộ với mũ (nếu chưa kết nối với mũ).

Khi còn cách địa điểm khoảng 2 km thì mũ sẽ thông báo công việc cần làm tại địa điểm đó. Rồi khoảng 1 km thì mũ sẽ thông báo lại và khi người dùng thực hiện xong công việc thì có thể bấm nút hoàn thành trong app điện thoại, nếu không mũ sẽ thông báo thêm 1 lần nữa khi người đó rời khỏi địa điểm đó.

###### **5. Tìm mũ**
* Bật app trên điện thoại, vào phần tìm mũ, khi đó app sẽ cho biết  vị trí lần cuối mà mũ còn kết nối với điện thoại.
* Nếu trong phạm vi 40m thì có thể bật tính năng dò bằng bluetooth khi đó, app sẽ cho biết khoảng cách tương đối tới mũ và người dùng có thể tìm bằng cách di chuyển theo hướng cho khoảng cách này giảm đi.

##### **V. Camera hành trình**
* Camera hành trình sẽ được kích hoạt khi người dùng đội nón bảo hiểm. Trên đường đi nếu có tai nạn xảy ra hoặc nếu người dùng có yêu cầu (bấm nút nguồn trên nón 3 lần) thì đoạn video sẽ được cắt 5 phút cuối và lưu lại còn không thì khi bộ nhớ đầy đoạn video cũ nhất sẽ bị xóa.  

* Để xem lại video thì người dùng có thể dùng app điện thoại, trong phần video. Lưu ý cần phải kết nối với mũ thì mới có thể xem. Người dùng cũng có thể tải video về điện thoại và xóa đoạn video đó trên mũ.

* Đoạn video sẽ được lưu cùng với vị trí hiện tại, thời gian và vận tốc, người dùng có thể xem thông tin này trong app.


[Xem chi tiết và tải về](https://1drv.ms/w/s!AgJYhaQnQpM8pcF5Stn17Y1XqVU6qQ)

### **So sánh tổng quan giữa các loại mũ**


Thông tin  |  Full Head | 3/4 Head | 1/2 Head
-----------|------------|----------|----------
Gửi tín hiệu khẩn cấp| x | x | x
Định vị mũ | x | x | x
Cảnh báo tốc độ | x | x | o
Trợ lý giao thông | x | x | o
Camera hành trình | x | x | o
Giá bán (VNĐ) | 8.500.000 | 1.500.000 | 750.000



### **CÁC VẤN ĐỀ VÀ GIẢI PHÁP**
#### **I. MẶT KỸ THUẬT**
##### **1. Làm sao xác định được va chạm thế nào là gây nguy hiểm?**
- Chúng tôi sau khi tìm hiểu đã phát hiện một công thức tính toán độ va chạm gây nguy hiểm cho con người. Dưới đây là công thức được sử dụng và nguồn dẫn của công thức. 


![equation](https://wikimedia.org/api/rest_v1/media/math/render/svg/a1311fccb6d619c35edaac479d41079a9fbb7907)


Trong đó: 

          t1: Thời gian bắt đầu xảy ra va chạm (s).

          t2: Thời gian kết thúc va chạm. (s).
          
          a(t): gia tốc tại thời điểm t.

[ Xem chi tiết](https://en.wikipedia.org/wiki/Head_injury_criterion)

##### **2. Tại sao lại đặt các thiết bị ở những vị trí đó trên mũ?**
- Chúng tôi đã đánh giá tỉ lệ va chạm khi xảy ra trên các vùng của mũ để đảm bảo cho các thiết bị khi va chạm sẽ ít bị ảnh hưởng nhất. 
Đây là nguyên cứu về tỉ lệ được chứng minh. 

<p align="center">
  <img src="http://bikegearup.weebly.com/uploads/6/1/2/5/61250925/2104854_orig.jpg">  
<p align="center">
<b>Hình 4: Tỉ lệ va đập trên mũ</b><br>
</p>


[ Xem chi tiết](http://bikegearup.weebly.com/blog/the-important-in-wearing-motorcycle-helmet)

##### **3. Tại sao lại chọn các mẫu mũ bảo hiểm như vậy?**
-	Sau khi nghiên cứu các đặc điểm người tiêu dùng mũ bảo hiểm ở Việt Nam, chúng tôi quyết định chọn 3 kiểu dáng mà người tiêu dùng ưu chuộng nhất.
-	Ngoài ra, để đảm bảo sự an toàn của các thiết bị gắn bên trong, chúng tôi cũng sửa đổi một số cấu trúc của mũ. Tuy nhiên, chất lượng mũ vẫn được đảo bảo.

##### **4. Khối lượng mũ như vậy có ảnh hưởng gì đến người dùng không?**
- Hiện tại mũ bảo hiểm của chúng tôi chỉ nặng hơn loại thông thường khoảng 250g. Như vậy, so với những loại mũ nặng nhất thì cũng tương đương. Do đó, sẽ không có bất kì ảnh hưởng gì đến người dùng.

##### **5. Mũ có bảo đảm an toàn khi va đạp? Chống thấm nước? Các thiết bị có bị hư hại gì khi thời gian sử dụng dài?**
-	Chúng tôi thiết kế mũ được dùng trong các trường hợp đặc biệt. Vậy nên các bạn có thể yên tâm, nếu có xảy ra va chạm hoặc trời mưa, thiết bị cũng không gặp bất cứ trục trặc gì gây nguy hiểm cho người dùng. 

##### **6. Thiết bị thay thế khi bị hư hỏng?**
- Hiện tại, chúng tôi cung cấp một số thiết bị thay thế như Camera, Bluetooth, cảm biến va đạp, pin, ... Khách hàng có thể đến chi nhánh của công ty để được thay thế hàng chính hãng.

#### **II. MẶT KINH TẾ**
##### **1. Phân tích sơ bộ thị trường:**
- Thu nhập của người dân Việt Nam ngày càng tăng cao. Hiện nay, mức sống trung bình của một người trong khoảng từ 5-10 triệu đồng/tháng.


<p align="center">
  <img src=http://znews-photo.d.za.zdn.vn/w660/Uploaded/ovhunut/2016_11_02/grp1_1.png>  
<p align="center">
<b>Hình 6: Biểu đồ thu nhập năm chia theo nhóm thu nhập giai đoạn 2004-2014</b><br>
</p>

- Số lượng người dùng xe máy tính tới thời điểm hiện tại khoảng 45 triệu chiếc. 

=> Một thị trường lớn và đầy tiềm năng.

##### **2. Đối thủ kinh doanh:**
Tại Việt Nam, hiện nay chưa có loại mũ bảo hiểm thông minh nào được bày bán trên thị trường. Vậy nên sẽ có những thuận lợi và khó khăn sau:

a) Thuận lợi:
- Không phải cạnh tranh với các sản phẩm khác. 
- Thị trường rộng lớn, đa dạng.

b) Khó khăn:
- Bán những sản phẩm đầu tiên ở hạng mục này. 
- Chiếm được lòng tin của người tiêu dùng.

##### **3. Chiến lượt phát triển**
Để sản có thể đến rộng rãi hơn với người dùng, đầu tiên chúng tôi sẽ chú trọng phát triển 2 mảng lớn:

a) Sản phẩm Full Head dành cho người đi moto và dân phượt
- Đây là một phân khúc thị trường tiềm năng. Những khách hàng này có thu nhập cao và nhu cầu sử dụng mũ bảo hiểm Full Head thường xuyên. Tuy nhiên, yêu cầu của người dùng loại mũ này cũng rất khắc khe. 
- Chúng tôi sẽ tiếp cận một số nhóm phượt lớn tại Việt Nam, giới thiệu sản phẩm, cho họ dùng thử nghiệm để khảo sát được những điểm tốt và chưa tốt của mũ. Sau đó, tiến hành bán sản phẩm cho các nhóm này. Rồi dần dần họ sẽ là người quảng bá sản phẩm đến với dân phượt ở khắp nơi.

b) Sản phẩm 1/2 Head dành cho người dùng phổ thông
- Đây là phân khúc thị trường lớn. Người dùng phổ thông đa phần có thu nhập trung bình và nhu cầu sử dụng các tính năng của mũ không quá lớn. Chúng tôi tập trung chủ yếu phát triển hệ thống thông báo khi có sự cố xảy ra. Vậy nên giá thành của mũ khá phải chăng, phù hợp với hầu hết người điều khiển xe máy hiện nay. 

=> Xu hướng chung của người dân là quan tâm bảo vệ sức khỏe, tính mạng của mình và người thân. Vậy nên, sản phẩm ra đời sẽ tạo ra một cuộc cách mạng trong việc sử dụng các sản phẩm thông minh có giá vừa phải để chăm sóc và bảo vệ sức khỏe, tính mạng. 

##### **4. Tầm nhìn**
 Theo kế hoạch, đến năm 2020, công ty sẽ cung cấp cho 80% người điều khiển xe máy tại Việt Nam mũ bảo hiểu thông minh do team chúng tôi phát triển. Giá thành sản phẩm ngày càng phù hợp với người dùng phổ thông. Đặc biệt, sản xuất ra một số loại mũ siêu bền dành cho tầng lớp thượng lưu. 
 
 Song song với chiếm lĩnh thị trường Việt, chúng tôi sẽ hướng đến phân phối sản phẩm sang các nước Đông Nam Á lân cận như Campuchia, Thái Lan, Lào, .... Đồng thời sẽ tiến vào các thị trường khó tính như: Nga, Châu Âu, Hoa Kì, Nhật Bản. 

### **MỞ RỘNG**
#### **I. Các môn học liên quan đến CNTT cần thiết**
- Thiết kế giao diện.
- Lập trình nhúng.
- Phát triển phần mềm cho thiết bị di động.
- Cơ sở dữ liệu.
- Phương thức lập trình hướng đối tượng.
- Phát triển web.

#### **II. Các trang web tham khảo**

[http://bikegearup.weebly.com/blog/the-important-in-wearing-motorcycle-helmet](http://bikegearup.weebly.com/blog/the-important-in-wearing-motorcycle-helmet)

[http://www.hvcsnd.edu.vn/vn/Acedemy/Thong-tin-An-toan-giao/206/6344/Tinh-hinh-trat-tu-an-toan-giao-thong-nam-2016-tren-pham-vi-toan-quoc.aspx](http://www.hvcsnd.edu.vn/vn/Acedemy/Thong-tin-An-toan-giao/206/6344/Tinh-hinh-trat-tu-an-toan-giao-thong-nam-2016-tren-pham-vi-toan-quoc.aspx)

[http://news.zing.vn/oxfam-nguoi-giau-kiem-1-ngay-bang-nguoi-ngheo-kiem-10-nam-post694593.html](http://news.zing.vn/oxfam-nguoi-giau-kiem-1-ngay-bang-nguoi-ngheo-kiem-10-nam-post694593.html)

[http://vnexpress.net/tin-tuc/oto-xe-may/tuong-lai-nao-cho-xe-may-tai-viet-nam-3383030.html](http://vnexpress.net/tin-tuc/oto-xe-may/tuong-lai-nao-cho-xe-may-tai-viet-nam-3383030.html)

[https://en.wikipedia.org/wiki/Head_injury_criterion](https://en.wikipedia.org/wiki/Head_injury_criterion)

#### **III. Poster**
