<h1>MÔN PHÁT TRIỂN PHẦN MỀM NGUỒN MỞ (4305)</h1>
<h1>Tên đề tài : Xây dựng ứng dụng chat Online(Python) </h1>
<h2>Thành viên:</h2>
	<br>1.Nguyễn Đình Thái (Nhóm Trưởng)
	https://www.facebook.com/chickns0up
	<br>2.Trịnh Văn Bình
	https://www.facebook.com/trinh.binh.969


<h2>Phần 1: Mục tiêu Đề tài</h2>	
		<br>Tạo ra chương trình chat nhóm giữa các thành viên với nhau, triển khai theo mô hình server & client
		<br>Có thể trao đổi thông tin giữa các client qua khoảng cách địa lý lớn, 
		<br>Bảo mật thông tin cho client
		<br>trên tiêu chí nhỏ gọn, dễ sử dụng.

<h2>Phần 2: Hướng phát triển trong tương lai:</h2>
		<br>Đảm bảo bảo mật thông tin cho các client
		<br>Cho phép triển khai nhiều kênh
		<br>Hỗ trợ số lượng lớn client chat cũng lúc
		<br>Giao diện trực quan
	
<h2>Phần 3: Chuẩn lập trình:</h2>
	Triển khai theo mô hình 2 lớp
	Presentation Layers
	Lớp này làm nhiệm vụ giao tiếp với người dùng cuối để thu thập dữ liệu và hiển thị kết quả/dữ liệu thông qua các thành phần trong giao diện người sử dụng.

	Business Logic Layer

	Đây là layer xử lý chính các dữ liệu trước khi được đưa lên hiển thị trên màn hình hoặc xử lý các dữ liệu.
	Đây là nơi đê kiểm tra ràng buộc, các yêu cầu nghiệp vụ, tính toán, xử lý các yêu cầu và lựa chọn kết quả trả về cho Presentation Layers.

	Cách vận hành của mô hình

	Yêu cầu được xử lý tuần tự qua các layer như hình.
	- Đầu tiên User giao tiếp với Presentation Layers (GUI) để gửi đi thông tin và yêu cầu. Tại layer này, các thông tin sẽ được kiểm tra, nếu OK chúng sẽ được chuyển xuống Business Logic Layer (BLL).

	- Tại BLL, các thông tin sẽ được nhào nặn, tính toán theo đúng yêu cầu đã gửi, BLL sẽ gửi trả kết quả về GUI
<img src='/img/2_TIER.png'>


<h2>Phần 4: Hướng dẫn sử dụng:</h2>
Cú pháp chạy server:
python server.py

<img src='/img/hdsd_server.png'>

Cú pháp chạy client:

<p>python client.py [server] [cổng]

<img src='/img/hdsd_client.png'>


<h2>Phần 5: Sản Phẩm:</h2>
Hình ảnh các client đang chat
<img src='/img/chat.PNG'>

<br>Triển khai server dự phòng 
<br><img src='/img/server2.PNG'>

<h2><left>Sơ đồ nguyên lý hoạt động</h2>
<br><img src='/img/socket.jpg'></left>


<h2>Phần 6: Tài liệu cho người dùng cuối:</h2>
https://github.com/TCU1/ChatClientServer_Python/tree/master/Document
<h2>Phần 7: Tài liệu cho nhà phát triển:</h2>
https://github.com/TCU1/ChatClientServer_Python/tree/master/Document
<h2>Phần 8: Kênh trao đổi thông tin:</h2>


<h2>Phần 9: Thông tin giấy phép & tổ chức mã nguồn:</h2>
https://github.com/TCU1/ChatClientServer_Python/tree/master/Document

