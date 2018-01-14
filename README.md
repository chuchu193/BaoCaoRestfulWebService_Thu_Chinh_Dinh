
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

<h2> Ưu điểm của Restful WebService : </h2>
So sánh với SOAP:<br>
- Không có tools đắt tiền nào yêu cầu tương tác với Web service <br>
- Smaller learning curve<br>
- Hiệu quả (SOAP sử dụng XML cho tất cả các truyền tin, REST có thể sử dụng định dạng truyền tin ngắn gọn hơn)<br>
- Nhanh (không yêu cầu xử lý rộng rãi)<br>
- Gần gũi hơn với các công nghệ Web khác trong triết lý design.<br>

<h2> Phía Client ( Client-Side) </h2>
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
