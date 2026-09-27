# NHẬT KÝ TƯƠNG TÁC AI - NGHIÊN CỨU KIẾN TRÚC CLUSTERED & SECONDARY INDEX

- **Prompt 1 (Khái niệm Index vật lý):** "Hãy phân biệt cơ chế lưu trữ dữ liệu giữa Clustered Index (Chỉ mục cụm) và Secondary Index (Chỉ mục phụ) trong công cụ lưu trữ InnoDB của MySQL. Khi thực hiện một câu lệnh tìm kiếm không trúng Covering Index, quá trình Lookup Table/Key Lookup diễn ra ở tầng đĩa cứng như thế nào?"
- **Prompt 2 (Khái niệm Write Penalty):** "Giải thích chi tiết thuật ngữ 'Write Penalty' (Hình phạt khi Ghi) của chỉ mục Index. Tại sao khi ta chèn thêm dù chỉ một cột vào cấu trúc của Secondary Index lại khiến quá trình thực thi lệnh INSERT/UPDATE của hệ thống bị chậm đi đáng kể?"
- **Prompt 3 (Tính toán dung lượng byte dữ liệu):** "Hướng dẫn tôi cách tính toán dung lượng bộ nhớ vật lý chính xác bằng đơn vị Byte của các kiểu dữ liệu thông dụng trong MySQL bao gồm TINYINT, INT, BIGINT, DATETIME, TIMESTAMP và cấu trúc chuỗi linh hoạt VARCHAR(N) dưới bảng mã cấu hình utf8mb4."
