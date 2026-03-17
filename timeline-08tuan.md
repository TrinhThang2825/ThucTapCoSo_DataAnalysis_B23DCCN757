# Thực tập Cơ sở – Kế hoạch & Tiến độ 08 Tuần

## 1. Thông tin sinh viên
* **Họ tên:** Trịnh Xuân Thắng
* **MSSV:** B23DCCN757
* **Lớp:** INT13187-20252-21
* **Email:** trinhxuanthang200805@gmail.com
* **GitHub username:** TrinhThang2825
* **Link repository:** https://github.com/TrinhThang2825/ThucTapCoSo_DataAnalysis_B23DCCN757

## 2. Định hướng & Mục tiêu
1. **Tôi muốn làm vai trò gì sau khi ra trường?**
    - Data Analyst (Chuyên viên phân tích dữ liệu).
2. **Kỹ năng tôi còn thiếu / yếu trong vai trò đó là gì?**
    - Kỹ thuật tiền xử lý dữ liệu thô (Data Wrangling) và Trực quan hóa dữ liệu (Data Visualization).
3. **Tôi có thể học và thực hành được kỹ năng đó trong 8 tuần không?**
    - Có, tập trung sâu vào thư viện Pandas (xử lý dữ liệu) và Matplotlib/Seaborn (vẽ biểu đồ).

## 3. Đăng ký chủ đề thực tập
* **Định hướng:** [x] Cải thiện / củng cố kỹ năng đang có (7–8)
* **1–2 kỹ năng chính muốn học / cải thiện:**
    1. **Python (Pandas):** Xử lý, làm sạch và thống kê dữ liệu.
    2. **Data Visualization:** Trực quan hóa kết quả phân tích bằng biểu đồ.
* **Bài toán / nội dung áp dụng cụ thể:** Phân tích dữ liệu giả lập thị trường Laptop 2026. Xây dựng luồng xử lý từ bước khởi tạo dữ liệu giả lập đến bước xuất báo cáo Insight về mối tương quan giữa cấu hình (RAM, Brand) và giá bán (Price).
* **Làm việc nhóm (nếu có):** Không.

---

## 4. Kế hoạch thực hiện 08 tuần

### Tuần 1 – Khởi động & Tìm hiểu nền tảng
* **Mục tiêu tuần:** Thiết lập môi trường và nắm vững cấu trúc Repo chuẩn.
* **Tìm hiểu / Đọc:**
    - [x] Cấu trúc dự án chuẩn và cách quản lý GitHub | roadmap.sh | Hoàn thành | Hiểu cách phân bổ thư mục data/docs/src.
    - [x] Markdown Guide cho GitHub | GitHub Docs | Hoàn thành | Biết cách trình bày bảng và tài liệu chuyên nghiệp.
* **Thực hành:**
    - [x] Khởi tạo Repo, thiết lập cấu trúc thư mục chuẩn theo yêu cầu của Giảng viên. | Khung thư mục dự án | [x] | Đã hoàn thành.

### Tuần 2 – Triển khai cơ bản (Buổi trao đổi 1)
* **Mục tiêu tuần:** Thực hiện khởi tạo dữ liệu giả lập (Synthetic Data).
* **Tìm hiểu / Đọc:**
    - [x] Thư viện Numpy và Pandas cơ bản | Pandas Official Docs | Hoàn thành | Biết cách tạo DataFrame và phát sinh số ngẫu nhiên.
    - [x] Khái niệm và ứng dụng Synthetic Data | Towards Data Science | Hoàn thành | Hiểu lợi ích của dữ liệu giả lập trong kiểm thử Pipeline.
* **Thực hành:**
    - [x] Viết script Python tạo 200 dòng dữ liệu Laptop (Brand, RAM, Price, Rating). | `data/laptop_data_2026.csv` | [x] | Dữ liệu sạch 100%.

### Tuần 3 – Mở rộng & Đào sâu
* **Mục tiêu tuần:** Thực hiện thống kê mô tả để hiểu sâu về dữ liệu.
* **Tìm hiểu / Đọc:**
    - [x] Các đại lượng thống kê: Mean, Median, Std | Statistics Handbook | Hoàn thành | Hiểu ý nghĩa của độ lệch chuẩn trong biến động giá.
    - [x] Kỹ thuật Groupby và Describe trong Pandas | Pandas API | Hoàn thành | Biết cách nhóm dữ liệu theo Thương hiệu (Brand).
* **Thực hành:**
    - [x] Tính toán giá trung bình theo Brand và phân khúc loại máy. | `docs/week03-research.md` | [x] | Đã có Insights sơ bộ về giá.

### Tuần 4 – Hoàn thiện giữa kỳ (Buổi trao đổi 2)
* **Mục tiêu tuần:** Trực quan hóa dữ liệu cơ bản bằng biểu đồ.
* **Tìm hiểu / Đọc:**
    - [ ] Thư viện Matplotlib và Seaborn cơ bản | Seaborn Gallery | Chưa thực hiện | Tìm hiểu cách vẽ biểu đồ cột (Bar chart).
* **Thực hành:**
    - [ ] Vẽ biểu đồ so sánh số lượng máy và giá trung bình theo hãng. | Ảnh trong `reports/` | [ ] | Dự kiến thực hiện tuần tới.

### Tuần 5 – Nâng cao / Tối ưu
* **Mục tiêu tuần:** Phân tích tương quan giữa cấu hình và giá bán.
* **Tìm hiểu / Đọc:**
    - [ ] Hệ số tương quan Pearson và Scatter Plot | Statistics How To | Chưa thực hiện | Tìm hiểu mối liên hệ giữa các biến số.
* **Thực hành:**
    - [ ] Phân tích mối quan hệ giữa RAM_GB và Price_VND. | `notebooks/Correlation.ipynb` | [ ] | 

### Tuần 6 – Kiểm thử & Đánh giá (Buổi trao đổi 3)
* **Mục tiêu tuần:** Tối ưu hóa Pipeline xử lý và kiểm tra logic dữ liệu.
* **Tìm hiểu / Đọc:**
    - [ ] Cách xử lý Outliers (Giá trị ngoại lai) | Pandas Guide | Chưa thực hiện | Tìm hiểu cách làm sạch dữ liệu nâng cao.
* **Thực hành:**
    - [ ] Viết hàm kiểm tra logic và hiệu chỉnh sai lệch dữ liệu. | `src/project/clean_pipeline.py` | [ ] | 

### Tuần 7 – Hoàn thiện cuối
* **Mục tiêu tuần:** Tổng kết báo cáo Insights và dọn dẹp Repo.
* **Thực hành:**
    - [ ] Hoàn thiện toàn bộ ghi chú học tập trong `docs/`. | Đủ 8 tuần docs. | [ ] | 
    - [ ] Viết README.md tổng kết dự án và Insights tìm được. | README.md hoàn chỉnh. | [ ] | 

### Tuần 8 – Tổng kết (Buổi trao đổi 4)
* **Mục tiêu tuần:** Demo kết quả và phản ánh quá trình thực tập.
* **Thực hành:**
    - [ ] Báo cáo cuối kỳ: Trình bày các Insights quan trọng từ dữ liệu giả lập. | Report/Slide demo. | [ ] | 

---

## 5. Checklist & Tổng kết
* [x] Nộp kế hoạch thực tập đúng hạn (Trước 23/02/2026).
* [ ] Tham gia đủ 04 buổi trao đổi online.
* [x] Cập nhật timeline-08tuan.md mỗi tuần.
* [x] Có ghi chú tìm hiểu trong `docs/` (Đã xong 3 tuần đầu).
* [ ] Sản phẩm cuối chạy được / demo được.

**Tự đánh giá mức độ hoàn thành:** 35%
**Điều tôi tự hào nhất:** Đã tự chủ động xây dựng script Python để tạo dữ liệu giả lập có logic, giúp làm chủ hoàn toàn quy trình phân tích.
**Vướng mắc:** Cần tìm hiểu cách tối ưu hóa biểu đồ để hiển thị chuyên nghiệp hơn.
