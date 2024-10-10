Giải thích mã:
create_folder(): Hàm này kiểm tra và tạo thư mục nếu chưa tồn tại.
download_image(): Tải ảnh từ URL và lưu vào thư mục đã chỉ định.
get_image_urls(): Hàm này lấy danh sách URL của các ảnh trên trang web bằng cách sử dụng BeautifulSoup.
websites[]: Danh sách các trang web bạn muốn lấy ảnh từ đó.
Chương trình sẽ duyệt qua từng trang web, lấy URL của các ảnh và tải chúng về thư mục A.
Lưu ý:
Bạn cần thay thế URL trong danh sách websites bằng các URL thật chứa ảnh.
Đoạn mã trên có thể không tải được ảnh nếu trang web có biện pháp bảo mật hoặc cần xác thực.
