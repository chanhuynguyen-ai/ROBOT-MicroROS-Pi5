# MicroROS-Pi5

**MicroROS-Pi5** là dự án xây dựng hệ thống **robot nhúng sử dụng micro-ROS trên Raspberry Pi 5** để kết nối vi điều khiển với hệ sinh thái **ROS 2**. Mục tiêu của đề tài là tạo cầu nối giữa thế giới **embedded real-time** (ESP32/STM32) và hệ thống robot cấp cao chạy trên Linux, cho phép trao đổi dữ liệu cảm biến, điều khiển cơ cấu chấp hành và tích hợp thuật toán AI/Computer Vision trong cùng một kiến trúc ROS thống nhất.

Hệ thống tập trung vào giao tiếp **publisher/subscriber, service và message** giữa vi điều khiển và ROS 2 thông qua micro-ROS agent chạy trên Pi 5. Dự án phù hợp cho các ứng dụng robot di động, xe tự hành mô hình, IoT robot, và các bài toán cần độ trễ thấp ở tầng điều khiển nhưng vẫn khai thác được sức mạnh xử lý của Raspberry Pi.


<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/5cd6047e-0efa-4f44-b260-8a1592592784" />
