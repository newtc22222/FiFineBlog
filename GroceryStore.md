# Ứng dụng Cửa hàng tiện lợi
## Ý tưởng của ứng dụng
Ứng dụng dựa trên hoạt động từ các cửa hàng bán lẻ xung quanh chúng ta, đó có thể là các quầy bán thức ăn nhanh, shop quần áo, mĩ phẩm. Trong lần thực hiện dự án này,
tôi lựa chọn việc xây dựng ứng dụng dựa trên các shop bán hàng khá phổ biến với lượng hàng hóa vô cùng đa dạng như Family Mark, MiniStop,... <br>
Ứng dụng tập trung vào khả năng kiểm soát hàng hóa bên trong cửa hàng, giữa việc quản lý các mặt hàng, nhập và bán, cũng như thống kê doanh thu theo chu kỳ. <br>

> Bên cạnh đó, ứng dụng cũng sẽ đề cập đến việc kiểm soát các nhân viên làm việc cho cửa hàng dành cho chủ cửa hàng.
> Việc liên lạc với nhân viên trực tuyến đã trở nên khá phổ biến. Đây sẽ là phần mở rộng cho ứng dụng.

## Khâu thiết kế
Phần quan trọng đối với mỗi dự án luôn là việc xây dựng những cấu trúc đầu tiên, việc định hình được cấu trúc của một chương trình sẽ giúp cho chúng ta hiểu rõ các vấn đề
cần thiết bên trong, tăng tốc độ code và giảm thiểu những sai sót về cấu trúc cũng như logic trong quá trình hoàn thành.
Trong bài viết này, tôi sẽ đề cập đến các lược đồ cơ bản như là **Use-case**, **Activity diagram** và **ER diagram**
### Use-case
Đây là lược đồ mang tính quyết định đến sự khái quát về các tính năng và tác nhân cơ bản bên trong chương trình. <br> <br>
![Lược đồ Use-case](https://lh3.googleusercontent.com/pw/AM-JKLXRfWL41xF0Lo4X3muuIhuMj9d4sT6D9T0vHaYJd4uKEIFgI5mt8td7iTDwVXKcuaR_6ycyWxGhZVIHK7-62nQ58C0i_hKa6Gv2NZrZRpmeHyDUL3ByicrPggua0xXmy_WQ1FbgxEfp4y3qJKJ26MKI=s831-no?authuser=0)
### Activity diagram
Lược đồ hoạt động sẽ giúp bạn định hình các hoạt động liên quan đến hệ thống và tác động của nó trong quá trình làm việc. <br>
Các **Activity diagram** sẽ được tạo nên dựa trên các **Use-case** đã đề cập trước đó. <br> <br>
![Lược đồ hoạt động đăng nhập](https://lh3.googleusercontent.com/TuSD-HxxgWRrm7GWLfRFip0HI9GRALdI8DrdTLRVJr-HADKyrt86ysI7ZFCBBzq_-JN2Jdoe-nrjt-Op2VDBWaS7W1mEIIEVUS5xM8luzuT-XyIfz6vOZ2YKl9qMALqnlN_qxTU-yRNxVueMqWf5YzvUOCyUZh4MLQU1HZMj0dbiisquG8DxDjiOAXzxd_JnfSWoLbR1navKhqLrBVOnN8_USLuGb8N0OJssz6p3sW86xgvz9MtaWdr2YCeEPICeFWbbfhnIZsRBZScc-1eqMXzaTBWpdXEQFTfVKEdzGGCHQQbGMFRU_mue3fQO0LgYRQxDuVstPcjdn9kFKb9a9HKgpvpx7fF2-sUQE9frqAqb4FnuVENt5E8Ei2DUuu8veocmLR1tb7uo6WsMDQcu_5KePo9H5mjABN__Pd1fiMwAUASbHDSOa1eNQsx-QoDJDQR9rTX2yQ0hoJunvzT_Ze_UzU9tHoaDuLT0ARyQRFcRfmojo-2-YW3KW2zDXLgsbvQYN1x4Gr_-BmPz-Vqd8SSQ_8QTUz-Tin9pVA6EdaNJ3SFROOHWDBR565qz1Hdbg5gsVPdCKIQhwvMxEN3LC4v4FqEv-Orr1UouMleM8Lhj18Lt-1z0k_JLvb5_3Zj59x9w9PWLgC5Pf34iglY3PGU5-Lg4_bq1r9qAL7SUT0gJg8Nsn4dTOCeiY2L46WE8EYV6vISzCPGjSku0JOAMugZ2=w521-h236-no?authuser=0) <br>
_Activity diagram cho Use-case đăng nhập_
### ER Diagram
Trước khi làm đến lược đồ này, chúng ta đã khái quát được các chức năng và hoạt động bên trong hệ thống, phần còn lại là hình dung được các thực thể sẽ hoạt động như thế nào
phía bên trong hệ thống. Đây chính là lúc tạo ra ER diagram để có thể hình dung cụ thể hơn mức độ tương tác giữa các thực thể,
nghiên cứu về thông tin của từng thực thể và phân tích chi tiết các hành động để tiến hành thiết lập cơ sở dữ liệu. <br> <br>
![Lược đồ ER](https://lh3.googleusercontent.com/uvgSU8_IsJZWZf4CbF_frFP9vIddYu2rX7_cobnmcRbkDKW3IYpKi6dtzcHYi7hcQGds4WDIiyMPSfMzmmp73-JYOFujgumixiyYI2qtYixqOAjU33lR-IHnOKjwDYKbxDIG3mD2X3VeI4R9_OGRiVmmZUYmMACBFy3WjE33_7cWuGlqaQlkp0g7Fknz98Qo1qde0R7gVk568dxK36luw6VQQDKfl2LYwiqpZjkmIkF66q_sgJ0PT2JOMI1H5s3_SkYXOAyFo4E0dg1QGpm_E82xcJIUyivNXNMGi0B2vU-31qO4htPq2QRRiaIh01E5vbWIFMFRsZ2a0febgjAn3NVg_pQMu0_kru2Lf0TLhb0pD4euBZiyoO4MyYC0TYv4E9zX9Fa7FVA7MbYN6NKpXA0koi410Pqq-Mr2C5hQcDnRmTWzJFherLftdwcJakl9yVwu2K5Y4MwBM-X_wptatJBwk7YLx-DUfHxfDgTfbhx_-fEdeqRQ_XSA8Chj-Z7sJf9bU58YFITfUnIIvgxSyz4jM7KaZNCIa8A6q3BJqWdvdTSWJX4vjZQzW8mSMebGS5TnvPNkBvEO2FloOUbDKZ4D89_FrLdOVfSFmcfcYNe_TqFTK_brf9g0-K4bElq-jpGp1mf3CtR6kqfn53FaugDESNbAnV02kA5JeAgyQMVnw-vZBWp5Pzc6k-yVtGCyIrLiDLgg8PznNJT7SCTGQvZP=w1301-h916-no?authuser=0)
## Khâu thực hiện
### Tiến hành thiết lập cơ sở dữ liệu
Trong ứng dụng này, tôi sử dụng Hệ quản trị cơ sở dữ liệu là **SQL Server** vì ứng dụng chính sẽ được viết trên IDE **Microsoft Visual Studio 2019**
1. Các bảng bên trong cơ sở dữ liệu
2. Tạo các Trigger
3. Các thủ tục (Store Procedure)
4. Các hàm (Function)

### Xây dựng giao diện của chương trình
Ứng dụng được thiết kế bằng các công cụ cơ bản của **Windows Form** kết hợp giữa các _Form_ và _User Control_

## Code tham khảo
``` markdown
#Using System

public static void main(string[] args){
  Application.Start(new Program());
}
```

[Về trang chủ](index.md)
