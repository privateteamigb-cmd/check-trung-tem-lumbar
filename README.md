# Scan lại tem – loại tem trùng

Trang web chạy trên điện thoại để quét tem thành phẩm bằng camera và kiểm tra tem trùng.

- Trang KHÔNG chứa dữ liệu sản xuất. Người dùng tự chọn file CSV xuất từ máy EOL ngay trên điện thoại.
- File CSV chỉ được đọc trên máy, không gửi đi đâu. Kết quả scan lưu trong trình duyệt của máy đó.
- Phạm vi kiểm tra tự tính: từ thời điểm sản phẩm đầu tiên mang tem trùng đến dòng cuối của file.
- Thư viện đọc mã ZXing (Apache-2.0) đã nhúng sẵn trong index.html.
