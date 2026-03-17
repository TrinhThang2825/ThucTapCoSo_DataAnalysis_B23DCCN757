# Nhật ký thực tập - Tuần 2: Tạo dữ liệu giả lập (Synthetic Data)

## 1. Nội dung tìm hiểu (Đọc)
- **Thư viện Numpy:** Cách sử dụng `np.random.choice` để tạo dữ liệu phân loại và `np.random.randint` để tạo dữ liệu số.
- **Khái niệm Synthetic Data:** Tìm hiểu tại sao trong thực tế, các chuyên gia thường tạo dữ liệu giả lập để kiểm thử thuật toán trước khi áp dụng vào dữ liệu thật.

## 2. Kết quả tìm hiểu (Hiểu)
- **Tại sao chọn 200 dòng?** - 200 dòng là con số vừa đủ để thấy được sự biến động và quy luật thống kê (Luật số lớn sơ bộ). 
    - Nếu quá ít (ví dụ 10-20 dòng), các biểu đồ sẽ bị nhiễu và không thể hiện rõ xu hướng thị trường. 
    - Con số này cũng đảm bảo hiệu năng xử lý nhanh trên môi trường học tập.
- **Logic dữ liệu:** Để dữ liệu có giá trị phân tích, cần thiết lập mối quan hệ giữa các biến (Ví dụ: RAM cao thì giá phải cao hơn).

## 3. Thực hiện (Làm)
- Viết script Python sử dụng `Pandas` và `Numpy` để tạo bộ dữ liệu 200 dòng.
- Các trường thông tin bao gồm: `Laptop_ID`, `Brand`, `Type`, `RAM_GB`, `Storage_GB`, `Rating`, `Price_VND`.
- Xuất dữ liệu thành công ra file `data/laptop_data_2026.csv`.
