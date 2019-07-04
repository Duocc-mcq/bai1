


# Network Fundamentals
## 1.What is a Network?
- Mạng là tập hợp tất cả các thiết bị được kết nối với nhau bằng phương tiện truyền tải vật lý
## 2.Advantages and Disadvantages of Network 
### Advantages 
- Chia sẻ các thiết bị như máy in giúp tiết kiệm tiền.
- Trang web ( phần mềm) giấy phép có thể rẻ hơn so với việc mua một số giấy phép độc lập.
- Tập tin có thể dễ dàng được chia sẻ giữa những người dùng.
- Mạng người dùng có thể giao tiếp qua email và tin nhắn tức thời.
- Bảo mật rất tốt - người dùng không thể xem các tệp của người dùng khác không giống như trên các máy độc lập.
- Dữ liệu dễ dàng sao lưu vì tất cả dữ liệu được lưu trữ trên máy chủ tập tin.
### Disavantages 
- Mua cáp mạng và máy chủ tập tin có thể tốn kém.
 - Quản lý một mạng lớn rất phức tạp, đòi hỏi phải đào tạo và người quản lý mạng thường cần được tuyển dụng.
- Nếu máy chủ tệp bị hỏng, các tệp trên máy chủ tệp sẽ không thể truy cập được. Email vẫn có thể hoạt động nếu nó ở trên một máy chủ riêng biệt. Các máy tính vẫn có thể được sử dụng nhưng bị cô lập.
- Virus có thể lây lan sang các máy tính khác trên toàn mạng máy tính.
Có nguy cơ bị hack, đặc biệt với các mạng diện rộng. Các thủ tục bảo mật là cần thiết để ngăn chặn sự lạm dụng đó, ví dụ như tường lửa
## 3.Common physical compoment of network
- Routers là thiết bị trên mạng chuyển tiếp dữ liệu từ thiết bị này sang thiết bị khác.Dữ liệu này được gửi trong các gói từ thiết bị này sang thiết bị khác.Router đọc thông tin  mạng trên các gói để xác định đích cần định tuyến.
- Switches là một thiết bị mạng kết nối các thiết bị trên mạng cho phép dữ liệu được truyền trong mạng 
- Network hubs là một thiết bị mạng khác kết nối nhiều thiết bị ngoại vi trên mạng khiến chúng hoạt động như một phân đoạn duy nhất.
- Wireless access points là một thiết bị truy cập kết nối không dây.Điểm truy cập hoạt động như một bộ định tuyến bằng các định tuyến từ dữ liệu thiết bị này sang thiết bị khác bằng cách sử dụng tần số không dây.
- Network Cables được sử dụng kết nối vật lí các thiết bị mạng với nhau 
- Network Server là máy tính trên chính mạng.Máy chủ cung cấp các chức năng tất cả các thiết bị khác trên mạng và các thiết bị này được biết đến với tên gọi là máy khách.
- Network Interface Cards (NIC) là Để một thiết bị có thể kết nối với mạng, nó cần có thẻ giao diện mạng (NIC). NIC, còn được gọi là bộ điều hợp mạng, cho phép thiết bị gửi và nhận dữ liệu qua mạng thông qua việc sử dụng cáp Ethernet hoặc Kết nối không dây. 
Nếu không cài đặt NIC, thiết bị sẽ không thể kết nối với mạng.
## 4.Interpreting a network diagram


## 5.Compare physical topology and logical topology
- Cấu trúc liên kết logic là cách các thiết bị xuất hiện kết nối với người dùng.Cấu trúc liên kết logic cho biết cách quản lý dữ liệu trong mạng bất kể cấu trúc liên kết vật lý của nó.
- Cấu trúc liên kết vật lý của mạng được xác định bởi khả năng của các thiết bị và phương tiện truy cập mạng, mức độ kiểm soát hoặc khả năng chịu lỗi mong muốn và chi phí liên quan đến cáp hoặc cáp viễn thông.
## 6.Describe the network topologies
- Cấu trúc liên kết mạng là sự sắp xếp của các yếu tố ( liên kết , nút , v.v.) của mạng truyền thông.  topo mạng có thể được sử dụng để xác định hoặc mô tả sự sắp xếp của nhiều loại hình mạng viễn thông, bao gồm cả chỉ huy và kiểm soát các mạng vô tuyến,  công nghiệp fieldbusses và mạng máy tính .
[John_Gruber](https://en.wikipedia.org/wiki/John_Gruber)
[John_Gruber](https://en.wikipedia.org/wiki/John_Gruber "Markdown Creator")
![Atom](https://upload.wikimedia.org/wikipedia/commons/9/96/NetworkTopologies.png) 
Sơ đồ cấu trúc liên kết mạng khác nhau 
**Phân loại**
- Point-to-point
- Bus 
![Atom](https://upload.wikimedia.org/wikipedia/commons/thumb/4/47/BusNetwork.svg/527px-BusNetwork.svg.png) 
- Star
![Atom](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/StarNetwork.svg/800px-StarNetwork.svg.png) 
## 7.Describe function and operation of hub,switch and router 
**a.Router**
- Router là một thiết bị mạng máy tính dùng để chuyển các gói dữ liệu qua một liên mạng và đến các đầu cuối, thông qua một tiến trình được gọi là định tuyến. Định tuyến xảy ra ở tầng 3 tầng mạng của mô hình OSI 7 tầng.
 ![Atom](https://upload.wikimedia.org/wikipedia/commons/9/9a/Linksys_BEFSR41_Router_20040321.jpg )   ***Bộ router NAT của Linksys, thường sử dụng cho những mạng máy tính ở nhà hay ở cơ sở nhỏ***
- Router hoạt động như một liên kết giữa hai hoặc nhiều mạng và chuyển các gói dữ liệu giữa chúng. Router dựa vào bảng định tuyến (routing table) để tìm đường đi cho gói dữ liệu. Bảng định tuyến được quản trị mạng cấu hình tĩnh (static), nghĩa là được thiết lập 1 lần và thường do quản trị mạng nhập bằng tay, hoặc động (dynamic), nghĩa là bảng tự học đường đi và nội dung tự động thay đổi theo sự thay đổi của tô pô mạng.
**b.Switch**
- Switch là một thiết bị dùng để kết nối các đoạn mạng với nhau theo mô hình mạng hình sao (star). Theo mô hình này, switch đóng vai trò là thiết bị trung tâm, tất cả các máy tính đều được nối về đây.
- Switch nhận tín hiệu vật lý, chuyển đổi thành dữ liệu, từ một cổng, kiểm tra địa chỉ đích rồi gửi tới một cổng tương ứng.
**c.Hub**
- Trong Mạng, Hub là điểm kết nối chung cho các thiết bị được kết nối với mạng. Hub chứa nhiều cổng và được sử dụng để kết nối các phân đoạn của LAN
-  Với một Hub, khi thông tin vào từ một cổng và sẽ được đưa đến tất cả các cổng khác.
 ## 8.Describe function and operation of firewall and gateway 
- Firewall:Tường lửa là hệ thống bảo mật mạng được sử dụng để bảo vệ mạng máy tính khỏi bị truy cập trái phép. Nó ngăn chặn truy cập độc hại từ bên ngoài vào mạng máy tính. Tường lửa cũng có thể được xây dựng để cấp quyền truy cập hạn chế cho người dùng bên ngoài.
 ![Atom](https://upload.wikimedia.org/wikipedia/commons/5/5b/Firewall.png ) ***Tường lửa làm nhiệm vụ bảo vệ***




 




