# Kiểm thử hiệu năng web với jmeter
## Mục tiêu

Sử dụng jMeter để tạo một kịch bản kiểm tra mô phỏng người dùng truy cập trang web https://github.com/

Chạy kịch bản kiểm tra và ghi lại kết quả.

Phân tích kết quả kiểm tra, bao gồm thời gian phản hồi, số lượng yêu cầu thành công, số lượng yêu cầu thất bại, v.v.

Dựa trên kết quả phân tích, đưa ra kết luận về hiệu năng của trang web.

## Kịch bản kiểm tra

Thread Group:

Số lượng thread: 100

Thời gian chạy: 100 giay 

Ramp-up period: 10 giây
![threadgit](https://github.com/nhien261203/bt/assets/167493331/af68fa6c-770b-4ad7-a8d4-190ad91455db)


HTTP request
![httpgit](https://github.com/nhien261203/bt/assets/167493331/c25c6edb-dc83-4800-95a6-a8664b1b43ab)



Kết quả 10 người truy cập cùng 1 lúc 
![100ng](https://github.com/nhien261203/bt/assets/167493331/15a5654a-965c-4143-bd60-3e9b669830e4)


Phân tích: 

tỷ lệ thành công cao: 503/510 
