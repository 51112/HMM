# HMMDự đoán Nhiệt độ Hà Nội bằng HMM Phi Tuyến + Particle Filter
📌 Mô tả dự án
Dự án này sử dụng HMM phi tuyến kết hợp với Particle Filter cải tiến để dự đoán nhiệt độ từ dữ liệu thời tiết thu thập ở Hà Nội.
Mục tiêu là ước lượng trạng thái ẩn (nhiệt độ thực sự) từ dữ liệu quan sát nhiễu và không đầy đủ.

🔎 Dữ liệu được lấy từ trang rp5.ru — nguồn cung cấp dữ liệu thời tiết lịch sử và theo thời gian thực.

🧠 Phương pháp sử dụng
HMM phi tuyến: Mô hình chuỗi thời gian với trạng thái ẩn, không giả định phân phối chuẩn.

Particle Filter: Kỹ thuật suy luận xấp xỉ sử dụng nhiều "hạt" để mô phỏng phân phối xác suất của trạng thái.

Dự đoán

Cập nhật trọng số

Resampling

Ước lượng trạng thái

⚙️ Công nghệ & Thư viện
Python 3.x

pandas, numpy

matplotlib, seaborn

scikit-learn

📈 Kết quả
Trực quan hóa so sánh giữa nhiệt độ thực tế và dự đoán.

Tính toán chỉ số RMSE, MAE, R².

Đánh giá hiệu quả của mô hình qua từng giai đoạn thời gian.

🚧 Hạn chế & Định hướng phát triển
Chưa tích hợp các yếu tố ngoại sinh như mưa, ánh sáng, dữ liệu vùng lân cận.

Có thể mở rộng sang LSTM hoặc Deep State Space Models trong tương lai.
