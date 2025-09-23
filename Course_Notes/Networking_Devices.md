*Ngày 1. Networking Devices - Thiết bị mạng

## Mạng là gì?
- Mạng máy tính là 01 mạng viễn thông số cho phép các nút (nodes) chia sẻ tài nguyên.
- Client (máy khách): là thiết bị truy cập dịch vụ do Server cung cấp.
- Server là thiết bị cung cấp chức năng/dịch vụ cho các client.

## Switch (Thiết bị chuyển mạch - Tầng 2)
- Cung cấp kết nối cho các máy chủ và máy trạm trong cùng 01 mạng LAN (nội bộ).
- Có nhiều cổng mạng để các *end hosts* (máy tính, máy in, camera,..) kết nối
*Không thể kết nối mạng LAN khác nhau hay ra Internet*
-> Giống như 01 "ổ cắm điện có nhiều ngõ ra" chỉ giúp các thiết bị trong cùng 01 văn phòng/nhà chia sẻ dữ liệu với nhau.

## Router (Bộ định tuyến - Tầng 3)
- Thường có ít cổng mạng hơn Switch.
- Dùng để kết nối giữa nhiều LAN khác nhau.
- Cho phép dữ liệu truyền ra Internet
-> Giống như "người đưa thư quốc tế" gửi tin ra ngoài mạng khác.
## FIREWALL (Tường lửa - tâng 3, 4, 7)
- Là thiết bị phần cứng chuyên dụng về bảo mật mạng, kiểm soát lưu lượng đi vào/ra khỏi hệ thống mang.
- Có thể đặt bên trong hoặc bên ngoài mạng.
- Giám sát và kiểm soát lưu lượng dựa trên các qui tắc cấu hình.
- Khi được tích hợp khả năng lọc nâng cao, hiện đại thì gọi là Next-Generation FireWall (NGFW).
- Ngoài ra, còn có host-based FireWall là phần mềm cài trực tiếp trên máy tính để lọc lưu lượng chính máy đó.

![Sơ đồ](img/d1_img1.png)

### Câu hỏi.
Q1. Công ty bạn muốn mua một số phần cứng mạng để kết nối 30 máy tính trong phòng ban của bạn. Loại thiết bị mạng nào phù hợp?
a. Bộ định tuyến (Router) - Ví dụ như 
b. Tường lửa- Ví dụ như: Cisco ASA 5500-X
c. Bộ chuyển mạch (switch) -> CA
d. Máy chủ

Q2. Bạn nhận được một tệp video từ Iphone Apple của bạn mình Bằng AirDrop. Iphone của anh ấy hoạt động như thế nào trong giao dịch đó?
a. Server -> CA
b. Client
c. Mạng cục bộ LAN

Q3. Máy tính hoặc điện thoại thông minh của bạn hoạt động thế nào khi xem 01 video trên Youtube?
a. Server
b. Client -> CA
c. end host

Q4. Công ty của bạn muốn mua một số phần cứng mạng để kết nối các mạng riêng lẻ với nhau. Loại thiết bị mạng nào là phù hợp?
a. Bộ định tuyến (Router) -> CA
b. Tường lửa- Ví dụ như: 
c. Mạng cục bộ LAN
d. Máy chủ

Q5. Công ty của bạn muốn nâng cấp tường lửa cũ đã sử dụng trong nhiều năm lên một tường lửa có chức năng tiên tiến hơn. Họ nên mua loại tường lửa nào?
a. An host-based firewall (Giống như phần mềm chặn tập tin lạ xâm hại trên máy tính)
b. An host-level firewall
c. An next-generation firewall -> CA
d. An top-layer firewall