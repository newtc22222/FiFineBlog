# Ứng dụng Cửa hàng tiện lợi - P1: Phân tích và mô hình hóa
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
![Lược đồ hoạt động đăng nhập](https://lh3.googleusercontent.com/gWl1lDhD1FUre_rIt6kY5vvUZSSKhwW5GS6bdWPAKIyYPl-IirPim5uPWtNuBrCYIq9yM5gdQB7sfb6OW-YYJfGNKjSnm27H5dZc7K0Xiu7G2md-xvzOUz9mdWVNzigVDsG1j2p0oI3T9yihPmPCcw4RcU2bRT6f9tUtuc0URvsBDn-KHH0z4HPPz8H8r8eQZ8_hkKQ5VBPqNl8r5XRD0a22xNX8ceCL4ZHgDbOw9HLJjIDJRhUTYo3IFD_935tfsCWcKYM15qlgQJVZqS-SnjNVj3zLoX7SqwZttX_OjvYn0bq-4ESn5J2IklRVYtqlLKnldDBBeG70p8syuEU4Kg0q03nRv-NYzjIQAka--SWI0ERfsBoryT5u_Ar0qgB2CiMj4LrMO-lPpef8_2FPcESAh1tq6DatTLH4Ox_x3ZpY8PUBGvLf8UG-ZYEKYAlqKu2sByjb9NNOjE8cyIWsNcS6Rf4KmRvJK5Vc9IkE1ztgWPVED6ajne1eDA_VBAXYG6fJOO6Od5meyDr08e5Hf-toJig-J3YbEHiCaqCNKWkrKssLg-eQO01nw3p8QJY1XDXaIdE59ADmiT2slWBcxhBL4C6uNTEXYUyNTuzPLWwK_knjpoLUhY2yC-EOvDAgJ1t7enxmNkH3zHDk8_rBBBRBE2dVNLZK_9Gl5XcSMaeyTwHckXJ2j92K1mkJ1ElYK1jRGYfdXQ06M2UglgpkT1km=w656-h296-no?authuser=0) <br>
_Activity diagram cho Use-case đăng nhập_ <br><br>
![Lược đồ hoạt động tương tác dữ liệu](https://lh3.googleusercontent.com/Q7my58zfNOq755jErSLC7smiGcmuFztsfV3wuTHvVy3Zyzgu6Y72MD7sayIGW3NQgu0dnd1WMzANEZI9bEvM1Qwk86VZkM2Ge_kd6zSdKbOF8WYMxYjVxzMFFtbOjffg46805GsOmTbKpIreFdVwckr9q-kXT2SnfeXRAq4kDWqba9Wx1RyeHDEn1FQ5KGSwYZThfKpaQDOdxXJt8yVJ5g_e0WYieO6bCPow745rfbtcz5wZVxfy2d0QVAPNwuuTMBXrCbXegcfSAL_hnGIGyMdakyeIY80gwEOK2BUw0GkJEfylc024lotQLEYTgsuWoB61RLNJNrQVlj-0jYbDV1FiW4Rj42SUpxkOP8DTXoQHgXjRRnaiBh9nr8A2kozDcK8unxt2L3P8QBzCiByjQTEvcIqCzYpghfs0MZOS9YnvZYCcdizAtq7DuOyt8jV33lNHT1V2tz5Hx3RxqIYgSFIJo79YNcAlXJXlhMgPmEYbReHYnvXd8_U2Y-fH5n5uNaV0Bd_mAe5J07nQT5eUQCQxb367oY2jsLN06XUWjnkUB7uTcffqCSC_dwg570HLuuuzrAog_-jDAeL51xRt1s6VCpQRdmgrNU2M2FcNb1AWMCQm6sGVMpvTujabohrToqhuzov9t6eFoYKTJDZZhP1XwaBpniPi3hyaMbjGlqAgcgUiuwmyKVYKd5Hgi9zPBpQCW_IQpOEoCMVcBO3Q6MOv=w680-h519-no?authuser=0) <br>
_Activity diagram cho Use-case thêm, cập nhật, xóa_ <br><br>
![Lược đồ hoạt động bán hàng](https://lh3.googleusercontent.com/4PF64RPxhk8y95nWnfz4qYDuIT0Z5I56wqNa4DElA-_OZNbWN-oWDDNqGSuYDlZuEjDBuRrb-2UBEu4hbmyywSn7jU9bSC3qpbklO2o0u46iA8m23wtYyeXnHLtuUaKZsCk06hI5lcipgPDhL5iOoLnYc7GQZLOHQEyuAbTEH_xu_QebnLJcP5uY71rR2emfpKVHwp2sY9V8r4NdJxw2_sOUdk3Mis_7oq7SEPC6V4ldzaCHAspqiwwTA1ajEOnpHOfMKMH_njAYJNCqYssHhVxTkwZDRClTsYumYeWYLF2Y_N2K2Uq-88Z6TjDWKYWwlA1TDmSuzRj7C6zPq3Y5vX0bWtQOJ03Fo-05uk1CnQPXbHbTikBw4LV0uWw3M00iHfliyxEmY7BWlyqhYJ2BsgDUCUCDJz7cBTuVHrcc6OnnLClATg7sb3tYghhD5-i8U6NTGrFH74QL8sEUzsWwTgV3W8OnzFt4aj9wDErI6FmBM8FP0CGFViQXWKeOCkbS4se0UijqpjGU2R_Thh971r8quIwARsAU2XOdJ5PGjZ1u1OU94NArXGTxKEH9IkHUbN49QmW8gRZScg-SVg5_WaOGA8ty1o41MKWSbMGgnY71jb6kIoLEB8wr0LrF0_XFxbgcNldEmxUWhpd40pPqoMYVeypqj4Kd6y12wEH5UwCoOtIXOd4NOzzR-PA1Qz1k15kRzuDsvel4ZlnqjLscFj78=w1271-h383-no?authuser=0) <br>
_Activity diagram cho Use-case bán hàng_<br><br>
![Lược đồ hoạt động nhập hàng](https://lh3.googleusercontent.com/a-EHqP5vXckCYXrZQ-0NZ9L2cacFCPz8q4cYyRu4gg3b4oveO9_RLVzbJgPcDC-LtgNg0-yElO9WZacKfS-dWOy3pSn0xddXqsHnj1RDoElxuCX5q9WVhu9ns3POIV5E9z_VjCTMNrM2bNCg4XrUvFwNc7aykG4Fr_Uc0wJ2GMH-VghUFM_xU8Konj7wBqOskXKg4npTfBYxIxwsmMdZFwgBk6gzowowY-uxIuUfW-fqsct0s-MMHwTc-Bsaxsy9Sps4Xw2BwPnnBvtkf7MPdi3CpUGjBQC_llLx4YjOgHvNnjmobQkOGE9m1mskalt11j7xeC9eaQocwNfhiU9fT14LGYFLLEZ2X0mdotLU1ddsT-LdjqabQj6eSeWNHdoBjkVfENqysyY260Is7xcQ4YAO6D1yz6z2BIEfvB1KemQsz0eh8hQgsMcx24Rvfc-22145_y3j6cQkADUEa_oyfKg2ga00G5uc_Cy9w405rPHmwpO_dCHnolYPRs6wFUDQ-XaynDS6RcQHK6JKg8VFQ8j5B-kMpn-ek4x5sukCVs6DwVFobyyt_Ptw6aIJI6YtxYHpA3gpmArtrZxGMyBSxpZzy0ZGuCjSxgPOT3_x72cRodZZPSgWX07mA5x5eF6HULBo3paRKPrRCGOWasYe5GinLHUqOeeWwuKPUVgt7PDeWXTd0YK--DnAqbmKVfSSGxY_5BxqQf9_9mlx7k-M4Wcb=w1207-h306-no?authuser=0) <br>
_Activity diagram cho Use-case nhập hàng_ <br><br>
![Lược đồ hoạt động thống kê](https://lh3.googleusercontent.com/Vn3Y69agADAzaIlK4Cc_ayDbZyuICMs7hGSS7TIEq6i_lsdmhfiXg-JO3RFO9p0cn_dLlA47DEEpAcOJQqADWnE9RzdvBYtN5twSOEPe0LqdRu-_PG-7T7vwHm6318va0MC7t698TLYLaI86RA9p1ONPsYs1qcrI8Epda6QEy-onwcOuekoho9yBoSxEG8pAssF4nECdNnlXnFiPsas9LIpOrR_QGHgbq2aqHoOQHyd9Y4Gm8L4LuXCGEQXlXn0ZpGFBObSg3nX8yXmipw_8JNabIRh2cgLRkE_8K2Ld9HqsO24LhF7G8J-6ktycj0J-26rlSF2z5KAAo-iluQvPlQgEnXK8E1LbGdmWSEYyuDTgpftm0WThZ7uWcOjmrF-1F7u-LYN7Gbed3TpqAkj8BTR2jgjk1phBsGEAAo62ssgLyE--xqwmw-NSl_xpjIQWMrgsBRSn4Yl4a7wSxF72eJuXgbUtVfFQDZp9cRlSrwwJBLRibx7XRGbfwtQlUKod4QdYeeJysoAYi8r-FaX6DV-iV0o72TPYEYh0qMP2caUtRmwNec2y2zKGheH7Q2v7Aj-ZhP_SRqkmc6QeMi5QBvnexKBajcF0To4qN5yIS_y8GufCuCbJY8v-2C3phvXa6f-ulOhokXcSQEZ7tPxNWBdiaPxO57ydVGAa6dbHGGrsmluXdWUX2OZ1iOVHlSjD3d2r7s_UFkvpt31CpydCfLXG=w1147-h217-no?authuser=0) <br>
_Activity diagram cho Use-case thống kê_ <br>
### ER Diagram
Trước khi làm đến lược đồ này, chúng ta đã khái quát được các chức năng và hoạt động bên trong hệ thống, phần còn lại là hình dung được các thực thể sẽ hoạt động như thế nào
phía bên trong hệ thống. Đây chính là lúc tạo ra ER diagram để có thể hình dung cụ thể hơn mức độ tương tác giữa các thực thể,
nghiên cứu về thông tin của từng thực thể và phân tích chi tiết các hành động để tiến hành thiết lập cơ sở dữ liệu. <br> <br>
![Lược đồ ER](https://lh3.googleusercontent.com/uvgSU8_IsJZWZf4CbF_frFP9vIddYu2rX7_cobnmcRbkDKW3IYpKi6dtzcHYi7hcQGds4WDIiyMPSfMzmmp73-JYOFujgumixiyYI2qtYixqOAjU33lR-IHnOKjwDYKbxDIG3mD2X3VeI4R9_OGRiVmmZUYmMACBFy3WjE33_7cWuGlqaQlkp0g7Fknz98Qo1qde0R7gVk568dxK36luw6VQQDKfl2LYwiqpZjkmIkF66q_sgJ0PT2JOMI1H5s3_SkYXOAyFo4E0dg1QGpm_E82xcJIUyivNXNMGi0B2vU-31qO4htPq2QRRiaIh01E5vbWIFMFRsZ2a0febgjAn3NVg_pQMu0_kru2Lf0TLhb0pD4euBZiyoO4MyYC0TYv4E9zX9Fa7FVA7MbYN6NKpXA0koi410Pqq-Mr2C5hQcDnRmTWzJFherLftdwcJakl9yVwu2K5Y4MwBM-X_wptatJBwk7YLx-DUfHxfDgTfbhx_-fEdeqRQ_XSA8Chj-Z7sJf9bU58YFITfUnIIvgxSyz4jM7KaZNCIa8A6q3BJqWdvdTSWJX4vjZQzW8mSMebGS5TnvPNkBvEO2FloOUbDKZ4D89_FrLdOVfSFmcfcYNe_TqFTK_brf9g0-K4bElq-jpGp1mf3CtR6kqfn53FaugDESNbAnV02kA5JeAgyQMVnw-vZBWp5Pzc6k-yVtGCyIrLiDLgg8PznNJT7SCTGQvZP=w1301-h916-no?authuser=0)

[P2: Triển khai cơ sở dữ liệu](GroceryStore/GroceryStore2.md) <br>
[P3: Thiết kế giao diện người dùng](GroceryStore/GroceryStore3.md) <br>
[P4: Lập trình kết nối và chức năng](GroceryStore/GroceryStore4.md) <br>
[Về trang chủ](index.md)
