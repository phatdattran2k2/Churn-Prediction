# Churn-Prediction

### Mô tả 
  Mô hình dự đoán khả năng rời mạng viễn thông của khách hàng được xây dựng từ ba giải thuật: KNN, Cây quyết định và XGBoost. Mô hình sử dụng tập dữ liệu bao gồm 21 cột thuộc tính được lưu trữ và trích xuất của 3217 thuê bao đang sử dụng hoặc đã rời mạng tại VNPT Cần Thơ. Trong đó 20 cột đầu bao gồm các thuộc tính ảnh hưởng đến sự rời mạng của thuê bao, cột 21 là cột Churn (thanhly), cột này là cột gắn nhãn của tập dữ liệu, cột để nhận biết là thuê bao có ý định rời mạng hay không.


  Kết quả dự báo khách hàng có khả năng rời mạng cao với tỉ lệ chính xác dự báo của mô hình so với số liệu thực tế rất cao với độ chính xác (accuracy) của các giải thuật KNN, Cây quyết định, XGBoost lần lượt là 97.453%, 96.398%, 97.702%. 


