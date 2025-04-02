# THPTQG_source_analysis

<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/> 
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white"/>

Project này dử dụng các kiến thức đã học trong môn [Phân tích dữ liệu và học sâu](https://github.com/dusgkiet/DataAnalystDeepLearning) để làm nên bài báo cáo về `Phân tích về dữ liệu điểm thi THPT Quốc gia năm 2019 tại Hải Phòng.`

## Mục tiêu 

1. Làm sạch, xử lý và trực quan hóa dữ liệu điểm thi.
2. Phân tích phân bố điểm, số môn thi, tổ hợp thi.
3. Phát hiện outlier, xu hướng và mô hình điểm số.
4. Ứng dụng học máy (ML) để tìm tương quan và patterns.

## Nội dung chính:

**Tiền xử lý dữ liệu:** xử lý NaN, thêm cột số môn thi, tổ hợp thi.

**Phân tích mô tả:** thống kê điểm trung bình, độ lệch chuẩn, phân bố điểm từng môn.

**Trực quan hóa:** histogram, violin plot, boxplot, biểu đồ cột...

**Phát hiện outlier:** dùng IQR để phát hiện điểm bất thường.

**Phân tích tổ hợp thi:** xu hướng chọn KHTN/KHXH, phân bố số môn thi.

**Tương quan bằng ML:** dùng Random Forest & Gradient Boosting để tìm mối liên hệ giữa các môn.

**Phân tích chu kỳ & patterns:** dùng STUMPY để tìm chuỗi điểm lặp, clustering để phân nhóm học sinh theo điểm số.

## Các file chính 

[data.ipynb](https://github.com/dusgkiet/THPTQG_source_analysis/blob/main/data.ipynb): nơi thao tác với dữ liệu.

[thptqg_data_crawl.py](https://github.com/dusgkiet/THPTQG_source_analysis/blob/main/thptqg_data_crawl.py): file này dùng để crawl dữ liệu thô từ web về.

[BÁO CÁO CUỐI KÌ](https://github.com/dusgkiet/THPTQG_source_analysis/blob/main/B%C3%81O%20C%C3%81O%20CU%E1%BB%90I%20K%C3%8C.pdf): ghi lại những gì đã làm được.

[FILE TÓM TẮT BÁO CÁO](https://github.com/dusgkiet/THPTQG_source_analysis/blob/main/FILE%20T%C3%93M%20T%E1%BA%AET%20B%C3%81O%20C%C3%81O.pdf): file này tóm tắt gọn lại chỉ trong 2 trang giấy về những gì đã làm.
