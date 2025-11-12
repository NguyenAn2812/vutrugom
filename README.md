# 🌟 Tóm tắt Kế hoạch Kỹ thuật Website Ngọc Thọ Viên

**Mục tiêu:** Phác thảo rõ ràng các Tính năng Cốt lõi, Cơ sở dữ liệu (Yêu cầu GIS) và Sơ đồ Trang web cần thiết cho nhóm phát triển.

## 1. Tính năng Cốt lõi

Dự án tập trung vào việc tích hợp nội dung số, thương mại điện tử và công nghệ AI/GIS tiên tiến.

### A. Tính năng AI và Kiến thức Số

* **Công cụ Nhận dạng Gốm sứ (CV - Quét):** Cho phép người dùng tải lên hoặc chụp ảnh các sản phẩm gốm sứ. Hệ thống Thị giác Máy tính (CV) phân tích hình ảnh và trả về thông tin chi tiết về Loại/Tên gốm sứ, Nguồn gốc (làng nghề), Đặc điểm Men/Vật liệu và Giá trị Tham chiếu [trích dẫn: 108, 109, 110].
* **Bộ Giải mã Biểu tượng:** Phân tích các hoa văn, màu men, hình dạng và triết lý văn hóa của gốm sứ, tích hợp AI để nhận dạng hình ảnh nhằm tra cứu nguồn gốc và ý nghĩa biểu tượng của các họa tiết [trích dẫn: 32, 86].
* **Chatbot AI (Trợ lý Kiến thức Kỹ thuật số) 24/7:** Hỗ trợ hỏi đáp, tra cứu và thuyết minh tự động về lịch sử, kỹ thuật, biểu tượng và các khía cạnh du lịch của gốm sứ Việt Nam [trích dẫn: 87].

### B. Bản đồ Kỹ thuật số và Tính năng Thông tin

* **Bản đồ "Hành trình Gốm sứ Việt Nam" (GIS):** Hiển thị vị trí chính xác (Hệ thống Thông tin Địa lý) của các làng nghề trên toàn quốc (ví dụ: Bát Tràng, Phù Lãng, Biên Hòa) dưới dạng bản đồ tương tác [trích dẫn: 94, 95, 96].
* **Thư viện Đa phương tiện:** Tổng hợp hình ảnh 360 độ, video về quy trình làm gốm và các bài viết chuyên sâu về bảo tồn giá trị gốm sứ truyền thống [trích dẫn: 111, 112].

### C. Tính năng Thương mại Điện tử & Cộng đồng

* **Chợ Thương mại Điện tử:** Cho phép nhà sản xuất/nghệ nhân niêm yết và bán sản phẩm gốm sứ trực tuyến, phân loại theo làng nghề và chất liệu. Hỗ trợ thanh toán và vận chuyển an toàn [trích dẫn: 98, 99, 100, 101].
* **Diễn đàn Gốm sứ:** Một không gian trực tuyến để tương tác, học tập, tổ chức hội thảo và triển lãm ảo giữa các nghệ nhân, sinh viên và những người đam mê [trích dẫn: 86].

## 2. Yêu cầu Cơ sở dữ liệu (Tập trung vào Hệ thống GIS)

Cơ sở dữ liệu phải xử lý cả dữ liệu địa lý truyền thống và phức tạp để hỗ trợ các tính năng cốt lõi.

* **Các Loại Dữ liệu Yêu cầu:**
* **Dữ liệu Địa lý (GIS):** Vị trí chính xác (Tọa độ) của các làng nghề, điểm du lịch và địa chỉ sản xuất để hiển thị trên Bản đồ GIS [trích dẫn: 53].
* **Dữ liệu Kiến thức Số:** Thông tin lịch sử, kỹ thuật, ký hiệu, triết lý văn hóa và dữ liệu đào tạo cho các mô hình AI/CV.
* **Dữ liệu Thương mại Điện tử/Sản phẩm:** Thông tin chi tiết về sản phẩm, phân loại, giá cả, hàng tồn kho, đơn đặt hàng, thanh toán và chi tiết vận chuyển.
* **Dữ liệu Người dùng/Cộng đồng:** Thông tin tài khoản, bài đăng trên diễn đàn, bình luận và dữ liệu tùy chọn (cho các đề xuất AI).
* **Dữ liệu đa phương tiện:** Siêu dữ liệu lưu trữ và đường dẫn cho hình ảnh, video 360 độ và mô hình 3D.
* **Công nghệ được đề xuất:** **PostgreSQL với phần mở rộng PostGIS** (Được đề xuất để xử lý dữ liệu địa lý và không gian).

## 3. Sơ đồ trang web (Các trang bắt buộc)

Dựa trên cấu trúc và tính năng của nền tảng, trang web yêu cầu các trang sau:

| Tên trang (Tiếng Anh/Tiếng Việt) | Loại trang | Chức năng chính |
| :--- | :--- | :--- |
| **Trang chủ** (Trang chủ) | Tĩnh | Điểm vào, giới thiệu chung, CTA nổi bật. |
| **Gốm Di sản** (Gốm Di sản) | Nội dung/Thư viện | Giới thiệu về lịch sử, các dòng gốm, thư viện số và mô hình 3D[trích dẫn: 86]. |
| **Giải Mã Biểu Tượng** (Giải Mã Biểu Tượng) | Tương tác AI | Công cụ tải ảnh (CV Scan) và tra cứu ý nghĩa/nguồn gốc họa tiết[trích dẫn: 86, 107]. |
| **Hành trình Gốm Việt** | Bản đồ (GIS) | Bản đồ tương tác hiển thị các làng nghề và địa chỉ khách tham quan[trích dẫn: 87, 94]. |
| **Nghệ nhân & Kỹ thuật** | Danh sách/Chi tiết | Hồ sơ nghệ nhân, mô phỏng quy trình sản xuất và chia sẻ bí quyết thủ công[trích dẫn: 86]. |
| **Diễn đàn Gốm** | Cộng đồng | Không gian thảo luận, trao đổi và tổ chức hội thảo/triển lãm trực tuyến[trích dẫn: 86]. |
| **Sàn Thương mại** | Thương mại điện tử | Danh sách sản phẩm, trang sản phẩm chi tiết, phân loại theo làng nghề/nguyên liệu[trích dẫn: 98, 99, 100]. |
| **Giỏ hàng & Thanh toán** | Thương mại điện tử | Quy trình mua hàng, thanh toán và vận chuyển [trích dẫn: 101]. |
| **Liên Hệ/Về Chúng Tôi** (Liên Hệ/Về Chúng Tôi) | Tĩnh | Thông tin liên hệ, tầm nhìn và sứ mệnh của Ngọc Thọ Viên. |

---

**Bước tiếp theo:** Các yêu cầu đã rõ ràng. Bạn có muốn tôi hỗ trợ **soạn thảo ma trận phân công vai trò cụ thể** cho các thành viên trong nhóm (ví dụ: phân công nhiệm vụ AI, GIS và Thương mại điện tử cho các nhà phát triển cụ thể) không?
