Giả định: thiết kế một hệ thống mạng của một công ty có 50 nhân viên, các nhân viên có thể truy cập internet làm việc, có một website quảng bá sản phẩm đặt phía trong mạng nội bộ của Công ty.
- Chia 50pc thành 3 VLAN: 10, 20, 30
- Đổi VLAN NATIVE từ 1 thành VLAN 99, mode trunk
- Tạo 1 VLAN để đặt tất cả các Server cần thiết
- Kết nối lại với nhau dùng Trunk và Static Router
- Cấu hình để tất cả các nhân viên có thể truy cập Internet (Router_ISP)
- Đặt 1 tường lửa ASA bên ngoài Router_Biên để kiểm soát các truy cập từ bên ngoài vào hệ thống mạng
- Cấu hình cho tất cả các nhân viên đều truy cập được website quảng bá
- Cấu hình NAT (Router_Biên) để pub web ra bên ngoài Internet, NAT 1:1
- Firewall ASA, hoặc ACLs
- VNP để có thể từ xa truy cập vào hệ thống của công ty

