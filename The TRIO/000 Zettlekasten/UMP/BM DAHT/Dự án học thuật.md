![[#1. Các loại thiết kế nghiên cứu]]

## 1. Các loại thiết kế nghiên cứu
- Một số thiết kế nghiên cứu thường sử dụng => thác mức độ chứng cứ
![[Dự án học thuật-1687331809723.jpeg|444]]
- Báo cáo ca và hàng loạt ca
	- Báo cáo ca: < 3 ca
	- Hàng loạt ca: nhiều hơn 30 ca
	- Chỉ **trình bày lại**
	- Mô tả lại các trường hợp cấp nên thiếu tính khái quát hóa
	- Tạo nên các câu hỏi nghiên cứu mới
- Cắt ngang, đoàn hệ hồi cứu và bệnh chứng, đoàn hệ tiến cứu
	- Nghiên cứu cắt ngang: **mô tả dân số** hoặc tìm **tỉ lệ hiện mắc**. Hạn chế trong xác định trình tự nguyên nhân – hậu quả. Thường câu hỏi là TÌM TỈ LỆ (hiện mắc)
		- VD: BN hen dùng bình xịt MDI để điều trị phòng ngừa. **Tỉ lệ** BN sử dụng bình xịt đúng là bao nhiêu?
	- Bệnh chứng đi **từ bệnh lý** -> Thường là câu hỏi NGUYÊN NHÂN-KẾT QUẢ: ==HỒI CỨU==
		- VD: 
	- Đoàn hệ đi **từ phơi nhiễm** hay không phơi nhiễm: ==hồi cứu/tiến cứu==
- RCT
	- Đánh giá ==hiệu quả== của một can thiệp mới hoặc điều trị mới
	- Câu hỏi NC là: Thuốc A có HIỆU QUẢ HƠN trong điêu trị bệnh
	- Phải có nhóm chứng, là tiến cứu
	- VD: Tại Mỹ, thuốc sinh học A mới sản xuất, có hiệu quả phòng ngừa đợt cấp hen suyễn tốt hơn so với MDI. **Đánh giá hiệu quả** thuốc A cho bệnh nhân hen suyễn tại Việt Nam.



## 2. Các phương pháp phân tích thống kê
- Bảng test tham số hay test phi tham số (mẫu nhỏ-định danh, thứ hạng – sức mạnh ít hơn). Cho TH cỡ mẫu bn, tham số, chọn test phù hợp
- Nhớ đơn giản:
	- Test tham số (máy cái phân phối chuẩn, biến định lượng) -> Student’s t test, ANOVA, tương quan, hồi quy
	- Test phi tham số (Phân phối không chuẩn/không biết phân phân bố, Biến định danh hay thứ hạng) -> Test chi BP, Fisher, Mann Whitne u test, Mc Nemar
- Phân tích sự khác nhau: chọn phép kiểm (Lưu đồ)
	- Bảng 2x2 => Chi bp, ko làm được chi bp (1 trong các số đó 5) thì Fisher
	- Xem các ví dụ slide
	![[Dự án học thuật-1687331836521.jpeg]]
- Phân tích sự tương quan: độ lớn mối tương quan và ý nghĩa thống kê
	![[Dự án học thuật-1687331845922.jpeg]]
	- Lưu đồ, các chỉ số
	- Bệnh chứng: OR => Hồi quy logistic
	- Cắt ngang OR hay PR => hồi quy nhị phân/logistics
	- Thời gian: RR => Hồi quy COX
	- RCT: RR hay HR => hồi quy COX

- Tỷ lệ lưu hành và Tần suất mới mắc
- Tương quan: 
	- ko chuẩn là Spearman => KHÔNG KẾT LUẬN SỰ ẢNH HƯỞNG CỦA CÁC BIẾN
	- Chuẩn là Pearson: hai biến có phân phối chuẩn
- Hồi quy: => KẾT LUẬN ĐƯỢC ẢNH HƯỜNG CỦA CÁC BIẾN
	- Hồi quy tuyến tính
	- Hồi quy Logistics: biến nhị phân
	- Hệ số tương quan R2: ĐÓng góp số % vào thay đổi
	- Hệ số hồi quy Beta: độ thay đổi của kq khi biến thay đổi 1 đơn vị

## 3. Giá trị chẩn đoán
- Ss, Sp cách tính

| -        | Có giang mai | Không có giang mai | Tổng |
|----------|---------------|---------------------|-------|
| TPHA (+) | 48            | 150                 | 198   |
| TPHA (-) | 2             | 9800                | 9802  |
| Tổng    | 50            | 9950                | 10000 |

Độ nhạy (Se) = 48/50 = 96% (khả năng XN để **xác định** người mắc bệnh)
Độ đặc hiệu (Sp) = 9800/9950 = 98.5% (khả năng để XN **loại trừ** người mắc bệnh)
Giá trị tiên đoán dương = 48/1985 = 24.2% (**Xác xuất mắc bệnh** khi XN dương tính)
Giá trị tiên đoán âm = 9800/9802 = 99.9% (**Xác xuất không mắc bệnh** khi XN âm tính)

- Đường cong ROC (AUC => diện tích dưới đường cong) => xác định cut off
	- AUC bao nhiêu là rất tốt, tốt,.., ==p-value <0.05==
	- Chỉ số Youden Index: `J = Sen – (1-Sp)` 
	  Càng cao càng tốt

| AUC         |       Ý nghĩa       |
| ----------- |:-------------------:|
| > 0.90      | Rất tốt (Excellent) |
| 0.80 - 0.90 |     Tốt (Good)      |
| 0.70 - 0.80 |  Trung bình (Fair)  |
| 0.60 - 0.70 |  Không tốt (Poor)   |
| 0.50 - 0.60 |   Vô dụng (Fail)    |
