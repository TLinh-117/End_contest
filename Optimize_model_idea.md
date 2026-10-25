## 1. Các lỗi trong bài
- Thiếu Macbook
- Chưa lọc sản phẩm cũ
- Features còn thiếu nhiều thứ quan trọng



## 2. Ý tưởng cải thiện
- Phân chia lại GPU thông minh hơn : Đưa GPU thành 5 tier list khác nhau

    Ví dụ : cùng là dòng 50 nhưng 5090 > 5080 > 5070ti > 5070 > 5060ti > 5060 > 5050


    Ví dụ : cùng là card tích hợp nhưng Intel UHD Graphics <<<<< AMD Radeon 8060S
    
    + Phân loại GPU theo tier list :


      iGPU cơ bản < dGPU đời cũ < AI iGPU < dGPU tàm trung < dGPU cao cấp < iGPU flagship < dGPU flagship




- Thêm features quan trọng, bỏ 1 trong 2 cái resolution width/ resolution height:


  + Thêm weight (cân nặng của máy)
  
      
  + Thêm cpu_ultra (có 1 số dòng chip pro hoặc ultra giá thành sẽ nhỉnh hơn)
      
      
  + Thêm touch_screen (màn hình cảm ứng)


  + Gộp resolution width/ resolution height thành res (để hai hệ số tương quan cao, cùng hướng đến 1 thông tin trong features là vô nghĩa)


  + Thêm screen_hz (tần số quét màn hình)


- Nếu đã chỉnh GPU thành tier list thì nên đổi thành LabelEncoder thay vì OnehotEncoder
