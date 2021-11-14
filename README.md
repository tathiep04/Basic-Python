# DSP301x_1.1-A_EN
Introduction to Data Science

This is some of solution on the Lab code that I had learned from Funix. Save it as a pack to study more.


############################
Introduction to Data Science

1. Python basic

Các kiểu data khác nhau: Float, int, str.
Các biểu thức tính toán: +,  -,  *, **,  //,  %,  /,  &, |.
Các kiểu cấu trúc CSDL cơ bản: List, tuple, set, dictionary (định nghĩa, ứng dụng của từng loại và so sánh chúng với nhau).
Đọc, ghi và xử lý text file.
Vòng lặp, câu lệnh có điều kiện, cấu trúc xử lý exception (try-except).
Khai báo và sử dụng hàm: Cách thông thường và cách sử dụng lambda.
Cách khởi tạo, mở, lưu và xóa Jupyter Notebook file trên local machine/google colab.
2. Python OOP

Định nghĩa class và object.
Khai báo và sử dụng attribute, method.
Cách khai báo constructor, destructor.
Class inheritance: Ý nghĩa, cách khai báo và ứng dụng.
3. Python for Data Science

3.1. Numpy trong Python

Khai báo thư viện numpy, sự khác biệt giữa numpy và list.
Một số phép xử lý đơn giản trong numpy: Indexing, slicing, khai báo mảng nhiều chiều.
Các phép tính cơ bản trong numpy: Cộng trừ nhân 2 ma trận, phép tính nhân từng vị trí giữa 2 ma trận.
Các phép tính thống kê và xử lý dữ liệu trong numpy: Mean, median, standard deviation, min, max, det.
Các phép xử lý cắt/ghép array trong numpy: Cắt/nối mảng, xoay mảng, xóa mảng.
Các phép xử lý advance (các methods khác trong class numpy).
3.2. Pandas với Python

Khai báo thư viện, sự khác biệt giữa pandas và numpy/list.
Đọc, ghi và xử lý csv/txt/xlsx file với Pandas.
Một số phép xử lý cơ bản trên DF: head, summary, các phép truy xuất thông tin theo hàng/cột hay truy xuất thông tin có điều kiện đi kèm, thêm cột/xóa cột trong df.
Các phép thống kê trong pd: Mean, min, median, max, summary, IQR, standard deviation, xử lý missing data và outlier.
Xử lý nâng cao: Áp dụng 1 function vào 1 cột, groupby, sort, các câu lệnh khác (các methods khác trong class pd).
3.3. Sklearn

Khai báo thư viện, ý nghĩa của thư viện sklearn.
Một số nhóm cấu trúc lệnh cơ bản: fit, fit_transform, score.
Tìm hiểu sâu hơn về sklearn: Chạy cho các thuật toán nào, chạy trên CPU hay GPU, có gì ưu việt hơn so với các ML libraries khác.
4. Math in ML

4.1. Stats

Cách tính và ý nghĩa của các thông số sau: Mean, mode, median, min, max, variance, standard deviation.
Concept của events, sample space và random trials.
Dữ liệu trên miền liên tục/miền rời rạc.
Range, interquartile range, IQR.
Các data distribution khác nhau: Normal, Bernoulli, Uniform, vv…
Correlation (Pearson's r)/regresion, similarity/distance function.
Visualization: Frequency table, scatter plot, contingency table.
4.2. Probability

Định nghĩa và cách tính toán xác suất thông thường/xác suất có điều kiện.
Dependence/independence event.
Random event.
Định lý Bayes.
5. Overview of DS

5.1. Từ bài toán đến hướng tiếp cận và cách giải quyết

Hiểu rõ bài toán business (Business Understanding)

Làm rõ vấn đề.
Xác định mục tiêu.
Xác định objective để hoàn thành mục tiêu.
Xác định phương pháp phân tích phù hợp

Phương pháp tiếp cận phân loại (classification approach).
Phương pháp tiếp cận dự báo (regression approach).
Phương phép tiến cận thống kê mô tả (descriptive approach).
5.2. Từ yêu cầu đến thu thập dữ liệu

Yêu cầu dữ liệu (Data requirement)

Xác định nội dung dữ liệu
Xác định định dạng và nguồn để thu thập dữ liệu ban đầu
Thu thập dữ liệu (Data collecting)

Viết các tool để thu nhặt và thu thập dữ liệu.
Đưa ra các thống kê mô tả và trực quan hóa ban đầu về dữ liệu.
Đánh giá số lượng, chất lượng và các hiểu biết ban đầu về dữ liệu.
5.3. Từ hiểu dữ liệu đến chuẩn bị dữ liệu

Hiểu dữ liệu (Data understanding)

Khai phá dữ liệu (Data mining)
Phân tích dữ liệu (EDA)
Chuẩn bị dữ liệu

Làm sạch dữ liệu (Data cleaning)
Chuyển đổi dữ liệu (Data transformation)
Trích xuất đặc trưng của dữ liệu (Feature engineering)
5.4. Từ mô hình hóa dữ liệu đến việc đánh giá mô hình

Mô hình hóa dữ liệu (Data modelling):

Lựa chọn mô hình (Model selection)
Huấn luyện mô hình (Training model)
Đánh giá mô hình (Model evaluation):

Đánh giá độ chính xác của mô hình (Training/Validation accuracy)
5.5. Từ phản hồi đến triển khai mô hình thực tế

Phản hồi kết quả của mô hình

Phân tích lỗi (Error analysis)
Cải thiện mô hình (Model finetuning)
5.6. Triển khai mô hình (model deployment)

Cài đặt môi trường (Environment setting)
Triển khai mô hình thực tế (Serving model deployment)
