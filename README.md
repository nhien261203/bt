# Kiểm thử hiệu năng web với jmeter
## Mục tiêu

Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://www.facebook.com/?locale=vi_VN

Chạy kịch bản kiểm tra và ghi lại kết quả.

Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

## Kịch bản kiểm tra

Thread Group:

Số lượng thread: 10
Thời gian chạy: 11 giây
Ramp-up period: 10 giây
![thread](https://github.com/nhien261203/bt/assets/167493331/c05ffffa-6c80-4e3e-98fe-d0f6243efdbb)

HTTP request
![http](https://github.com/nhien261203/bt/assets/167493331/7b86ab5e-70df-444f-8409-58bd49fcfd71)


Kết quả 10 người truy cập cùng 1 lúc 
![truycap](https://github.com/nhien261203/bt/assets/167493331/faea7fb3-4a43-42a8-af60-a8736de36223)

