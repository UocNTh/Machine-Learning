# Những khái niệm cơ bản

### **1. Nhiệm vụ, kinh nghiệm, phép đánh giá** 

*"Một chương trình máy tính được gọi là "**học tập**" từ kinh nghiệm E để hoàn thành nhiệm vụ T với hiệu quả được đo bằng phép đánh giá P, nếu hiệu quả của nó khi thực hiện nhiệm vụ T, khi được đánh giá bởi P, cải thiện theo kinh nghiệm E."*


VD: Một trò chơi máy tính có khả năng tự chơi cờ vây. Chương trình máy tính này sẽ học từ các ván cờ đã chơi trước đó của con người để tính toán ra chiến thuật hợp lý nhất. 

Chương trình máy tính có nhiệm vụ T là chơi cờ vây thông qua kinh nghiệm E là các ván cờ đã chơi trước đó với chính nó và con người, Phép đánh giá P ở đây là khả năng giành chiến thắng của chương trình. 

Để xây dựng một chương trình học máy, ta cần xác định rõ ba yếu tố: 
- Nhiệm vụ 
- Phép đánh giá 
- Nguồn dữ liệu huấn luyện 

### **2. Dữ liệu** 

- Các **nhiệm vụ** trong machine learning được mô tả bằng việc một hệ thông xử lý một điểm dữ liệu đầu vào như thế nào.

- **Kinh nghiệm** trong machine learning là bộ dữ liệu được sử dụng để xây dựng mô hình. Thường được chia ra làm 3 tập dữ liệu không giao nhau: Training set, Test set, Validation set.

- **Tập huấn luyện** là bộ dữ liệu được sử dụng trong quá trình xây dựng mô hình

- **Tập kiểm tra** là bộ dữ liệu được dùng để đánh giá mô hình

- **Tập xác thực** được sử dụng trong việc lựa chọn các siêu tham số mô hình

### **3. Các bài toán cơ bản trong Machine Learning** 

**3.1 Phân loại (Classification)**

Một trong những bài toán được nghiên cứu nhiều nhất trong Machine Learning.

Chương trình được yêu cầu xác định class/label của một điểm dữ liệu trong số C nhãn khác nhau

VD bài toán: Phân loại chữ số viết tay, Phân loại thư rác(spam)

**3.2 Hồi quy (Regression)** 


Nếu tập địch gồm các giá trị thực (có thể là vô hạn) thì bài toán được gọi là hồi quy.

VD Ước lượng giá của một căn nhà có x (m2) chứa y (phòng) và cách trung tâm thành phố z (km).

VD Một ứng dụng dự đoán giới tính và tuổi dựa trên khuôn mặt. Dự đoán giới tính là một bài toán 

**3.3 Máy dịch** 

Trong bài toán máy dịch, dịch từ một đoạn văn bản từ ngôn ngữ này sang ngôn ngữ khác. Dữ liệu huyến luyện là các cặp văn bản song ngữ

**3.4 Phân cụm** 

**3.5 Hoàn thiện dữ liệu** 

### **4. Phân nhóm các thuật toán Machine Learning** 

**4.1 Học có giám sát (Supervised Learning)** 

Việc xây dựng mô hình dự đoán mối quan hệ đầu vào và đầu ra được thực hiện dựa trên các cặp (đầu vào, đầu ra) đã biết trong tập huấn luyện. 

Đây là một thuật toán phổ biến nhất trong các thuật toán Machine Learning

Các thuật toán phân loại và hồi quy là ví dụ điển hình trong nhóm này


