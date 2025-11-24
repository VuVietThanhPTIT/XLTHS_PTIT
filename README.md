XLTHS_PTIT

Bài tập lớn xử lý tín hiệu số – Học viện Công nghệ Bưu chính Viễn thông (PTIT)


Ủng hộ mình chai nước lọc MB: 66623282328
Mình được 9.5 nên bạn có thể yên tâm tham khảo nhé!

📌 Giới thiệu

Bài tập lớn tập trung vào thiết kế bộ lọc số FIR (Finite Impulse Response) bằng ba phương pháp:

Cửa sổ (Window Method)

Lấy mẫu tần số (Frequency Sampling Method)

Bình phương tối thiểu (Least Squares Error Method)

Ngoài ra nhóm còn triển khai ứng dụng lọc âm và nhận dạng nốt nhạc từ file .wav.

📁 Nội dung chính


1️⃣ Phương pháp Cửa sổ (Window Method)

Thiết kế bộ lọc FIR bằng cách nhân đáp ứng xung lý tưởng với các loại cửa sổ:
Rectangular, Hanning, Hamming, Blackman, Kaiser…

2️⃣ Phương pháp Lấy mẫu tần số (Frequency Sampling)

Lấy mẫu đáp ứng tần số lý tưởng tại N điểm

Áp dụng điều kiện đối xứng để tạo pha tuyến tính

Sử dụng IFFT để thu được h(n)

3️⃣ Phương pháp Bình phương tối thiểu (Least Squares Error)

Thiết kế bộ lọc bằng cách tối thiểu hóa sai số bình phương giữa đáp ứng thật và đáp ứng mong muốn.

4️⃣ Ứng dụng: Lọc âm & Nhận dạng nốt nhạc

Đọc file .wav

Lọc tín hiệu bằng FIR

Phân tích FFT theo từng frame

Tìm tần số đặc trưng

Suy ra nốt nhạc theo âm giai
