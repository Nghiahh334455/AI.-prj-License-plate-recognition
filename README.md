# AI.-prj-License-plate-recognition
🚗 Dự Án Nhận Diện Biển Số Xe (License Plate Recognition - LPR)
🌟 Giới Thiệu Chung
Dự án này là một ứng dụng sử dụng Python và thư viện xử lý ảnh để tự động nhận diện, trích xuất và đọc ký tự từ biển số xe trong hình ảnh hoặc luồng video.
Mục tiêu: Phát triển một giải pháp chính xác và hiệu quả để tự động hóa việc kiểm soát truy cập hoặc giám sát phương tiện.
Công nghệ cốt lõi: Xử lý ảnh (Computer Vision) 
⚙️ Tính Năng Nổi Bật
Phát hiện Biển số: Nhận diện và khoanh vùng vị trí biển số xe trong ảnh (License Plate Detection).
Trích xuất Ký tự: 
Độ chính xác: Đạt độ chính xác khoảng [ độ chính xác 95%] trong điều kiện ánh sáng tốt/tiêu chuẩn.
1. Xử lý ảnh (Image Processing)
Median Blur - Lọc nhiễu
Gamma Correction - Hiệu chỉnh độ sáng
Histogram Equalization - Cân bằng histogram để tăng độ tương phản
Bilateral Filter - Khử nhiễu với bảo toàn cạnh
Morphological Operations (Erosion & Dilation) - Xử lý hình thái học
Canny Edge Detection - Phát hiện cạnh
Adaptive Thresholding - Chuyển đổi nhị phân thích ứng
2. Phát hiện đối tượng (Object Detection)
Contour Detection - Phát hiện đường viền của biển số
Bounding Rectangle - Xác định vùng chứa biển số dựa trên tỷ lệ khung hình và diện tích
3. Deep Learning - Convolutional Neural Network (CNN)
4. Kỹ thuật huấn luyện
Data Augmentation - Xoay, zoom, shift hình ảnh
Train/Validation/Test Split (70%-15%-15%)
Early Stopping & Model Checkpoint - Lưu mô hình tốt nhất

CONTACT WITH ME : NGHIAEMTC2K4@GMAIL.COM  
