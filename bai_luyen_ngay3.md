
#   Bài Làm – Ôn  Luyện Ngày  3


-   **Họ tên:** Hà Duy Mạnh 
-   **Lớp:** HN-KS26-CNTT1
-   **Link repository:** [https://github.com/adaptable14/-HN-KS26-CNTT1-_Nhap-mon-CNTT_OnTap-Ngay3](https://github.com/adaptable14/-HN-KS26-CNTT1-_Nhap-mon-CNTT_OnTap-Ngay3)
-   **Hệ điều hành (Windows/macOS):** Windows

## Bài 1.  [README.md]

-   Heading 1: tên dự án ✅
-   Ít nhất 2 heading cấp 2✅ 
-   Mô tả ngắn có cả **in đậm** và _in nghiêng_✅
-   Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu🔲
-   Danh sách đánh số ít nhất 3 bước✅
-   Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án🔲
-   Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành✅
-   Blockquote nhắc không upload `.env`✅

## Bài 2. Excel

-    d) **Số dòng còn hiển thị sau khi lọc là ** 7 dòng

-    e) 
1.  **Vì sao vùng tra cứu cần dấu `$`

  **Trả lời:** Dấu dùng để cố định hàng và cột (tạo **địa chỉ tuyệt đối**) cho vùng bảng tra cứu`$`. Điều này đảm bảo khi bạn kéo hoặc sao chép công thức VLOOKUP xuống các dòng bên dưới, vùng dữ liệu tham chiếu sẽ được giữ nguyên cố định, không bị dịch chuyển theo dòng`KhoaHoc!$A$2:$C$8`.
  
2.  **Nếu bỏ dấu `$` rồi kéo công thức xuống thì điều gì xảy ra?

-   **Trả lời:** Nếu bỏ dấu`$` thì vùng tra cứu sẽ chuyển thành địa chỉ tương đối và bị trượt xuống theo từng dòng (ví dụ ở dòng 3 sẽ thành , dòng 4 thành ,...)`$``A3:C9``A4:C10`. Hệ quả là phạm vi tra cứu sẽ bị lệch khỏi bảng dữ liệu gốc, khiến VLOOKUP không tìm thấy thông tin và bảng Excel sẽ trả về lỗi **`#N/A`** ở các dòng phía dưới.

## Tự chấm (điền sau khi có đáp án)

-   **Điểm tự chấm:** ..../100
-   **Lỗi mình đã mắc và cách sửa**
