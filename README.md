## Amazon Fine Food Reviews Analysis

### Mô tả
Tệp notebook `amazon-fine-food-review.ipynb` chứa mã nguồn phân tích tập dữ liệu đánh giá thực phẩm trên Amazon. Tập dữ liệu này được lấy từ dataset **Amazon Fine Food Reviews trên Kaggle**, bao gồm hơn 500.000 đánh giá của người dùng về các sản phẩm thực phẩm, bao gồm cả văn bản đánh giá, xếp hạng sao và thông tin khác.

### Nội dung chính của Notebook
- **Tiền xử lý dữ liệu:** Làm sạch dữ liệu, xử lý giá trị thiếu, chuyển đổi văn bản.
- **Phân tích dữ liệu:** Thống kê mô tả, trực quan hóa dữ liệu.
- **Phân tích cảm xúc:** Sử dụng SentimentIntensityAnalyzer để đánh giá cảm xúc của các nhận xét.
- **Trực quan hóa dữ liệu:** Tạo WordCloud và biểu đồ để hiển thị các xu hướng chính trong dữ liệu.

### Kết quả đạt được & Insight
- **Phân bố xếp hạng sản phẩm:**
  - Đa số người dùng đánh giá sản phẩm ở mức 4 và 5 sao, cho thấy phần lớn khách hàng hài lòng với sản phẩm.
  - Rất ít đánh giá 1 hoặc 2 sao, chứng tỏ số lượng phản hồi tiêu cực thấp hơn đáng kể so với phản hồi tích cực.

- **Từ phổ biến trong đánh giá tích cực & tiêu cực:**
  - Các từ phổ biến trong đánh giá **tích cực** bao gồm "great", "delicious", "love", "best", "tasty" → nhấn mạnh chất lượng tốt của sản phẩm.
  - Các từ phổ biến trong đánh giá **tiêu cực** bao gồm "bad", "disappointed", "waste", "awful", "terrible" → thể hiện sự thất vọng của khách hàng về sản phẩm hoặc dịch vụ.

- **Độ dài trung bình của đánh giá:**
  - Độ dài trung bình của một bài đánh giá là khoảng **80-100 từ**, cho thấy người dùng có xu hướng viết nhận xét chi tiết thay vì chỉ đánh giá ngắn gọn.

- **Phân bố điểm cảm xúc (Sentiment Score):**
  - Điểm cảm xúc có xu hướng nghiêng về phía tích cực, chứng minh rằng phần lớn đánh giá mang tính khen ngợi hơn là chỉ trích.

- **WordCloud cho đánh giá tích cực và tiêu cực:**
  - Trong đánh giá **tích cực**, các từ như "amazing", "excellent", "recommend", "perfect" xuất hiện nhiều.
  - Trong đánh giá **tiêu cực**, các từ như "refund", "horrible", "problem", "never" thường xuất hiện, phản ánh các vấn đề mà khách hàng gặp phải.

