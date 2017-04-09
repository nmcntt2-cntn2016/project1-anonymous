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
Hiện nay, tai nạn giao thông là một vấn đề nhức nhối trong xã hội. Trong năm 2016, nước ta xảy ra 21 589 vụ tai nạn, làm chết   8 685 người, bị thương 19 280 người. Có nhiều vụ tai nạn nếu được cấp cứu kịp thời, nạn nhân đã có thể được cứu sống. Vì vậy cần có một giải pháp để giảm thiểu thiệt hại bằng việc thông báo ngay lập tức cho người thân để hỗ trợ kịp thời.

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
* Người dùng phổ thông: Thích hợp với loại ½ head hoặc ¾ head. Họ thường xuyên di chuyển quảng đường từ ngắn đến trung bình. Những người này cần loại mũ gọn nhẹ, có những chức năng cơ bản, giá thành vừa phải vì họ thường có thu nhập khoảng 5 triệu đến 15 triệu một tháng. 
* Những người sử dụng moto, đi phượt hoặc thường xuyên di chuyển bằng xe gán máy trên đoạn đường dài: Thích hợp với loại mũ Full Head. Tuy giá thành cao nhưng với thu nhập của họ cùng tính năng của mũ khiến họ yên tâm hơn trên những chuyến đi xa.
* Người thân của người đi xe gán máy: Những người này tuy không có nhu cầu sử dụng nhưng họ có khả năng mua để tặng, thậm chí tác động đến người thân đang dùng xe máy của mình sử dụng mũ bảo hiểm thông minh. Thông thường những người này thuộc tầng lớp trung lưu đến thương lưu, thu nhập từ 10 triệu một tháng trở lên.

### **Chức năng**

<p align="center">
  <img src="https://scontent.fsgn5-1.fna.fbcdn.net/v/t34.0-12/17792412_646130398908109_1859550620_n.jpg?oh=af9d3199b995b42dde876ebcc62e8569&oe=58EAAC3D">  
<p align="center">
<b>Hình 4: Các chức năng</b><br>
</p>

### **Chi tiết về các chức năng**
#### **I.	Nhận diện người dùng**
*	Mũ được trang bị cảm biến giúp nhận dạng người dùng. Khi người dùng đội mũ, tất cả các chứng năng sẽ tự động bật

#### **II.	Phát hiện va chạm**
*	Khi có va chạm xảy ra, bộ cảm biến sẽ gửi tín hiệu đến trung tâm xử lý.
* Cách xác định va chạm:
  - Va chạm 1 lần với lực xác định.
  - Va chạm nhiều lần với lực xác định.

#### **III.	 Định vị mũ**
*	Mũ được kết hợp với thiết bị định vị GPS. Định vị và tự động ghi lại vị trí sau một khoảng thời gian, thông qua đó biết được vị trí xe khi cần thiết.

#### **IV.	Gửi tín hiệu khẩn cấp**
*	Trung tâm xử lý sẽ gửi tin nhắn đến các số điện thoại được đăng kí trước khi nhận được tìn hiệu từ cảm biến va chạm.
* Nội dung tin nhắn sẽ bao gồm:
  - Vị trí của người sử dụng gặp sự cố theo GPS.
  - Thời gian thực được lưu lại.
  - SOS
  - Chỉ số HIC và tốc độ xe tại thời điểm đó.
  -	Hình ảnh cắt từ camera (nếu có Internet).

#### **V.	Cảnh báo tốc độ**
* Khi người điều khiển xe chạy đến một tốc độ nguy hiểm (do người dùng đặt) thì mũ sẽ cảnh báo người dùng.

#### **VI.	Trợ lý giao thông**
##### **1. Tìm đường**
*	Kết nối với điện thoại thông qua BLUETOOTH. Chiếc mũ sẽ như một trợ lý ảo chỉ đường cho người dùng thông qua loa trên mũ khi người dùng sử dụng "Bản đồ" trên ứng dụng điện thoại để tìm đường đi.

##### **2. Tự động trả lời điện thoại và đọc tin nhắn.**
*	Do được kết nối với điện thoại, khi điện thoại nhận được cuộc gọi, loa gắn trên mũ sẽ thông báo cho người đội mũ biết. Người dùng có thể nói vào mic để trả lời hoặc từ chối cuộc gọi thông qua một số câu lệnh có sẵn. Tương tự, khi có tin nhắn, người đội mũ sẽ được thông báo. Người đội mũ có thể sử dụng chức năng đọc tin nhắn đến của mũ để nghe tin nhắn. Hiện tại, mũ chỉ mới đáp ứng 2 ngôn ngữ: Tiếng Việt và Tiếng Anh.

#### **VIII.	Camera hành trình**
*	Camera được tích hợp để ghi lại 5 phút sau cùng. Nếu có sự cố xảy ra, camera tự động ghi cho đến khi đầy bộ nhớ.  Người dùng có thể thay đổi thẻ nhớ. Camera có tầm mở rộng 120 độ. 

### **Bản thiết kế**
### **Thông số kĩ thuật**
### **Quy trình vận hành**
### **Sơ lược về ứng dụng điện thoại**
### **Hướng dẫn sử dụng**
#### **I.Thiết đặt lần đầu**
* Bước 1: Bật mũ bảo hiểm (bằng cách bấm nút Power trên mũ). 
* Bước 2: Bật Bluetooth trên điện thoại. 
* Bước 3: Mở app trên điện thoại, mở hambergur menu (hình 3 gạch ở góc trái trên). 
* Bước 4: Chọn nút thêm (hình dấu cộng). 
* Bước 5: Nhập mã PIN (được ghi bên trong mũ). 
* Bước 6: Thiết lập: đặt tên mũ, các chức năng khác (theo hướng dẫn của app). 
* Bước 7 (tùy chọn): Chỉnh lại mã PIN. 

##### **II. Sử  dụng chức năng cảnh báo tốc độ:**
* Cần bật chức năng cảnh báo tốc độ (trong phần cài đặt). 
* Khi người dùng đội mũ bảo hiểm và chạy quá tốc độ được quy định (tùy thuộc người dùng đang ở đường nào và chỉnh tốc độ tối đa là bao nhiêu) thì mũ tự động thông báo mỗi 5 phút một lần đến khi người đó chạy đúng tốc độ. 

##### **III. Phát hiện va chạm và gửi tín hiệu khẩn cấp**
* Luôn bật, có thể chỉnh một vài thông số trong phần cài đặt như là: 
  - Mức độ để mũ kích hoạt việc gửi tín hiệu khẩn cấp. 
  - Số điện thoại người nhận tín hiệu khẩn cấp. 
  - Gửi tín hiệu khẩn cấp qua kênh nào. Có 2 kênh cho người dùng tự chọn. 
* Khi có va chạm thì mũ sẽ tự động thực hiện các bước: 
  - Bước 1: Đánh giá va chạm (dựa vào các dữ liệu thu được từ cảm biến gia tốc kế, vận tốc,...). 
  - Bước 2: Nếu va chạm nguy hiểm (lớn hơn hoặc bằng mức độ được cài đặt) thì mũ sẽ gửi tín hiệu theo các kênh được thiết đặt (và mũ sẽ sáng đèn đỏ để báo hiệu là bước gửi tín hiệu sắp được thực hiện). 
  - Bước 3: Trong 10 giây, nếu người dùng không gặp nguy hiểm thì người dùng có thể bấm vào nút nguồn 2 lần liên tiếp, khi đó mũ sẽ không gửi tín hiệu. 
  - Bước 4: Mũ sẽ gửi tín hiệu S.O.S. theo thứ tự danh sách người nhận trong cài đặt. 
  
##### **IV. Trợ lý giao thông**
###### **1. Chỉ đường:**
* Bước 1: Kết nối mũ với điện thoại, mở app điện thoại, vào chức năng bản đồ. 
* Bước 2: Chọn địa điểm đến, ứng dụng sẽ đưa ra những lộ trình để người dùng lựa chọn. 
* Bước 3: Sau khi chọn lộ trình chọn nút bắt đầu di chuyển, khi đó lộ trình sẽ được gửi qua mũ và mũ sẽ ra hiệu cách di chuyển. 

###### **2. Nghe điện thoại:**
* Trong phần cài đặt sẽ có 2 chế độ: 
  - Tự động trả lời (bằng một tin nhắn hoặc một đoạn ghi âm sẵn, lưu lại thông điệp của người gửi). 
  - Hỏi người dùng xem muốn trả lời hay không (dùng giọng nói hoặc nút bấm trên mũ). 
* Khi có cuộc gọi tới thì nếu người dùng đang đội mũ và bật chức năng tự động trả lời thì app trên điện thoại sẽ giúp trả lời tự động và có thể lấy thông điệp nếu cần. Còn khi người dùng chọn chức năng thứ 2 thì mũ sẽ đọc tên người gọi (hoặc số) rồi hỏi là muốn nghe hay không. Nếu không thì nói “không” để ra lệnh cho mũ ngắt cuộc gọi (hoặc trả lời tự động), và nếu muốn nghe thì nói “có”. Hoặc ngoài ra có thể bấm nút 2 lần để không nghe máy và 1 lần để nghe máy. Khi nghe điện thoại nên ngừng xe lại. 

###### **3. Đọc tin nhắn:**
* Trong phần cài đặt, người dùng có thể chọn bật chế độ nhận tín hiệu khi có tin nhắn tới.  
* Lúc đó, nếu có tin nhắn, mũ sẽ đọc thông tin người gửi. Người dùng có thể chọn nghe hoặc bỏ qua thông qua giọng nói hoặc nút bấm trên mũ. 

### **CÁC VẤN ĐỀ VÀ GIẢI PHÁP**
#### **I. MẶT KỸ THUẬT**
##### **1. Làm sao xác định được va chạm thế nào là gây nguy hiểm?**
- Chúng tôi sau khi nguyên cứu đã tìm ra được một công thức tính toán độ va chạm gây nguy hiểm cho con người. Dưới đây là công thức được sử dụng và nguồn dẫn của công thức. 


![equation](https://wikimedia.org/api/rest_v1/media/math/render/svg/a1311fccb6d619c35edaac479d41079a9fbb7907)


Trong đó: 

          t1: Thời gian bắt đầu xảy ra va chạm. (s)

          t2: Thời gian kết thúc va chạm. (s)
          
          a(t): gia tốc tại thời điểm t

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
