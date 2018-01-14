﻿
<h2> 3. Các công nghệ, nền tảng cho server side. </h2>

  Ngôn ngữ lập trình server là những ngôn ngữ chạy phía server ( server-side). Đây là những ngôn ngữ được các lập trình viên sử dụng để viết các chương trình, tiện ích chạy trên các server. Trong lĩnh vực này, các lập trình viên có rất nhiều lựa chọn để chọn cho mình một công nghệ phù hợp như sử dụng ASP, Java, Perl, PHP, Python, Ruby, Node.js, Swift... Chúng ta sẽ tìm hiểu sơ qua về các ngôn ngữ lập trình và công nghệ phía server này nhé.
  ###  3.1 ASP.Net
   Microsoft Active Server Pages (ASP) là một môi trường sever-side scripting cho phép ta tạo ra và chạy các ứng dụng Web động, tương tác với client một cách hiệu quả. Nó cho phép chúng ta sử dụng tất cả các tính năng của một ngôn ngữ lập trìnnh như C# hay VB.NET, html, javascript, css để tạo trang Web dễ dàng.
    + Các ưu điểm của ASP.NET
     - ASP.Net sử dụng phong cách lập trình mới: Code behide. Tách code riêng, giao diện riêng . Dễ đọc, dễ quản lý và bảo trì.
     - Hỗ trợ nhiều web server control .
     - Hỗ trợ thiết kế và xây dựng MasterPage lồng nhau.
     - Hỗ trợ bẫy lỗi (debug) JavaScript
     - Hỗ trợ kỹ thuật truy cập dữ liệu mới LINQ
     - Hỗ trợ kỹ thuật bất đồng bộ ASP.Net Ajax
     - ASP.Net hỗ trợ mạnh mẽ bộ thư viện phong phú và đa dạng của .Net Framework, làmviệc với XML, Web Service, truy cập cơ sở dữ liệu qua ADO.Net, …
     - ASPX và ASP có thể cùng hoạt động trong 1 ứng dụng.
     - Kiến trúc lập trình giống ứng dụng trên Windows.
     - Hỗ trợ quản lý trạng thái của các control
     - Tự động phát sinh mã HTML cho các Server control tương ứng với từng loại Browser
     - Hỗ trợ nhiều cơ chế Cache…
     - Trang ASP.Net được biên dịch trước. Thay vì phải đọc và thông dịch mỗi khi trang web được yêu cầu, ASP.Net biên dịch những trang web động thành những tập tin DLL mà Server có thể thi hành nhanh chóng và hiệu quả. Làm gia tăng tốc độ thực thi so với kỹ thuật thông dịch của ASP…
                            Mô phỏng quá trình biên dịch trong ASP.NET
     ![asp](https://user-images.githubusercontent.com/35051952/34913333-64a943ae-f92c-11e7-8153-c60e8653142f.PNG)

   ###  3.2 Java
   Java là một trong những ngôn ngữ lập trình hướng đối tượng phổ biến. Nó giúp cho các lập trình viên phát triển các ứng dụng mà có thể chạy trên nhiều thiết bị phần cứng và hệ điều hành khác nhau. Java là một ngôn ngữ lập trình có tính bảo mật cao, hướng đối tượng, bậc cao và mạnh mẽ.
   Những đặc trưng của java
     + Viết 1 lần chạy mọi nơi : một chương trình viết bằng Java sẽ được biên dịch ra mã máy ảo java,sau đó sẽ được chuyển thành mã máy tương ứng,máy ảo java có thể tương thích với các hệ điều hành trên các kiểu CPU khác nhau.
     + Hướng đối tượng : java là một ngôn ngữ hướng đối tượng hoàn toàn.
     + Đa nhiệm – đa luồng : cho phép nhiều tiến trình, tiểu trình có thể chạy song song cùng một thời điểm và tương tác với nhau.
     + Hỗ trợ mạnh cho việc phát triển ứng dụng : cung cấp nhiều công cụ, thư viện lập trình phong phú hỗ trợ cho việc phát triển nhiều loại hình ứng dụng khác nhau cụ thể như: ứng dụng đơn, ứng dụng client-server; ứng dụng trên các thiết bị di động, không dây, …
    + Ưu điểm ngôn ngữ lập trình Java:
      - Dùng mã nguồn mở (có thể chạy trên Apache hoặc IIS) 
      - Mã nguồn rõ ràng, mã nguồn tách biệt với giao diện HTML.
      - Visual Studio có thể sinh mã, tiết kiệm thời gian viết code.
      - Dễ học khi đã biết HTML, C + Có thể dùng PHP, Ruby… để GUI.
      - Dựa vào XAMP + Tomcat plugin (dễ cấu hình).
      - Đi cặp Oracle.
      - Hoạt động trên Linux, có thể trên IIS – Windows!
      - Nếu ko có Java Studio thì xài Eclipse, NetBean … viết code!
 
   ###  3.3 Perl
   Perl là ngôn ngữ lập trình có khả năng chắt lọc một lượng lớn dữ liệu và cho phép xử lí dữ liệu nhằm thu được kết quả cần tìm. Nó thì có tốc độ xử lý văn bản nhanh đến mức kinh ngạc, nhưng không được sử dụng nhiều trong thế giới Internet hiện đại. 
   Tuy nhiên hầu như tất cả các hacker đều có một số thủ thuật được viết bởi Perl, vì thế nó cũng đáng giá để bạn để tâm nghiên cứu vào một lúc nào đó.
   Perl được xây dựng ra một trong ứng dụng quan trọng là tạo ra các website tương tác. Có rất nhiều mã kịch bản Perl dùng để xử lý biểu mẫu, tạo sổ khách hàng, tạo các diễn đàn trên nền web, đếm số người truy cập một trang web… 
   Perl cũng được biết đến với việc vận hành OOP (lập trình hướng đối tượng) và hỗ trợ tất cả các hình thức thừa kế, đa hình và đóng gói.
   Perl đủ linh hoạt để hỗ trợ thực hiện theo thủ tục cũng như OOP đồng thời.
   Perl cũng có thêm các mô-đun cho phép bạn viết / sử dụng / tái sử dụng mã được viết bằng Python, PHP, PDL, TCL, Octave, Java, C, C ++, Basic, Ruby và Lua trong kịch bản Perl của bạn. Điều 
   này có nghĩa là bạn có thể kết hợp Perl với các ngôn ngữ lập trình bổ sung thay vì viết lại mã hiện có.

          ![perl](https://user-images.githubusercontent.com/35051952/34914292-64c27412-f942-11e7-93af-ed9abafecd59.png)


   + Perl là ngôn ngữ thông dụng trong lĩnh vực quản trị hệ thống và xử lí các trang Web do có các ưu điểm sau: 
    - Nó là công cụ thao tác văn bản rất mạnh. Bạn có thể đưa vào một chuỗi văn bản dài và nhanh chóng tách nó ra thành các trường, dữ liệu. Đó chính là các thông tin sẽ được xử lý và lưu giữ.
    - Perl là ngôn ngữ có thể chạy trên nhiều hệ điều hành. Một mã kịch bản viết cho Windows có thể chạy trên hệ điều hành Unix hoặc Mac mà không hoặc chỉ cần điều chỉnh đôi chút. Perl nổi danh là một ngôn ngữ tuyệt vời – thực sự là như vậy! Các nhà lập trình Perl thường nói rằng họ có thể làm được rất nhiều việc chỉ với một dòng lệnh, theo một số cách khác nhau.
    - Thao tác với chuỗi kí tự rất tốt 
    - Đã có một thư viện mã lệnh lớn do cộng đồng sử dụng Perl đóng góp (CPAN). 
    - Cú pháp lệnh của Perl khá giống với C, từ các kí hiệu đến tên các hàm, do đó, nhiều người (đã có kinh nghiệm với C) thấy Perl dễ học.
    - Perl khá linh hoạt và cho phép người sử dụng giải quyết với cùng một vấn đề được đặt ra theo nhiều cách khác nhau. 
   ###  3.4 PHP
   PHP là ngôn ngữ kịch bản máy chủ (server-side) được sử dụng trên Internet ngày nay — nó chạy trên 75% của tất cả các máy chủ Web — và là sức mạnh phía sau của các nền tảng như WordPress, Wikipedia, và thậm chí là một phần của Facebook.
   PHP là ngôn ngữ lập trình sử dụng mã nguồn mở. Điều này có nghĩa là bạn có thể sử dụng PHP hoàn toàn miễn phí cho việc thực hiện website của mình. Ngôn ngữ PHP có thể chạy được trên nhiều nền tảng hệ điều hành khác nhau như Windows, Mac OS và Linux. 
   Ngôn ngữ lập trình PHP có thể được sử dụng trên nhiều hệ điều hành khác nhau bao gồm Windows, Mac OS và Linux (Ubuntu, Linux Mint…). Hiện nay, PHP đang là một trong những ngôn ngữ phổ biến hàng đầu được dùng trong lập trình web.
     
         ![php](https://user-images.githubusercontent.com/35051952/34914960-b7111554-f94f-11e7-8eed-2e1685f4c74c.PNG)


   + PHP là một ngôn ngữ lập trình web rất được ưa chuộng, hiện là ngôn ngữ lập trình web phổ biến nhất. Nhờ vào một số đặc điểm sau:
       - PHP hoạt động với tốc độ rất nhanh và hiệu quả. Một server bình thường có thể đáp ứng được hàng triệu truy cập / ngày.
       - PHP dễ học và linh động
       - Rất nhiều hàm hỗ trợ và nhiều phần mở rộng phong phú. PHP cung cấp một hệ thống dữ liệu phong phú. Do từ đầu, PHP được xây dựng để xây dựng và phát triển các ứng dụng trên web nên nó cung cấp rất nhiều hàm xây dựng sẵn giúp dễ dàng thực hiện các công việc như: Gửi, nhận mail, làm việc với Cookie…
       - Đặc biệt mã nguồn mở, thường xuyên nâng cấp, chạy được trên nhiều máy chủ web, nhiều hệ điều hành (đa nền tảng)
       - Cộng đồng sử dụng và hỗ trợ đông đảo 
       - Ngoài phần code chính (thường gọi là code thuần), các phần mở rộng cũng rất phong phú mà lại miễn phí như nhiều frame work, nhiều CMS
       - Các mã nguồn chia sẻ trên mạng tìm được rất nhiều và dễ dàng
       - Được tích hợp và sử dụng ổn định trong một mô hình LAMP = Linux+Apache+Mysql+Php, mã nguồn mở, chi phí thấp.
       - Các hosting hỗ trợ nhiều
 
   ###  3.5 Python
   Python là một ngôn ngữ lập trình thông dịch do Guido van Rossum tạo ra năm 1990. Python hoàn toàn tạo kiểu động và dùng cơ chế cấp phát bộ nhớ tự động; do vậy nó tương tự như Perl, Ruby, Scheme, Smalltalk, và Tcl. Python được phát triển trong một dự án mã mở, do tổ chức phi lợi nhuận Python Software Foundation quản lý.
     + Đặc điểm chính của python:
       - Dễ dàng để sử dụng: Python là một ngôn ngữ lập trình bậc cao rất dễ dàng sử dụng và là ngôn ngữ thân thiện với lập trình viên vì cấu trúc đơn giản, cú pháp định nghĩa rõ ràng và hơn hết là lượng từ khóa của python ít hơn.
       - Đọc code khá dễ dàng: Phần code của Python được định nghĩa khá rõ ràng và rành mạch.
       - Thư viện chuẩn khá rộng lớn: Thư viện rộng nên Python tương thích được với UNIX, Windows, và Macintosh.
       - Một ngôn ngữ thông dịch: Ngôn ngữ giúp cho quá trình debug dễ hơn vì là trình thông dịch thực thi code theo từng dòng. Chính vì vậy mà Python ngôn ngữ thu hút và được lựa chọn của rất nhiều lập trình viên.
       - Là một ngôn ngữ lập trình hướng đối tượng: Python còn hỗ trợ các phương thức lập trình theo hàm và theo cấu trúc.
       - Python còn được biết đến là nơi có kho dữ liệu khá lớn cung cấp cho toàn bộ các CSDL thương mại lớn.
       - Điều đặc biệt, ngôn ngữ Python còn có tốc độ xử lý nhanh hơn hẳn so với ngôn ngữ PHP.
       -  Python còn được biên dịch và chạy trên tất cả các nền tảng lớn nhất hiện nay.
       -  Python có Gui programming giúp cho việc thực hiện ảnh minh họa di động một cách tự nhiên và sống động hơn.
         
           ![python](https://user-images.githubusercontent.com/35051952/34914698-70c37812-f94a-11e7-8d15-ed4a4b4c78b0.PNG)

   
   ###  3.6 Ruby
   Ruby là ngôn ngữ lập trình kịch bản bởi mã lệnh của Ruby có thể chạy trực tiếp bởi máy tính mà không cần phải biên soạn thành một tệp thực thi tệp tin .exe trên Windows hay tệp tin binary trên Linux. Ruby, và framework phát triển ứng dụng web của nó là Ruby On Rails, là nguồn sức mạnh cho một số trang web lớn như là Groupon, Shopify (một nền tảng thương mại điện tử), và được dùng để xây dựng front-end cho mạng xã hội Twitter.
  Nó là một ngôn ngữ hoàn toàn hướng đối tượng và được thông dịch bởi server trước khi gửi mã HTML tới trình duyệt của người dùng — cũng giống như PHP (nhưng cũng có nhiều điểm hoàn toàn khác biệt). Tuy nhiên, nó có một số đặc điểm nổi trội đó là phát triển ứng dụng nhanh chóng, viết ít code bị lặp lại, và tốc độ thực thi khá nhanh.
    + Ưu điểm của Ruby
      - Mã nguồn mở
      - Hoạt động trên nhiều nền tảng
      - Có thể nhúng vào HTML
      - Ngôn ngữ cấp cao
      - Cung cấp các phương pháp đóng gói dữ liệu trong các đối tượng
      - OOP tinh khiết (Lập trình hướng đối tượng)
      - Kỹ thuật chuỗi và văn bản thao tác siêu tiên tiến
      - Có thể dễ dàng kết nối với DB2, MySQL, Oracle, và Sybase
      - Các chương trình lớn và mở rộng cao dễ dàng được bảo trì
      - Có một cú pháp sạch sẽ và dễ dàng cho phép các nhà phát triển mới để tìm hiểu Ruby rất nhanh chóng và dễ dàng
      - Có khả năng viết các ứng dụng đa luồng với một API đơn giản
      - Cung cấp lớp màn tiên tiến
      - Có thể viết thư viện bên ngoài Ruby hoặc C
      - Tính năng bảo mật tốt hơn
      - Nó có một trình gỡ lỗi
      - Cú pháp linh hoạt
      - Chuỗi xử lý mạnh mẽ

  ###  3.7 Node.js
   Node.js là 1 nền tảng chạy trên môi trường V8 Javascript runtime. Node.js cho phép lập trình viên xây dựng các ứng dụng có tính mở rộng cao sử dụng Javascript trên server.
  Và vì được porting từ C nên về mặt tốc độ xử lý thì rất nhanh.Node.js cho phép các nhà phát triển ứng dụng chỉ cần sử dụng Javascript để lập trình cho cả client side và server side, đưa Javascript từ một ngôn ngữ thuần client side có thể thực hiện các công việc phía sever mà trước đây phải do PHP, Ruby in Rails, Perl,... thực hiện.
    + Dưới đây là những lý do mà bạn không nên bỏ qua nền tảng này.
       - Đặc điểm nổi bật của Node.js là nó nhận và xử lý nhiều kết nối chỉ với một single-thread. Điều này giúp hệ thống tốn ít RAM nhất và chạy nhanh nhất khi không phải tạo thread mới cho mỗi truy vấn giống PHP. Ngoài ra, tận dụng ưu điểm non-blocking I/O của Javascript mà Node.js tận dụng tối đa tài nguyên của server mà không tạo ra độ trễ như PHP
       - Với cơ chế event-driven, non-blocking I/O(Input/Output) và mô hình kết hợp với Javascript là sự lựa chọn tuyệt vời cho các dịch vụ Webs làm bằng JSON.
       - Nếu bạn định viết 1 ứng dụng thể hiện trên 1 trang (Gmail?) NodeJS rất phù hợp để làm. Với khả năng xử lý nhiều Request/s đồng thời thời gian phản hồi nhanh. Các ứng dụng bạn định viết không muốn nó tải lại trang, gồm rất nhiều request từ người dùng cần sự hoạt động nhanh để thể hiện sự chuyên nghiệp thì NodeJS sẽ là sự lựa chọn của bạn.
       - NodeJS sẽ tận dụng tối đa Unix để hoạt động. Tức là NodeJS có thể xử lý hàng nghìn Process và trả ra 1 luồng khiến cho hiệu xuất hoạt động đạt mức tối đa nhất và tuyệt vời nhất.
       - Các web thông thường gửi HTTP request và nhận phản hồi lại (Luồng dữ liệu). Giả xử sẽ cần xử lý 1 luồng giữ liệu cực lớn, NodeJS sẽ xây dựng các Proxy phân vùng các luồng dữ liệu để đảm bảo tối đa hoạt động cho các luồng dữ liệu khác.Điều này giúp hệ thống tốn ít RAM nhất và chạy nhanh nhất khi không phải tạo thread mới cho mỗi truy vấn giống PHP. Cùng xem mô hình dưới đây để hiểu tại sao Node.js được đánh giá cao hơn.

                             ![node](https://user-images.githubusercontent.com/35051952/34914927-1c290e8e-f94f-11e7-9f0c-cc2aa08cc5d7.png)
                                     So sánh cách nhận và xử lý các request giữa server truyền thống và Node.js
       - Với sự ra đời của các ứng dụng di động & HTML 5 nên Node.js rất hiệu quả khi xây dựng những ứng dụng thời gian thực (real-time applications) như ứng dụng chat, các dịch vụ mạng xã hội như Facebook, Twitter,…
 
            