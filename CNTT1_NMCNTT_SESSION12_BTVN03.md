
# **Phần 1. Phân tích:** 
1. Tham số 1 ```lookup_value``` : mã vận đơn trên kiện hàng 
2. Tham số 2 ```table_array``` : bảng giá gốc đặt ở phòng kế toán 
3. Tham số 3 ```col_index_num``` : số thứ tự cột giá cước 
4. Tham số 4 ```range_lookup``` : FALSE 
# **Phần 2. Triển khai:**
- **Heading 1:** Tiêu đề chính của tài liệu
- **Heading 2:** Các mục quy trình nhỏ
- không dùng **Merge Cell** trong vùng dữ liệu bảng chính và bảng giá
- Font chữ đồng bộ
- cố định vùng dữ liệu cần tìm kiếm 
- mỗi dòng là một bản ghi đơn hàng duy nhất
# **Phần 3. Kiểm thử:**
- sử lí lỗi #N/A : Bọc hàm VLOOKUP bên trong hàm **`IFERROR`** kết hợp hàm **`TRIM`** để tự động làm sạch ký tự thừa, khoảng trắng và thông báo lỗi thân thiện
