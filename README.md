# LAPTOP PRICE PREDICTION
## Xây dựng hệ thống dự đoán giá laptop từ nền tảng CellphoneS

### 1. Tổng quan bài toán :

Laptop Price Prediction in Vietnam giải quyết bài toán định lượng hóa và dự báo giá laptop trên nền tảng trực tuyến CellphoneS tại Việt Nam từ 14 đặc trưng khác nhau.
- Thu thập dữ liệu từ trang web CellphoneS, xử lí dữ liệu thô và đưa thành tập dataset
- Tinh chỉnh dữ liệu, fill null và tách cột, làm sạch
- Biểu diễn EDA
- Data preprocessing
- Apply model
- Đưa ra két quả và nhận xét khái quát


### 2. Cấu Trúc Repository

```text
├──  README.md                  # Hướng dẫn cách đọc
├── requirement.txt             # Các thư viện cần thiết
├── End_contest.ipynb           # File code chính
└── cellphones_laptops_v3.csv   # Tập dữ liệu final (chưa qua tinh chỉnh)
```






### 3. Kết quả của model

####  Model : BaggingRegressor
 - Test R² Score : 0.7852
 - Test MAE      : 6.69
 - Test RMSE     : 12.67

#### Model : RandomForestRegressor
 - Test R² Score : 0.7949
 - Test MAE      : 6.66
 - Test RMSE     : 12.38

### Model : DecisionTreeRegressor
 - Test R² Score : 0.8080
 - Test MAE      : 6.71
 - Test RMSE     : 11.98
### Model : Ridge Regression
 - Test R² Score : 0.8254
 - Test MAE      : 6.44
 - Test RMSE     : 11.42
