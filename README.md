# _**MBH++**_  - *Anonymous* <h1> 
 *created by GitHub Classroom* 
 
 [_Trang chủ Team_](https://nmcntt2-anonymous.github.io/)
 
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
Hiện nay, tai nạn giao thông là một vấn đề nhức nhối trong xã hội. Trong năm 2016, nước ta xảy ra 21 589 vụ tai nạn, làm chết 8685 người, bị thương 19280 người. Có nhiều vụ tai nạn nếu được cấp cứu kịp thời, nạn nhân đã có thể được cứu sống. Vì vậy cần có một giải pháp để giảm thiểu thiệt hại bằng việc thông báo ngay lập tức cho người thân để hỗ trợ kịp thời.
**Image**

### **Mục đích**
Hạn chế tình trạng phát hiện sự cố quá trễ dẫn đến thiệt hại về con người. Đồng thời hỗ trợ người điều khiển xe trong quá trình tham gia giao thông.

### **Đối tượng hướng đến**
* Người dùng phổ thông: Thích hợp với loại ½ head hoặc ¾ head. Họ thường xuyên di chuyển quảng đường từ ngắn đến trung bình. Những người này cần loại mũ gọn nhẹ, có những chức năng cơ bản, giá thành vừa phải vì họ thường có thu nhập khoảng 5tr-15tr một tháng. 
* Những người sử dụng moto, đi phượt hoặc thường xuyên di chuyển bằng xe gán máy trên đoạn đường dài: Thích hợp với loại mũ Full Head. Tuy giá thành cao nhưng với thu nhập của họ cùng tính năng của mũ khiến họ yên tâm hơn trên những chuyến đi xa.
* Người thân của người đi xe gán máy: Những người này tuy không có nhu cầu sử dụng nhưng họ có khả năng mua để tặng, thậm chí tác động đến người thân đang dùng xe máy của mình sử dụng mũ bảo hiểm thông minh. Thông thường những người này thuộc tầng lớp trung lưu đến thương lưu, thu nhập từ 10tr một tháng trở lên.

### **Chức năng**
* Tự động gửi tín hiệu cho người thân khi gặp sự cố (tai nạn, va chạm…): Khi mũ được đội lên đầu người sử dụng, nếu bị va chạm xác định gây nguy hiểm, mũ sẽ tự động xác nhận là xảy ra sự cố để báo về điện thoại được liên kết thông qua SIM được gắn trên mũ và thông qua điện thoại được kết nối.
* Kết nối với điện thoại thông minh.
  - Kết nối với bản đồ để tìm và dẫn đường bằng giọng nói.
  - Đo tốc độ và cảnh báo nếu tới ngưỡng nguy hiểm.
  - Hỗ trợ trả lời điện thoại:
  - Trả lời cuộc gọi: Khi có cuộc gọi, mũ sẽ báo cho người dùng để người dùng quyết định sẽ trả lời hay không trả lời. Nếu cần thiết, mũ sẽ thực hiện chức năng trả lời tự động.
  - Đọc tin nhắn: Người dùng có thể chọn có đọc tin nhắn hay là không. Nếu chọn trả lời tin nhắn, mũ bảo hiểm sẽ tự động đọc tin nhắn cho người dùng.
  - Tránh kẹt xe: Cập nhật tình hình giao thông trong khu vực để thông báo khu vực kẹt xe đến người dùng.
* Ghi lại vị trí và tích hợp camera hành trình: Có thẻ nhớ để quay video, tự động ghi hình mỗi 5 phút sau cùng.
* Định vị và tự động ghi lại vị trí sau một khoảng thời gian, thông qua đó biết được vị trí xe khi cần thiết.

### **CÁC VẤN ĐỀ VÀ GIẢI PHÁP**
#### **I. MẶT KỸ THUẬT**
##### **1. Làm sao xác định được va chạm thế nào là gây nguy hiểm?**
- Chúng tôi sau khi nguyên cứu đã tìm ra được một công thức tính toán độ va chạm gây nguy hiểm cho con người. Dưới đây là công thức được sử dụng và nguồn dẫn của công thức. [ Bấm vào đây!](https://en.wikipedia.org/wiki/Head_injury_criterion)

##### **2. Tại sao lại đặt các thiết bị ở những vị trí đó trên mũ?**
- Chúng tôi đã đánh giá tỉ lệ va chạm khi xảy ra trên các vùng của mũ để đảm bảo cho các thiết bị khi va chạm sẽ ít bị ảnh hưởng nhất. 
Đây là nguyên cứu về tỉ lệ được chứng minh. [ Bấm vào đây!](http://bikegearup.weebly.com/blog/the-important-in-wearing-motorcycle-helmet)

##### **3. Tại sao lại chọn các mẫu mũ bảo hiểm như vậy?**
-	Sau khi nghiên cứu các đặc điểm người tiêu dùng mũ bảo hiểm ở Việt Nam, chúng tôi quyết định chọn 3 kiểu dáng mà người tiêu dùng ưu chuộng nhất.
-	Ngoài ra, để đảm bảo sự an toàn của các thiết bị gắn bên trong, chúng tôi cũng sửa đổi một số cấu trúc của mũ. Tuy nhiên, chất lượng mũ vẫn được đảo bảo.

##### **4. Khối lượng mũ như vậy có ảnh hưởng gì đến người dùng không?**
- Hiện tại mũ bảo hiểm của chúng tôi chỉ nặng hơn loại thông thường khoảng 250g. Như vậy, so với những loại mũ nặng nhất thì cũng tương đương. Do đó, sẽ không có bất kì ảnh hưởng gì đến người dùng.

##### **5. Mũ có bảo đảm an toàn khi va đạp? Chống thấm nước? Các thiết bị có bị hư hại gì khi thời gian sử dụng dài?**
-	Chúng tôi thiết kế mũ được dùng trong các trường hợp đặc biệt. Vậy nên các bạn có thể yên tâm, nếu có xảy ra va chạm hoặc trời mưa, thiết bị cũng không gặp bất cứ trục trặc gì gây nguy hiểm cho người dùng. 

#### **II. MẶT KINH TẾ**
##### **1. Phân tích sơ bộ thị trường:**
- Thu nhập của người dân Việt Nam ngày càng tăng cao. Hiện nay, mức sống trung bình của một người trong khoảng từ 5-10 triệu đồng/tháng.

![alt tag](http://znews-photo.d.za.zdn.vn/w660/Uploaded/ovhunut/2016_11_02/grp1_1.png)

- Số lượng người dùng xe máy tính tới thời điểm hiện tại khoảng 45 triệu chiếc. 
