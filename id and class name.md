MỘT SỐ CÁCH ĐẶT TÊN ID VÀ CLASS
Cách đặt tên:
_ Tên không được quá dài. <= cực kỳ quan trọng.
_ Hạn chế dịch (Chỉ dịch khi chưa biết đó thuộc khu vực tên nào mà thôi).
_ Thường thì chỉ cần xác định rõ khu vực, ý muốn của designer là ta có thể đặt được tên cho phù hợp.
VD: nhìn vào biết khu vực mà design muốn đưa thông tin giới thiệu thì ta nên đặt các tên sau: introduce, info, information. Nếu giới thiệu về cty thì cần: aboutUs, company, …
_ Việc đặt tên này chẳng những có ý nghĩa cho từng khu vực, mà nó còn giúp cho người khác khi nhìn vào code sẽ dễ dàng hình dung đó là gì.

Common: 
#header
	#headerInner
		#description		Câu dẫn
		#logo			Logo
		#hNav			Header navigation
		.hBlock			Header Block
	.hSection		Header Section
		.hGroup		Header Group
	.language		Ngôn ngữ
	.changeSize		Thay đổi font-size		
	.search			search form
#gNav#gNavInner

#visual
	#visualInner
	.vNav
#pageBody
	#pageBodyInner
#content
	.topicPath
	.section
	.sectionInner
	.pageTop	Trở về đầu trang
	.topPage	Trở về trang top
	.pagerLink	Danh sách link số: <<Previous [1][2][3] Next >>
	.contact
	
	[Những tên sau có thể đặt ngang hàng hoặc bên trong section]
.block
	.group
	.general
	.element

	[Tên đặc trưng - tên trang]
	.info	 	Thông tin, giới thiệu
.information 	Thông tin, giới thiệu
.aboutUs	Giới thiệu
.company	Công ty
.history		Lịch sử
.recruit		Đào tạo
	.news 		Tin tức
	.faq 		Phần hỏi đáp
	.product 	Sản phầm
	.category 	Danh mục
	.shopping	Mua sắm
	.shop		Mua sắm
	.blog		Blog
	.sitemap	Sitemap

	[Tên đặc trưng - tên riêng từng nội dung]
.info	 	Thông tin, giới thiệu
.news 		Tin tức
.faq 		Phần hỏi đáp
	.product 	Sản phầm
	.category 	Danh mục
.social		Mạng xã hội
	.list		Danh sách bất kỳ - khi không có cách đặt khác
	.infoList	Danh sách về thông tin
	.linkList	Danh sách link
	.menu		Thực đơn
	.menuList	Danh sách thực đơn
	.priceList	Bảng giá
	.gallery		Khu vực ảnh - dành cho trình diễn gallery
.thumnail	Danh sách hình
.imageList	Danh sách hình
.movie		Khu vực movie, youtube..
.movieList	Danh sách movie
.map		Bản đồ
	.item 		Mục
	.itemList	Danh sách các mục
	.step		Các bước
	.stepList	Danh sách các bước
	.noteList	Danh sách text ghi chú
.comment	Bình luận
.calendar	Lịch
.guide		Hướng dẫn
.article		Bài viết
.comment	Bình luận

	[Tên đặc trưng - chi tiết nhỏ]
	.last		Thành phần cuối - phục hồi style
.lastList	Thành phần cuối danh sách - phục hồi style
.photo		Ảnh chụp
.detail		Chi tiết - dành cho link
.more		Xem thêm - dành cho link
.backnumber	Link back number
	.price		Giá tiền
	.qrcode	Mã QR Code
	.important	Text ghi chú màu đỏ
	.note		Text ghi chú
	.require	Text ghi chú màu đỏ - thường có trong form
	.size0x		Dành cho width hoặc font-size
	.date		Ngày tháng
	.time		Thời gian
	.mail		Địa chỉ mail
	.phone		Số điện thoại

	[Tên đặc trưng - kết hợp js]
	.tabList		Nội dung sử dụng tab
	.jcarousel	Slide sử dụng jcarousel
	.gallery		Khu vực ảnh - dành cho trình diễn gallery

	[hx]
	.bHead 	Big Head - Tiêu đề lớn nhất
	.mHead	Medium Head - Tiêu đề trung bình
	.sHead		Small Head - Tiêu đề nhỏ
	.ssHead	Sub Small Head - Tiêu đề con
#sidebar
	#lNav
	.banner
	(Có thể sử dụng thêm tên bên phần content.)
#footer
	#footerInner
	#fNav
	.fLogo
		.fBlock
	.fSection
		.fGroup
		#copyright
Một số tên common thông dụng khác
	#main
	#wrap
	#wrapper

[Tên dành cho form]
.mail			Form mail
.mailForm		Form mail
.contact		Form liên hệ
.contactForm		Form liên hệ
.search		Form tìm kiếm
.searchForm		Form tìm kiếm
.login			Form đăng nhập
.loginForm		Form đăng nhập
.logout			Phần đăng xuất
.logoutForm		Phần đăng xuất
.signIn			Form đăng nhập
.signInForm		Form đăng nhập
.signOut		Phần đăng xuất
.signOutForm		Phần đăng xuất
.signUp		Form đăng ký
.signUpForm		Form đăng ký
.order			Form đặt hàng
.orderForm		Form đặt hàng
.shopping		Form mua bán
.onlineShop		Form mua bán

[Tên dành cho table]
Khi đặt tên cho table, cần xác định table đó hiển thị thông tin gì, nội dung về cái gì, khi đó sử dụng tên cho chính xác:
	.tableInfo		Sử dụng cho nội dung chung chung không rõ nghĩa

Những tên cần tránh:
Không nên đặt tên trùng với tag HTML hay thuộc tính trong CSS.
[Tên này dễ nhầm lẫn với tag html hay thuộc tính css]
.text
.image
.button
.color
.height
.width
.link
.title
.style
.table
.form
=>Tương tự cho ID
Nếu muốn sử dụng những tên trên thì cần viết kết hợp với tên chính, ví dụ .info:
.text         =>	.textInfo
.image     =>	.imageInfo
.button     =>	.buttonInfo
...

[Tên về màu sắc]
.red
.blue
…

[Tên về vị trí]
.left
.right
… 
Muốn sử dụng thì nên viết kết hợp với tên chính:
	.left 	   => 	.hLeft
	.left 	   => 	.blockLeft

[Tên riêng - tiếng Nhật]
.takeshi
.yokohama
…
[Tên viết tắt]
.txt
.img
.bnr
.btn
.bg
Muốn sử dụng thì nên viết kết hợp với tên chính:
.txtList	   =>	.textList
.imgList  => 	.imageList
