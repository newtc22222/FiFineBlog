# Ứng dụng Cửa hàng tiện lợi
## Ý tưởng của ứng dụng
Ứng dụng dựa trên hoạt động từ các cửa hàng bán lẻ xung quanh chúng ta, đó có thể là các quầy bán thức ăn nhanh, shop quần áo, mĩ phẩm. Trong lần thực hiện dự án này,
tôi lựa chọn việc xây dựng ứng dụng dựa trên các shop bán hàng khá phổ biến với lượng hàng hóa vô cùng đa dạng như Family Mark, MiniStop,... <br>
Ứng dụng tập trung vào khả năng kiểm soát hàng hóa bên trong cửa hàng, giữa việc quản lý các mặt hàng, nhập và bán, cũng như thống kê doanh thu theo chu kỳ. <br>

> Bên cạnh đó, ứng dụng cũng sẽ đề cập đến việc kiểm soát các nhân viên làm việc cho cửa hàng dành cho chủ cửa hàng.
> Việc liên lạc với nhân viên trực tuyến đã trở nên khá phổ biến. Đây sẽ là phần mở rộng cho ứng dụng.

## Khâu thiết kế
Phần quan trọng đối với mỗi dự án luôn là việc xây dựng những cấu trúc đầu tiên, việc định hình được cấu trúc của một chương trình sẽ giúp cho chúng ta hiểu rõ các vấn đề
cần thiết bên trong, tăng tốc độ code và giảm thiểu những sai sót về cấu trúc cũng như logic trong quá trình hoàn thành. <br>  
Trong bài viết này, tôi sẽ đề cập đến các lược đồ cơ bản như là **Use-case**, **Activity diagram** và **ER diagram**
### Use-case
Đây là lược đồ mang tính quyết định đến sự khái quát về các tính năng và tác nhân cơ bản bên trong chương trình. <br>
![Lược đồ Use-case](https://lh3.googleusercontent.com/pw/AM-JKLXRfWL41xF0Lo4X3muuIhuMj9d4sT6D9T0vHaYJd4uKEIFgI5mt8td7iTDwVXKcuaR_6ycyWxGhZVIHK7-62nQ58C0i_hKa6Gv2NZrZRpmeHyDUL3ByicrPggua0xXmy_WQ1FbgxEfp4y3qJKJ26MKI=s831-no?authuser=0)
### Activity diagram
Lược đồ hoạt động sẽ giúp bạn định hình các hoạt động liên quan đến hệ thống và tác động của nó trong quá trình làm việc. <br>
Các **Activity diagram** sẽ được tạo nên dựa trên các **Use-case** đã đề cập trước đó. <br>
![Lược đồ hoạt động đăng nhập](https://lh3.googleusercontent.com/7LyuEDuXprlvm-yQOz_1Ez9M67THXhKGXulo8WMbY4l8t2HSBbE10DOOi3U6uxc0UOFpJVoFwASySTJSRDNp-XescQvvs4jrxY5SbU89y5UYd1uK3bHD_OJUEmhLTkiw3EfMYHl89YfX0oQRgxJkIQv_ceFUlpzOAxSj-oWZNxZuruhpXk9S_4NV_ujtL5BJvsWN6i-lZdE8SovdmaNqgMAFaVdkdNEpyzcCC0S4rP6DxB6wDmU7lll3qn_LWz-myhuh0iO_W3ByytzIFRSDXEfb2-a44Ia1wlPMbEvek0C37LOSTystZMnP6sHN-yt7AMVNFC-VcgXeTyZ1_i3qhpAvRQbX7NCzKvOt6eYXPxvgrKjGv06TrTFIsACB0lTWkhcFyUkDTJzQS1P4G90AMwvWZQUw6I-ORPD_9cxUcsdTMCstJMC5GVWQpYZ013GemYV9etIM5WmqKeOPSnJY7R5p4cHIhFtH3h0g6y6VcRcrzfl7qBRkqFKJSEIY4mzeG5EfEaIJJCP9IC5VHeGbrUeE-oFW6Skhy8o3_rV3yVSVOW2mUrh5t4wlBTaKSawppHtX_QYAPJCLLmn3dOCmT_FPgKfT8PmB1yrq5_8I0sOH2ipr7KT29Ys6y8cBRZjuwQHia70OMZn7EJstSuhTa0npgdeXnlrSwO3vhfAzddRLOZt2g6W3ECZ_pEy3olhiamX1NCmRy5z7m0WIvF-vXDv2=w521-h236-no?authuser=0) <br>
_Activity diagram cho Use-case đăng nhập_
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
