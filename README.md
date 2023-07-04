# CongNghePhanMemHDT
Báo cáo môn công nghệ phần mềm hướng đối tượng  
Dưới đây là mô tả ngắn gọn về mỗi phần:  

Các vai trò: Admin, User, Phóng viên và Biên tập viên.  
Trạng thái bài báo: Đã được duyệt và chờ xuất bản (101), Đã xuất bản (102), Bị từ chối (103) và Chưa được duyệt (104).  
TagIndex: Một tag định danh cho trang chủ (TagHome).  
Gmail: Để lấy authentication-token, cần sử dụng refersh-token. Sau khi gửi code lên, sẽ nhận được authentication-token và có thể sử dụng để lấy dữ liệu.  
Upload: Để lấy tên file, cần tách chuỗi từ contentDisposition và bỏ qua hai kí tự đầu tiên để lấy tên.  
Thư viện html2pdf được sử dụng để tạo file PDF từ HTML.  
Thư viện tinymce được sử dụng để tạo nội dung HTML, có các tính năng như đính kèm ảnh, link, bảng, media.  
Thư viện datetimepicker được sử dụng để tạo picker cho ngày giờ.  
Các file Tag lưu trữ các đoạn link, script và fragment của trang JSP để phối hợp với các trang JSP khác thành một trang web hoàn chỉnh.  
Sử dụng Bootstrap 4, entity_encoding là "raw", selector là '#txtContent', height là 450, plugins bao gồm paste image link autolink lists table media, không có menubar, toolbar bao gồm undo redo, bold italic underline strikethrough, numlist bullist, alignleft aligncenter alignright, forecolor backcolor, table link image media.  
