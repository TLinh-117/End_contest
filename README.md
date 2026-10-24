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
      + R² Score : 0.8217
      + RMSE     : 8.54
      + MAE      : 5.83

#### Model : RandomForestRegressor
      + R² Score : 0.8144
      + RMSE     : 8.71
      + MAE      : 5.91
