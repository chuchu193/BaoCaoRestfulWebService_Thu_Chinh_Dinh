# BaoCaoRestfulWebService_Thu_Chinh_Dinh

<h1> Mô hình server và client của Restful web service </h1>

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