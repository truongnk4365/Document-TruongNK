##I. Khái niệm
	VMware là 1 chương trình tạo máy ảo trên máy tính, nó giúp cho 1 máy tính có thể chạy song song nhiều hệ điều hành thay vì 1 hệ điều hành trên 1 máy như bình thường chúng ta vẫn hay dùng.
	
	Máy ảo là một loại máy không phải làm một máy vật lý nhưng sử dụng được như một máy vật lý. Việc sử dụng ảo hóa tạo cho người quản trị dễ dàng trong việc quản trị, bảo trì, back up hệ thống, làm tránh lãng phí tài nguyên máy tính vật lý.
	
	VMware là một công cụ được dùng để tạo máy ảo trong  máy vật lý, tài nguyên của máy vật lý càng lớn thì tạo được càng nhiều máy ảo trong nó. Có thể tạo được máy ảo window, linux, unix,... trong nó. Trong bài báo cáo này sẽ giới thiệu đến VMware Workstation.

##II. Lịch sử phát triển của VMware
	VMware là một công ty phần mềm lớn vốn thuộc tập đoàn EMC chuyên làm phần mềm tạo máy ảo cho các hệ thống máy tính tương thích chip x86 của Intel. Sản phẩm chính của công ty bao gồm phần mềm ảo hóa VMware Workstation cho máy tình để bàn và VMware ESX server, VMware GSX server cho máy chủ. Các phần mềm tạo máy ảo của VMware được coi là tốt nhất trên thế giới bởi nó hỗ trợ nhiều hệ điều hành khác nhau như GNU/Linux, Mac OS X và Microsoft Windows. Các phần mềm máy ảo khác như Virtual PC chỉ hoạt động trên hệ điều hành Microsoft Windows. Đặc biệt VMware là công ty hàng đầu cung cấp các giải pháp ảo hóa cho các trung tâm dữ liệu với các sản phẩm như: VMware vSphere, VMware vCloud, VMware Director,... Trong bài báo cáo này sẽ giới thiệu đến VMware Workstation. 
		
##III. Các loại của VMware.
	Có 3 loại Vmware:
		* vmware workstation
		* vmware server
		* vmware vsphere

	- Vmware work station và vmware server được dùng cho máy tính desktop, nó là 1 chương trình ứng dụng được phát triển trên nền tảng window hoặc linux. Giúp cho chúng ta tạo ra máy ảo một cách đơn giản. Công dụng là thử nghiệm PC hay tận dụng hiệu năng của PC để làm được nhiều việc khác.

	- Vmware vsphere là 1 nền tảng giúp ta tạo ra hạ tầng điện toán đám mây, nó gồm các bộ ảo hóa hay được sử dụng cho các doanh nghiệp, khác với vmware work station, vmware server thì vmware vsphere không được sử dụng trong các máy tính cá nhân mà nó được sự dụng để cài đặt trực tiếp trên các máy server (máy chủ).
	
##IV. Một số ứng dụng 
	Khi chúng ta chỉ có 1 chiếc máy tính mà có nhiều công việc nhiều thứ chúng ta phải cần rất nhiều máy tính để có thể hoàn thành, hoặc có những công việc bạn phải làm trên hệ điều hành Linux nhưng vẫn muốn dùng windows. Vậy thì Vmware giúp bạn việc đó. Cụ thể một số ứng dụng của Vmware:

	
	* Dùng thử 1 hệ điều hành khác, khác với hệ điều hành mình đang dùng
	* Có thể cùng lúc dùng rất nhiều loại hệ điều hành. Ví dụ như windows, ubuntu, linux …..
	* Sử dụng 1 phần mềm đòi hỏi phải có hệ điều hành cũ. Nhưng chúng ta thì không muốn cài lại hệ điều hành đang dùng
	* Chạy và sử dụng được nhiều phần mềm thiết kế riêng cho các hệ điều hành khác nhau
	* Test 1 phần mềm nào đó trên rất nhiều các hệ điều hành khác nhau…
	
##V. Lab
	Thực hành cài đặt CentOS 7 trên VMware Workstation.
	1. giao diện chính của VMware Workstation 12 pro.
	<img scr="https://imgur.com/B5ELv07">
	
	2. tạo máy ảo
	chọn "create new a virtual marchine". sau đó làm theo thứ tự trong hình.
	<img scr="https://imgur.com/Po1lTK6">
	<img scr="https://imgur.com/CJiv1Qt">
	<img scr="https://imgur.com/fb2uZ72">
	<img scr="https://imgur.com/FZXFggX">
	<img scr="https://imgur.com/B9AlsIe">
	<img scr="https://imgur.com/aDuu7nC">
	<img scr="https://imgur.com/HIilnu7">
	<img scr="https://imgur.com/DFaV8k5">
	<img scr="https://imgur.com/QkJfZhw">
	<img scr="https://imgur.com/6xeFYdX">
	<img scr="https://imgur.com/KrQL09t">
	<img scr="https://imgur.com/XSPS8YZ">
	<img scr="https://imgur.com/hTiWyzE">
	<img scr="https://imgur.com/lpKrIkZ">
	
	3. kết quả
	<img scr="https://imgur.com/BCGd8br">
	
