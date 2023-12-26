# WIRELESS ST_LINK
## Tổng quan
## Yêu cầu
* Giao tiếp qua cổng USB để nạp dữ liệu vô chip STM32/STM8.
* Trung gian giao tiếp truyền thông UART
* Nạp không dây từ máy tính xuống chip ST
## Linh kiện
* STM32F103CBT6: Thành phần chính trong việc đọc dữ liệu từ máy tính qua cổng COM để chuyển đổi và nạp vào chip STM8/STM32. Đồng thời có thể đọc và chuyển đổi dữ liệu UART giao tiếp giữa thiết bị với máy tính. Ngoài ra giao tiếp với ESP32 để nạp không dây cho chip ST.
* ESP32: Post và get dữ liệu nạp cho chip.