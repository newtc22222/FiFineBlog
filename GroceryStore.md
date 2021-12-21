# Ứng dụng cửa hàng tiện lợi
## Khâu thiết kế
Phần quan trọng không thể thiếu với mỗi ứng dụng cơ bản luôn là việc xây dựng những cấu trúc đầu tiên, 
ở đây tôi sẽ nói về các lược đồ cơ bản như là **Use-case** và **Activity diagram**
### Use-case
Đây là lược đồ mang tính quyết định đến sự hình dung về các tính năng và tác nhân cơ bản bên trong chương trình. <br>
![Lược đồ Use-case](https://user-images.githubusercontent.com/64945902/146870335-e6ccfbe0-d0cb-4f6a-814b-29b082e0e399.png)
### Activity diagram
Lược đồ hoạt động sẽ giúp bạn định hình các hoạt động liên quan đến hệ thống và tác động của nó trong quá trình làm việc.
### ER Diagram
`Đang cập nhật`
## Khâu thực hiện
### Tiến hành thiết lập cơ sở dữ liệu
Trong ứng dụng này, tôi sử dụng Hệ quản trị cơ sở dữ liệu là **SQL Server** vì ứng dụng chính sẽ được viết trên IDE **Microsoft Visual Studio 2019**
1. Các bảng bên trong cơ sở dữ liệu
2. Các thủ tục (store procedure)
3. Các hàm (function)
### Xây dựng giao diện của chương trình
Ứng dụng được thiết kế bằng các công cụ cơ bản của **Windows Form** kết hợp giữa các _Form_ và _User Control_

## Code tham khảo
``` markdown
#Using System

public static void main(string[] args){
  Application.Start(new Program());
}
```
