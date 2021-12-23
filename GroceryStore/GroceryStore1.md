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
![Lược đồ hoạt động đăng nhập](https://lh3.googleusercontent.com/LyGsSakDN3cHBOEp69uU3SS7LgMufg6Zra7mycvOinV_Wjpm1qj2SktwhqzNn5gA5txVTb9O5cvZQ-0O0xrbBO2hhmYq_SpgplMpkqiXFbp5Iuf6tnaKX9Y7Dhs9auSTh4TPSNvq_Sgsq5n9tkRYfn7PWC01WExA8diZn2gD2v3JbHfDMhReJ57slm2jzLtumuaWW7LVq3vpVCmbhb_1ZE17YLiE_DucAbHJ_Kv-C4wzwc2a7vX2OtW6LXxzc8m5pzThsEDpbIHTztyTHjEVuqKapbe1bIo5wo50W0BkG19stjfAJ_nMzdPEl-3pXR43SINK5OLvseSnm_lnp9XDIy1NfHucKLj3QAgC0J5Ns11-q5kQvSTQe9ZYEXTjrONDLligz9GssSrdO9Q1u7dIx7VS9wXhTsJX4fJWmgzCmemjkkDfrHS_MOHo0uliurwIcx9lg1uvPXbnKmcXRMvSu9Tc-y5PxlMoaT2DskQt6ptZVO98kPaRdMeUixTggQYJZX6umm_QXzjSYwHtU4PgjNlXAWg_kJuDsnzE43ff6I2SlmGarqp5YyD-QYz_xmI0VzKg-m5LR0DDhqUJ9cpm38bzvhR2QUOwe9B3RuQCw2DNoOgPGOznJ1w743kmPDShBlcxtF6bOyqxpiipCqg3XgtzOZpgrvA0Dt0OyMWmgNWoW66HlkqprcgyiLGH4kZJqBdxK16vw4_TAHmz5UmD2G-j=w656-h296-no?authuser=0) <br>
_Activity diagram cho Use-case đăng nhập_ <br><br>
![Lược đồ hoạt động tương tác dữ liệu](https://lh3.googleusercontent.com/4RFbAGmcWWJowE-s9NDpodPvjxXNuHUSJX1DvbFNqRDPdwCQL326rHCtE7PywyTmjVRkY8llG0a8nKWFK_emQMJMDVvNh7SmYD1eHNDcIJTnb1ivHvIWoqGJ6AvjMJELfhF3g7VM3edfyj77PEnr5E4cRXosXZjiajY7TZ-aCxw9DEBoRbWTVCz0UoGktsePxebahJ2Z8KfXU_mxhR2_zRQ2K2Rh2j19BCZKwJj1lXuzkTxFH-TCYZMmmmWq2ibIH3y0pYBuRi3QZew7hcWGR5IUuhdt2hdhEEyh48YDRvwwKFHc0ZHkv5fdItLJGU3hRzBrAzc_MwZ5BXpBxCkjoqoUBcHbRDCm0Xvy2zLLHvenDtAWzL_cQZmJec0JNUJYY2VDjEblLfy7LtE9qhMFTTvaJwnug9aWUatmNsniMwAX7Ko4lZYsANtb9n4rGo6_1lxsD4J7Dn3Od0EtX5oxCHbXsh_O6MKs5Tzwf8i6Ykfx4m5mp80ndLtbdlUcx6nPWobQMC1eKWe2GEwLtsrdR9e-YLDKodlNU5U8JDLQYmHBAAU5QVUGFRBKJuYm4LPJ236zAqGeIwUsLQ0LqpXTnGxfQGJoEVGNIgr4LEo-Egb4z2JxyEL9Qhl9urDP5OjbOoyffPxvsoBUYMKGtvKWJgFii1MVuEKiZtYvo4tIgnEUb8itLuWQi2fmYTixAmUS49X29WIRkaM2D8-L21qIGWUT=w680-h519-no?authuser=0) <br>
_Activity diagram cho Use-case thêm, cập nhật, xóa_ <br><br>
![Lược đồ hoạt động bán hàng](https://lh3.googleusercontent.com/wBDB4Ff4SSJ4bTX9uBgLDwkdkxNWHT5BYhdhfmol7a0ovGsboH9-SjCOutgHyctFkB34wrNhGXSK1S9IXUeacDj8YtG2GIyrljYEJlk3XWYIQvswJYHhwcG6sMruFdiTYFOtQUWvkihkeMwmu1s2Tmz6frVOgS1waRKnEskL6MYGeDT4x7oDVni0PjLeBu03bhmP7EoZqnbxd4AmmubXjFOTCznhh2TzjKPaxCve2LeP5msLYjpPddDtmGbe5FTawoeqdRMS-iei3YgltfhMxZc8UQwqT3orn-sp9_zbfocZMLpwBmXqnfX5HR2CBARxAoJfbVDIjVVDvLfMtQX5l2h72hAe98LpRx41nqmwEGcNKY08c7HDlg8GoLY2VhrgzOX8h31S63O2bZdn-O_NRBZ7Ab9dZXcrewZ7dCAcohkUz-g1Nmhy5IT76dLKxDDWw6DXv8amiEbfPVuSEyDcJgKjjsfS8QYWbpJsCSySv_YTSiarIcUXJg_g4FDAxmv838FoQvehgTtUladviTslk8y1WbjdZD_1WwH5YURM1yyffl0xNBk9TbnKpzpe5PAzHNiJ6qalUFDpsbhSXAtwjRUfkcpf7wPgaNqNSvqeOgXjLUYmLhlQs7Tiz5hnkUgn890jNuns77DlQ8Gl07vdDz90RmP7vH3RIepvlJBZmKwC8G4aOALsIBLbdOkq2_buN-TuRc9OCidA1u3KasjjftBW=w1271-h383-no?authuser=0) <br>
_Activity diagram cho Use-case bán hàng_<br><br>
![Lược đồ hoạt động nhập hàng](https://lh3.googleusercontent.com/SYF2FvSrTXio4sY9AtvLXct0eKnJpLAKgRNGQ6NgrNeG8JzqUNU2n1x1m7vLBPI2PgZnHT5cfSmwGNi8U61Q1_S0ori33DQamQpE-kEkXr0GPVw7qIKe5GWifqs5VtUBVxKYwsUfJP-SxqjMNVqPbsYJZAREu_kORITsSLAVITiMOpr9srGheU4BjMzT5D6UpjCPYQEuwjcRI45dw3cXvbbulh3vpOra7se22DH_xeLI9SGeacIsXSloTtHKmZ7i8RmfePjetCG2LmkjwwPKC6ibYsWvxAmmFhw8dRLVDA3vjQhOhL1ILBTylJboy59JG-rMd7ZmQXA3zYaOAwUc96QFqJshFL7ewqC5uypTutdRxcluj6MwgUFchPxyHmZGa2mRVb9nuhHjm7mnej33KXOXLVC5X7exijy_m3rhqGwF9fXD-v0j2lmVprVGyqlzHPI0XsQwKfbjTrr_8lGD-xzHCbeECwKB5UXX2nqY3qi1fPiR_QONsPQe26Jm5-5kKabQAoq_P_jI6sWQkvapxGt1jVS5iLvAUudWVxq6xAvoAEeGE_dwWAHfmzNQZcW1XN7R6hnoh1msfTicNoPdJ2fqJWRbI6OUF3Ox-8OuD6nSVm86Qdi-2VkoB-HEL7aBKBsDryTQSm1mgA5MBWRfEly9CHUVBwFIQCixp1T5B3BE5OMHNpgWbmr55oecrMEB4_WXQVYor71SQjD-Cq-SeKkt=w1207-h306-no?authuser=0) <br>
_Activity diagram cho Use-case nhập hàng_ <br><br>
![Lược đồ hoạt động thống kê](https://lh3.googleusercontent.com/xv3U18k5Pi00XahG_v4T2zPiz1x8if89nlhMAA-t0zIVMxZ0Af4aKimDwN8siKTjSUP4Qo_zRKIOw-2ZA1x0lprz7QElgl1RRHkpJ2ZMTeCSMNTt9Z6R85W57iW_wf6CP8JP2AARFotTIbRDpjDyv6xAhc1ljQnWarIOPoIAyKUXxJ6CviwbnN58be5m2i3X16eUEMHMkl5igchhOk1F16ntmu82w_WKehIyvJ-vsrPYKs5y6tw0bMPeRQ5Hz4RjFg-OFcnXAkfr6BU3ZvsjArFaZQaMLwV4ZEwwBbk0ktLXYOVu1k2KhjUIcxcCNrkutVAEYRS4sFECuh-ZThZcUp0hTaG43nCjov2oWtoNDpRTsZ9Isw0xs6ytsfcwvW5q2U7zODK99qrk1ra1bXPP5MmIZKCdKCDOvji-sXwCTAf2-MgDgfUQGzDwVY-MwkaWodpm2rqG4f86nJgxXuKLPbI2etlBIa-KZ0dG4eF2FFgUn1JY6mO_Q_LgyhCU2WXLmVSJhTk-pMNYdQ72VXeP4x1j1UVd5np8UbmluV-5j1mGjERo6ZQ1ds27EE7CJDKknRf8WjG72A6gxQH4nIRekFY3u1M3WAXeaYDLCfT-4aWUHt8l94QPjyT2q7VxVP3ari8Pv4WHkBLHgkpNj6YnTj7EPsKsFMvooWnU9wQs5Dtnrix-BBaWUYdiWdvDLY2J175XzTd473Ehn1Sosf4V56hV=w1147-h217-no?authuser=0) <br>
_Activity diagram cho Use-case thống kê_ <br>
### ER Diagram
Trước khi làm đến lược đồ này, chúng ta đã khái quát được các chức năng và hoạt động bên trong hệ thống, phần còn lại là hình dung được các thực thể sẽ hoạt động như thế nào
phía bên trong hệ thống. Đây chính là lúc tạo ra ER diagram để có thể hình dung cụ thể hơn mức độ tương tác giữa các thực thể,
nghiên cứu về thông tin của từng thực thể và phân tích chi tiết các hành động để tiến hành thiết lập cơ sở dữ liệu. <br> <br>
![Lược đồ ER](https://lh3.googleusercontent.com/uvgSU8_IsJZWZf4CbF_frFP9vIddYu2rX7_cobnmcRbkDKW3IYpKi6dtzcHYi7hcQGds4WDIiyMPSfMzmmp73-JYOFujgumixiyYI2qtYixqOAjU33lR-IHnOKjwDYKbxDIG3mD2X3VeI4R9_OGRiVmmZUYmMACBFy3WjE33_7cWuGlqaQlkp0g7Fknz98Qo1qde0R7gVk568dxK36luw6VQQDKfl2LYwiqpZjkmIkF66q_sgJ0PT2JOMI1H5s3_SkYXOAyFo4E0dg1QGpm_E82xcJIUyivNXNMGi0B2vU-31qO4htPq2QRRiaIh01E5vbWIFMFRsZ2a0febgjAn3NVg_pQMu0_kru2Lf0TLhb0pD4euBZiyoO4MyYC0TYv4E9zX9Fa7FVA7MbYN6NKpXA0koi410Pqq-Mr2C5hQcDnRmTWzJFherLftdwcJakl9yVwu2K5Y4MwBM-X_wptatJBwk7YLx-DUfHxfDgTfbhx_-fEdeqRQ_XSA8Chj-Z7sJf9bU58YFITfUnIIvgxSyz4jM7KaZNCIa8A6q3BJqWdvdTSWJX4vjZQzW8mSMebGS5TnvPNkBvEO2FloOUbDKZ4D89_FrLdOVfSFmcfcYNe_TqFTK_brf9g0-K4bElq-jpGp1mf3CtR6kqfn53FaugDESNbAnV02kA5JeAgyQMVnw-vZBWp5Pzc6k-yVtGCyIrLiDLgg8PznNJT7SCTGQvZP=w1301-h916-no?authuser=0)

[P2: Triển khai cơ sở dữ liệu](GroceryStore2.md) <br>
[P3: Thiết kế giao diện người dùng](GroceryStore3.md) <br>
[P4: Lập trình kết nối và chức năng](GroceryStore4.md) <br>
[Về trang chủ](index.md)