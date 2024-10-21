## Ứng dụng quản lý thông tin và giao dịch trong ngân hàng ở mức phân tán (28/05/2024).
### Tổng Quan về Các điều kiện để đạt được sự phân tán của một ứng dụng :
 1. Phân Tán về mặt vị trí các Server 
 2. Phân tán về mặt dữ liệu
 3. Phân Quyền về mặt chức năng 
 4 . Sử dụng được Giao Tác Phân Tán
 5. Sử dụng được Stored Procedures đã cài sẵn ở SQL
 6 .Hiển thị được các trigger tương ứng đã cài ở SQL 
## Demo
## Trang đăng nhập chung với tất cả Server.
![image](https://github.com/user-attachments/assets/4349c096-2d5e-4184-a8bf-2a085bf4a851)
## Đăng nhập vào Server Hồ Chí Minh nếu nó đang tắt ở Radmin ( ứng với trường hợp server ở ngân hàng HCM bị lỗi hoặc không hoạt động ) -> phân tán về mặt vị trí Server.
![image](https://github.com/user-attachments/assets/ac45c33e-a9c9-4cdb-97dc-dc31a6e74172)

## Đăng nhập vào trụ sở tổng, nó hiển thị toàn bộ dữ liệu của các Server khác. ( Server tổng hoặc Server khác vẫn không bị ảnh hưởng dù Server HCM không hoạt động.)
## Server tổng phân quyền về tính năng,mọi thông tin về phân mảnh sẽ không thể thay đổi, quản trị viên của Server tổng chỉ thay đổi thông tin nhân bản thôi( loại thẻ,....) -> Phân quyền về mặt người dùng, vị trí.

![image](https://github.com/user-attachments/assets/5d026cd6-13fd-4cfc-85cf-ace1f2b1d80e)

## Đăng nhập vào Server Đà Nẵng nếu nó hoạt động, nó chỉ hiển thị được dữ liệu của Server nó thôi -> Phân tán về mặt dữ liệu.

![image](https://github.com/user-attachments/assets/5e443570-8bf3-45ef-8566-842dba7c1bed)
## Giao diện quản lý nhân viên của Server Đà Nẵng.
![image](https://github.com/user-attachments/assets/9d500071-cc6d-4749-b5b6-783741dce1e4)

## Phân quyền cho Quản trị viên của Server con ( chỉ quản lý thông tin về nhân viên, chi nhánh, còn lại thì không được)
![image](https://github.com/user-attachments/assets/2c9068fc-89d0-4928-9e1f-e60ce5bc0be1)

## Phân quyền cho Giao dịch viên của Server con( ngược lại so với quản trị viên )

![image](https://github.com/user-attachments/assets/2575a425-50b3-45ed-96bb-0155e06d7455)

## Hiển thị Trigger từ DBMS.
![image](https://github.com/user-attachments/assets/bc527b39-b751-4987-bfa8-5ec63a3f9612)


## Thực hiện Giao tác phân tán ( Giao dịch giữa các trụ sở ngân hàng các nhau, Server khác) -> Tính năng quan trọng nhất -> Đạt được điều kiện quan trọng nhất của một App Phân tán.
![image](https://github.com/user-attachments/assets/1141f1cf-1d29-46b9-ba23-04b4fed77efe)

## Sử dụng được Store Procedures từ DBMS. -> Các SP như Thống kê dữ liệu ở trang Home, Chuyển/ Rút tiền và Giao dịch.
![image](https://github.com/user-attachments/assets/716aad91-842f-43c1-9503-a22a578ce2f1)






