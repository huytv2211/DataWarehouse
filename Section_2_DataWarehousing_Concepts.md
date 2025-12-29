2.1 Data Warehouse Concaepts

2.2 Why we need to build Data Warehouse
    Making data-driven decisions
    One-stop shopping

2.2.1 Making data-driven decisions 
(Ra quyết định dựa trên dữ liệu) là phương pháp đưa ra quyết định kinh doanh dựa trên việc phân tích dữ liệu thực tế và số liệu thay vì dựa vào trực giác, 
kinh nghiệm cá nhân hay phỏng đoán. Quá trình này bao gồm việc thu thập, xử lý và diễn giải dữ liệu từ nhiều nguồn khác nhau (như hành vi khách hàng, doanh thu)
để tạo ra thông tin chi tiết, giúp các nhà lãnh đạo đưa ra quyết định chính xác, hiệu quả hơn, giảm thiểu rủi ro và tối ưu hóa hiệu suất. 
Các yếu tố chính
Dựa trên dữ liệu, không phải cảm tính: Sử dụng bằng chứng cụ thể, số liệu thay vì suy đoán chủ quan.
Thu thập và phân tích: Thu thập dữ liệu từ các nguồn đa dạng (KPIs, hành vi người dùng, doanh số) and sử dụng các công cụ để phân tích.
Tạo thông tin chi tiết: Biến dữ liệu thô thành những hiểu biết sâu sắc (insights) để hỗ trợ quyết định chiến lược và vận hành.
Cân bằng kinh nghiệm và dữ liệu: Dữ liệu là nền tảng, nhưng kinh nghiệm chuyên môn vẫn cần thiết để đưa ra quyết định linh hoạt, phù hợp với ngữ cảnh. 
Ví dụ
Một công ty truyền thông xã hội dùng dữ liệu về các nội dung người dùng tương tác để cá nhân hóa nội dung và quảng cáo hiển thị, theo một bài viết trên oes.vn.
Dùng dữ liệu doanh thu để quyết định mở chi nhánh mới ở đâu, theo một bài viết từ MindX. 
Lợi ích
Nâng cao tính chính xác và giảm thiểu rủi ro trong các quyết định.
Tối ưu hóa hiệu suất và dự đoán xu hướng tương lai.
Tăng cường khả năng cạnh tranh và thích ứng trong môi trường kinh doanh hiện đại. 

2.2.2 One-stop shopping (mua sắm một điểm đến) 
là mô hình kinh doanh mà một địa điểm hoặc tổ chức cung cấp đa dạng sản phẩm, dịch vụ (từ mua sắm, ăn uống, giải trí đến dịch vụ khác) tại cùng một nơi, 
giúp khách hàng đáp ứng mọi nhu cầu chỉ trong một lần ghé thăm, tiết kiệm thời gian và công sức, ví dụ điển hình là các đại siêu trung tâm thương mại (TTTM) lớn như Vincom, Aeon Mall. 
Đặc điểm chính:
Tính đa dạng (Variety): Cung cấp nhiều loại hàng hóa, dịch vụ trong cùng một khu vực (quần áo, thực phẩm, siêu thị, rạp phim, khu vui chơi, nhà hàng, ngân hàng,...).
Tiện lợi (Convenience): Khách hàng có thể hoàn thành nhiều việc cùng lúc, không cần di chuyển đến nhiều địa điểm khác nhau.
Tập trung (Focus): Có thể tập trung vào một ngành hàng lớn (ví dụ: một siêu thị nội thất lớn) hoặc toàn diện các ngành hàng khác nhau. 
Ví dụ ở Việt Nam:
Các trung tâm thương mại lớn như Vincom, Takashimaya, Aeon Mall, Lotte Mart hoạt động theo mô hình này. 
Lợi ích cho khách hàng:
Tiết kiệm thời gian: Chỉ cần đến một chỗ là có đủ mọi thứ.
Tiết kiệm chi phí di chuyển: Không cần đi lại nhiều lần.
Trải nghiệm toàn diện: Thỏa mãn nhu cầu mua sắm, giải trí cho cả gia đình (trẻ em, người lớn).
2.3 Data Lake
*Data Lake (Hồ dữ liệu) là một kho lưu trữ tập trung, có khả năng mở rộng cao, dùng để chứa dữ liệu thô, đa dạng về cấu trúc (có cấu trúc, bán cấu trúc, phi cấu trúc) 
từ nhiều nguồn khác nhau, lưu ở dạng nguyên bản mà không cần xử lý hay định dạng trước, cho phép phân tích và khai thác dữ liệu linh hoạt cho nhiều mục đích sử dụng sau này bằng các công cụ và ngôn ngữ khác nhau. 
Đặc điểm chính
Lưu trữ dữ liệu thô: Dữ liệu được nạp vào Data Lake ở dạng nguyên thủy (raw data) và được lưu trữ cho đến khi có nhu cầu sử dụng cụ thể.
Hỗ trợ đa dạng định dạng: Chứa cả dữ liệu có cấu trúc (structured), bán cấu trúc (semi-structured) và phi cấu trúc (unstructured) như văn bản, hình ảnh, video, log....
Khả năng mở rộng: Có thể lưu trữ khối lượng dữ liệu lớn (Big Data) mà không bị giới hạn về kích thước hay định dạng.
Linh hoạt: Cho phép người dùng truy cập và phân tích dữ liệu bằng nhiều công cụ và ngôn ngữ (SQL, Python, R, Machine Learning) khi cần thiết, thay vì phải định nghĩa cấu trúc trước như Data Warehouse.
Nguồn cấp dữ liệu phong phú: Thu thập dữ liệu từ nhiều nguồn khác nhau như hệ thống vật lý, đám mây, thiết bị biên (edge computing). 
Lợi ích
Tăng cường phân tích: Cung cấp nguồn dữ liệu dồi dào cho các phân tích chuyên sâu, dự báo và học máy.
Tiết kiệm chi phí: Lưu trữ dữ liệu thô ban đầu thường rẻ hơn so với việc xử lý trước và lưu trữ trong kho dữ liệu truyền thống.
Độ tin cậy cao: Tập trung tất cả dữ liệu vào một nơi an toàn, đáng tin cậy. 
So sánh nhanh với Data Warehouse
Data Lake: Lưu trữ dữ liệu thô với mục đích sử dụng chưa xác định, linh hoạt, lưu mọi loại dữ liệu.
Data Warehouse: Lưu trữ dữ liệu có cấu trúc, đã qua xử lý, làm sạch, tổ chức rõ ràng cho các mục đích báo cáo chiến lược. 

