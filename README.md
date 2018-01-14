# BaoCaoRestfulWebService_Thu_Chinh_Dinh

<h2> 1 Mô hình server và client của Restful web service </h2>

###  RESTful Service
- Là một dịch vụ web đơn giản sử dụng HTTP và tính chất của REST.
- Nó tuân thủ theo 4 nguyên tắc thiết kế cơ bản sau:
### 1 Sử dụng các phương thức HTTP một cách rõ ràng
- Thiết lập một ánh xạ 1-1 giữa các hành động: tạo, đọc, cập nhật và xoá (CRUD) các quá trình vận hành và các phương thức HTTP:
POST (HttpPost) – Tạo một tài nguyên trên máy chủ
GET (HttpGet) – Truy xuất một tài nguyên
PUT (HttpPut) – Thay đổi trạng thái một tài nguyên hoặc để cập nhật nó
DELETE (HttpDelete) – Huỷ bỏ hoặc xoá một tài nguyên
### 2 Phi trạng thái
- Mô hình phi trạng thái
<img src="https://duythanhcse.files.wordpress.com/2015/11/h68-2.png">
- Mô hình trạng thái
<img src="https://duythanhcse.files.wordpress.com/2015/11/h68-1.png">

### 3 Hiển thị cấu trúc thư mục như URls
- Cấu trúc địa chỉ của RESTful service:
Giấu các đuôi tài liệu mở rộng của bản gốc trong máy chủ (.jsp, .php, .asp).
Để mọi thứ là chữ thường (thực ra là không phân biệt, nhưng cũng nên tuân thủ để khỏi phải nhớ HOA-thường lung tung).
Thay thế các khoảng trống bằng gạch chân hoặc gạch nối (một trong hai loại).
Tránh các chuỗi yêu cầu.
Thay vì sử dụng mã (404 Not Found) khi yêu cầu địa chỉ cho một phần đường dẫn thì luôn luôn cung cấp một trang mặc định hoặc tài nguyên như một phản hồi.
	
### 4 Chuyển đổi linh hoạt JavaScript Object Notation (JSON) và XML hoặc cả hai
- Là một bản tóm tắt các thuộc tính của những thứ trong mô hình dữ liệu hệ thống.
- Định dạng dữ liệu mà ứng dụng và trao đổi dịch vụ trong mức đáp ứng yêu cầu/ phản hồi hoặc trong phần thân của HTTP.
- Các chủ thể trong mô hình dữ liệu có liên quan với nhau.
- Cấu trúc dịch vụ sao cho nó tận dụng được phần đầu chấp nhận HTTP có sẵn bên trong – một loại MIME
=======

<h2> 2 Ưu điểm của Restful WebService : </h2>
So sánh với SOAP:<br>
- Không có tools đắt tiền nào yêu cầu tương tác với Web service <br>
- Smaller learning curve<br>
- Hiệu quả (SOAP sử dụng XML cho tất cả các truyền tin, REST có thể sử dụng định dạng truyền tin ngắn gọn hơn)<br>
- Nhanh (không yêu cầu xử lý rộng rãi)<br>
- Gần gũi hơn với các công nghệ Web khác trong triết lý design.<br>

<h2> 3. Các công nghệ, nền tảng cho server side. </h2>
Ngôn ngữ lập trình server là những ngôn ngữ chạy phía server ( server-side). Đây là những ngôn ngữ được các lập trình viên sử dụng để viết các chương trình, tiện ích chạy trên các server. Trong lĩnh vực này, các lập trình viên có rất nhiều lựa chọn để chọn cho mình một công nghệ phù hợp như sử dụng ASP, Java, Perl, PHP, Python, Ruby, Node.js, Swift... Chúng ta sẽ tìm hiểu sơ qua về các ngôn ngữ lập trình và công nghệ phía server này nhé.###  3.1 ASP.Net
### 3.1 ASP.Net
Microsoft Active Server Pages (ASP) là một môi trường sever-side scripting cho phép ta tạo ra và chạy các ứng dụng Web động, tương tác với client một cách hiệu quả. Nó cho phép chúng ta sử dụng tất cả các tính năng của một ngôn ngữ lập trìnnh như C# hay VB.NET, html, javascript, css để tạo trang Web dễ dàng.
![asp](https://user-images.githubusercontent.com/35051952/34913333-64a943ae-f92c-11e7-8153-c60e8653142f.PNG)
### 3.2 Java
Java là một trong những ngôn ngữ lập trình hướng đối tượng phổ biến. Nó giúp cho các lập trình viên phát triển các ứng dụng mà có thể chạy trên nhiều thiết bị phần cứng và hệ điều hành khác nhau. Java là một ngôn ngữ lập trình có tính bảo mật cao, hướng đối tượng, bậc cao và mạnh mẽ.
### 3.3 Perl
Perl là ngôn ngữ lập trình có khả năng chắt lọc một lượng lớn dữ liệu và cho phép xử lí dữ liệu nhằm thu được kết quả cần tìm. Nó thì có tốc độ xử lý văn bản nhanh đến mức kinh ngạc, nhưng không được sử dụng nhiều trong thế giới Internet hiện đại. 
Tuy nhiên hầu như tất cả các hacker đều có một số thủ thuật được viết bởi Perl, vì thế nó cũng đáng giá để bạn để tâm nghiên cứu vào một lúc nào đó.
Perl được xây dựng ra một trong ứng dụng quan trọng là tạo ra các website tương tác. Có rất nhiều mã kịch bản Perl dùng để xử lý biểu mẫu, tạo sổ khách hàng, tạo các diễn đàn trên nền web, đếm số người truy cập một trang web… 
Perl cũng được biết đến với việc vận hành OOP (lập trình hướng đối tượng) và hỗ trợ tất cả các hình thức thừa kế, đa hình và đóng gói.
Perl đủ linh hoạt để hỗ trợ thực hiện theo thủ tục cũng như OOP đồng thời.
Perl cũng có thêm các mô-đun cho phép bạn viết / sử dụng / tái sử dụng mã được viết bằng Python, PHP, PDL, TCL, Octave, Java, C, C ++, Basic, Ruby và Lua trong kịch bản Perl của bạn. Điều 
này có nghĩa là bạn có thể kết hợp Perl với các ngôn ngữ lập trình bổ sung thay vì viết lại mã hiện có.

![perl](https://user-images.githubusercontent.com/35051952/34914292-64c27412-f942-11e7-93af-ed9abafecd59.png)
### 3.4 PHP
PHP là ngôn ngữ kịch bản máy chủ (server-side) được sử dụng trên Internet ngày nay — nó chạy trên 75% của tất cả các máy chủ Web — và là sức mạnh phía sau của các nền tảng như WordPress, Wikipedia, và thậm chí là một phần của Facebook.   
![php](https://user-images.githubusercontent.com/35051952/34914960-b7111554-f94f-11e7-8eed-2e1685f4c74c.PNG)
### 3.5 Python
Python là một ngôn ngữ lập trình thông dịch do Guido van Rossum tạo ra năm 1990. Python hoàn toàn tạo kiểu động và dùng cơ chế cấp phát bộ nhớ tự động; do vậy nó tương tự như Perl, Ruby, Scheme, Smalltalk, và Tcl. Python được phát triển trong một dự án mã mở, do tổ chức phi lợi nhuận Python Software Foundation quản lý.
![python](https://user-images.githubusercontent.com/35051952/34914698-70c37812-f94a-11e7-8d15-ed4a4b4c78b0.PNG)  
### 3.6 Ruby
Ruby là ngôn ngữ lập trình kịch bản bởi mã lệnh của Ruby có thể chạy trực tiếp bởi máy tính mà không cần phải biên soạn thành một tệp thực thi tệp tin .exe trên Windows hay tệp tin binary trên Linux. Ruby, và framework phát triển ứng dụng web của nó là Ruby On Rails, là nguồn sức mạnh cho một số trang web lớn như là Groupon, Shopify (một nền tảng thương mại điện tử), và được dùng để xây dựng front-end cho mạng xã hội Twitter.
Nó là một ngôn ngữ hoàn toàn hướng đối tượng và được thông dịch bởi server trước khi gửi mã HTML tới trình duyệt của người dùng — cũng giống như PHP (nhưng cũng có nhiều điểm hoàn toàn khác biệt). Tuy nhiên, nó có một số đặc điểm nổi trội đó là phát triển ứng dụng nhanh chóng, viết ít code bị lặp lại, và tốc độ thực thi khá nhanh.
### 3.7 Node.js
Node.js là 1 nền tảng chạy trên môi trường V8 Javascript runtime. Node.js cho phép lập trình viên xây dựng các ứng dụng có tính mở rộng cao sử dụng Javascript trên server.
Và vì được porting từ C nên về mặt tốc độ xử lý thì rất nhanh.Node.js cho phép các nhà phát triển ứng dụng chỉ cần sử dụng Javascript để lập trình cho cả client side và server side, đưa Javascript từ một ngôn ngữ thuần client side có thể thực hiện các công việc phía sever mà trước đây phải do PHP, Ruby in Rails, Perl,... thực hiện.
    + Dưới đây là những lý do mà bạn không nên bỏ qua nền tảng này.
       - Đặc điểm nổi bật của Node.js là nó nhận và xử lý nhiều kết nối chỉ với một single-thread. Điều này giúp hệ thống tốn ít RAM nhất và chạy nhanh nhất khi không phải tạo thread mới cho mỗi truy vấn giống PHP. Ngoài ra, tận dụng ưu điểm non-blocking I/O của Javascript mà Node.js tận dụng tối đa tài nguyên của server mà không tạo ra độ trễ như PHP
       - Với cơ chế event-driven, non-blocking I/O(Input/Output) và mô hình kết hợp với Javascript là sự lựa chọn tuyệt vời cho các dịch vụ Webs làm bằng JSON.
       - Nếu bạn định viết 1 ứng dụng thể hiện trên 1 trang (Gmail?) NodeJS rất phù hợp để làm. Với khả năng xử lý nhiều Request/s đồng thời thời gian phản hồi nhanh. Các ứng dụng bạn định viết không muốn nó tải lại trang, gồm rất nhiều request từ người dùng cần sự hoạt động nhanh để thể hiện sự chuyên nghiệp thì NodeJS sẽ là sự lựa chọn của bạn.
       - NodeJS sẽ tận dụng tối đa Unix để hoạt động. Tức là NodeJS có thể xử lý hàng nghìn Process và trả ra 1 luồng khiến cho hiệu xuất hoạt động đạt mức tối đa nhất và tuyệt vời nhất.
       - Các web thông thường gửi HTTP request và nhận phản hồi lại (Luồng dữ liệu). Giả xử sẽ cần xử lý 1 luồng giữ liệu cực lớn, NodeJS sẽ xây dựng các Proxy phân vùng các luồng dữ liệu để đảm bảo tối đa hoạt động cho các luồng dữ liệu khác.Điều này giúp hệ thống tốn ít RAM nhất và chạy nhanh nhất khi không phải tạo thread mới cho mỗi truy vấn giống PHP. Cùng xem mô hình dưới đây để hiểu tại sao Node.js được đánh giá cao hơn.
![node](https://user-images.githubusercontent.com/35051952/34914927-1c290e8e-f94f-11e7-9f0c-cc2aa08cc5d7.png)

<h2> 4 Phía Client ( Client-Side) </h2>
Client-side là tên gọi chung của các ngôn ngữ chạy trên Client.<br>
**Sử dụng:**<br>
- Tạo ra những trang tương tác.<br>
- Làm cho web trở nên sinh động hơn với các thành phần động.<br>
- Tương tác với bộ lưu trữ tạm thời, và bộ lưu trữ cục bộ (Cookie, localStorage).<br>
- Gửi yêu cầu cho Server và nhận phản hồi từ nó.<br>
- Cung cấp dịch vụ remote cho các ứng dụng client-side, như là đăng ký bản quyền, gửi nội dung, hay là các game multiplayer.<br>
**Nền tảng:**<br>
- Javascript (phổ biến nhất).<br>
- HTML *.<br>
- CSS *.<br>
Bất kỳ ngôn ngữ nào chạy trên thiết bị client mà có tương tác với dịch vụ remote đều được gọi là ngôn ngữ client-side.<br>
* HTML và CSS không phải là ngôn ngữ lập trình, nó chỉ giúp định dạng website để hiển thị khi Client nhận phản hồi từ Server và các ngôn ngữ này là ngôn ngữ markup.

**JavaScipt:**<br>
*JavaScript là gì ?*
JavaScript là một ngôn ngữ lập trình đa nền tảng (cross-platform), ngôn ngữ lập trình kịch bản, hướng đối tượng. JavaScript là một ngôn ngữ nhỏ và nhẹ (small and lightweight). Khi nằm bên trong một môi trường (host environment), JavaScript có thể kết nối tới các object của môi trường đó và cung cấp các cách quản lý chúng (object).<br>
JavaScript chứa các thư viện tiêu chuẩn cho các object, ví dụ như:  Array, Date, và Math, và các yếu tố cốt lõi của ngôn ngữ lập trình như: toán tử (operators), cấu trúc điều khiển (control structures), và câu lệnh. JavaScript có thể được mở rộng cho nhiều mục đích bằng việc bổ sung thêm các object; ví dụ:<br>
- Client-side JavaScript - JavaScript phía máy khách, JavaScript được mở rộng bằng cách cung cấp các object để quản lý trình duyệt và Document Object Model (DOM)  của nó. Ví dụ, phần mở rộng phía máy khách cho phép một ứng dụng tác động tới các yếu tố trên một trang HTML và phản hồi giống các tác động của người dùng như click chuột, nhập form, và chuyển trang.
