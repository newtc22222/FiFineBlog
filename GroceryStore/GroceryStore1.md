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
![Lược đồ hoạt động đăng nhập](https://lh3.googleusercontent.com/qKaJrEydcbSbWC7KdBzfdefWWxpogKlTU8NkK9v_VnQKWRNNFCql-DbyST6LrUrJMx8eIBf5nz0OZiy7_ioOBX5qQdVF282TJ8o6Q84A-LrAMPbZLt39M4yKmPcLYpQwnt034omD91WBbaUc6TjK8_SUsBapz4dac_IakdUgktl21dKVnZK3vgl2GFt0mj1O28sP6ZJe8hOFmSlGhADWFHpNnwPznLCwJR8eS8acX17joDFv__WcvOjGQkYZ3FixhtQoV274mDS2tCbItEn6feItgRC3svgSFFbTut2CiH_sqQx5w1E-UPjFSRH4oWUNriuQYITW_-qwxwya-96xAYUzqxErY1x2CSwm9g9zs6Gg6BxnrSs0-R0Z-8sx9UAAdidinSWH09XHLyejuRaIFJEIH1szpd0AYidxrjhuGNAac6CVj05X2aZoO_jkw86JTA3xlsBPlF1k6OehFVC7VqjZQ7-Jphjqh1pWHoNaTbEECBg_YLRipXuOeduRjq2sm7rBHkYaJ0KlZPsBCJc-dTiSXrbziO3AQlmfllb9zdggJZuKSyfokFe6UI_X5SW-YJ_uEd9EBy0OvVEljUvlFmn-ksMmqoSld2em95GN9HTCl73o1tYapwrOs-DA-a-jYybDUNWlJeZSP5t-t8rDxKUbqqZVeayzIZtJD3bthHbBVy-4KZsH6ucKrWhdi9_clDz7yer_jGYkcTABJVrfxxCS=w656-h296-no?authuser=0) <br>
_Activity diagram cho Use-case đăng nhập_ <br><br>
![Lược đồ hoạt động tương tác dữ liệu](https://lh3.googleusercontent.com/HT9s5WGq2Bac59YsC3eNnoLIHgyBmuXfbmMaJcqA80BkcsLqiog0ShpzGbz6KGOYHc068jmajke0WH2JD3Qty6YUIaikFHCZxlN_PUzAhRJVXCEJhE8m90wzV3r1rY0wKSSnBIoXDAbPa72aAqxquA3dnWN5m_oNDmEpE20qzlnTbF4cDxiDBH9G8ZljESWw8uPVZf5nC40sbXEd7U6nhPmPDw4XkA7IdYRQG26ilyE03j9Y_wZstZMtrLSJmAsdy4sg7O5RiMUs3qB7n1X0nTRYi8KfFFpI-acyJhDQgWBBh-T4mhbbjAZfeouPgWJ6ys-qKuDCn-dCMQg8C5s10RC0nqSvQZtf7Py6jaUULz7HLmw-DyF7fpzm0SA8Xh_G8VRzqrrqBgJ1SUnWwPnpaCJQuYIpqcDisyV4tRPc6-zoHIQadzVWNE18M-6mbmd8ZCCF3aslZQq3LPEAWKV9uevaupLoBEs9OU8IJ34CJex6KzGRZaKoDBPzV100JKHMZpgdBtzeMbKBvWNAc1QsIxzCfaHHOzw0LXy6keoyrbOUG1AmB92lYnDBG41xqLXiHTg5e0iharVCicThcBJWS8QBMM1mZfgkTGG1Qg1APjgNj5m0h1i7tWGKNFCffsBKFzHq7dtTI7XUT-R6P35Fy4GrnMZ5hmvHIZClGgI8DCJytMRHYazX-iBqQV_SbtAVcsRINEeRFJAlt560owPJE08G=w680-h519-no?authuser=0) <br>
_Activity diagram cho Use-case thêm, cập nhật, xóa_ <br><br>
![Lược đồ hoạt động bán hàng](https://lh3.googleusercontent.com/-3tDKWox8tmBAatTYGrU_4TqXH3-_rgURNNfGm_rseL4eHQ_SJ5O93Tt8YfmYbfiUYLGKxHNDj47KkHin7SLU-g_6yNwU7wh1LTwXOd8g3ywB06TYZ6m1vceVhFf5dbEWcPdr4mOndoBnY9WJfcjArZCqjOcVlw4sPjy70kRQuZo2cKi7xY3nUdX1TSd9e1BVJsKL3JYkk8dvP4Og9prqS075ibCVSNBcyHw0y7y9nWXnXJux7GAYNutMp2iFM_GrzLFMrpMSbWL235XiT3A9gGC0xcLYwYYrzo2Fmjv6fu4lmxZLpLBZoxhGnPD9yX9oaC55Ed1Xy1zLIpdMYk_kSbLr01dtnQXzn02Ozvv9Ht6g3ALKDhS-8rTfKtcNVobixBAZhBRWoS_urP6hjnl_qVik3-46qk8QQp_bMTMerdTBjeCoN4TGjYbW16UlTv0tyE69Zvcufd-IamiTjan1wMS9iEmKfRB84YK0DTac-VwK1BGykYN9PPIpt9Qmrshsd18aBFsnPoxFVtkyOx-G55hQXhdwmlhh8xE3WAcyENjZkdiwPszUweZnkTNIiNdlq5nmkFG6OMrzVha8eW5JoZsknibgV_xCqV_Jc6AdObPUF5qy8qhBqC2o5N1oOcDnHstCmKbkD85HxAzqW48ijhUxN8Ru8pY11FZ4JFlvRP5Y-Bguy1PZUZC9JMm8WIoy4tB9Qgkb4THdZ_TEwLtaoZr=w1271-h383-no?authuser=0) <br>
_Activity diagram cho Use-case bán hàng_<br><br>
![Lược đồ hoạt động nhập hàng](https://lh3.googleusercontent.com/jdd5CXy6JcERLgcZb6dhU_y4bc7MAZU8BKk7WHPqukorkeXlbubaljq8RRvutUJwHjUX7PLDFH7wm9fcAy2OhJ7j-o_OMbc9mMZRQr7DumIpLGHDC5kbtNuoB3jAVs5jTKJkI8nobcjvbAVnBNKU2-Dn8pag2bkSWhTdyWcqstqTUZDJ-DY-orh3uc5ZcqGfHgXmlclFclfqqmUqt0Ht-b0pME5dRvNWK-rWNmbk7FIDSMc3za-cwddT_nalxZZm3GWkByz_4imgKmF-SGNoZXOyEiSQnsSJsRkPf_z3kDtRgNqVPKl5DaB40H241XwHG8B0nXlRDBTkLEWpR1pR0AtBAxaCYJO5thGn50J_XVsiPeLcnK6gguMjGRQpTtBl4C9oJTlBa5-rsQCAMrwTo-wJrJJ5Kjd6-KA-kDKLMnLojAN8dKgGqsEEKs_m2uI4YxsIT3MzVD-chRxxvQGRB5c_HMEDJDiJ-apNt8nFlMXaeZp_KQPDjJ3GreG7azhZppGMfCKe1BsfB_zWeMAinVUgBqeP_Wci5WkKXJaRiY4UR6P0lfExXJLPPs3dj4QUsOsEmkLvi7mdzT3ikaakzxM-Vj_rFdRYOjPl47mYP-P1DKCB9inWlWzJb-_KemxrAw21VqVOhQyAsc0IWdkYZEPmgpJsUjWhVJZKU9BWuz9segmTMDxPDs4RM8DVXSm7b8Y_KyvFuuVRosF1uQfmw8a8=w1207-h306-no?authuser=0) <br>
_Activity diagram cho Use-case nhập hàng_ <br><br>
![Lược đồ hoạt động thống kê](https://lh3.googleusercontent.com/yl-MIzdS3gaWk2NlmglBLuX_4TOp4UvwaHDi68NqLFEHysc7LdVR_dKLqC-dnjfrszEg9QXfSiPqLP-SOQIJid-5bLctDltNneZrUmoM-N8ycLIkCeAFLUTI60t5HCIrO-poGDgWgQ9W3b-Btiy8UgH6EbqGpwN3IbBmbu8HTLGTPA_HBYJE1uMYnwcW4HDXRULgnEQ_D7mDre1vOgdbRP8Xape07UyuSsJNj3bm_bjTlM29mFIt4nacfNiRP11rs142m_6srtRU8htKmfEnPmuXkMo0z3WlZ2dj7_ANZpVVrxlIvUQol9meSl1Eif4eTVzp4TBgwzHXLVq3wg4dcfpYUdm1TfrSIF8MmaBEEhnUVEFlCjI51ofJQ7TNojna0ND2aFwe-Nosimie0dp14tpVqx5a9_hE0SNfjNTZVY06Ty-1OZpr18mzAQOQ4CoDbuoz1NdXPtrRwPmbBpwIO-hOaJcqjD4nsv115JFqhb9GidQwdFe1I5UejOorOtBXgYdSDFr62EbIHvOsNYcSy3Ifdsie7OJ4dwtOys94iG4ShCtIdb7eekS6LLHFR0mFKIZByQVtWkRimxbhvQVuN84RlCmGxDc3yV8ZHArwxLIIHkj2rJjkZvothAU7cnoT62LDS3a33-OYR1pIW1CAtazjO6SGDCpMkknNZSgWPBuVwmG6Cy-l6ZVGVugziMVHaF4b4NvJrTreNGGtuVirCslT=w1147-h217-no?authuser=0) <br>
_Activity diagram cho Use-case thống kê_ <br>
### ER Diagram
Trước khi làm đến lược đồ này, chúng ta đã khái quát được các chức năng và hoạt động bên trong hệ thống, phần còn lại là hình dung được các thực thể sẽ hoạt động như thế nào
phía bên trong hệ thống. Đây chính là lúc tạo ra ER diagram để có thể hình dung cụ thể hơn mức độ tương tác giữa các thực thể,
nghiên cứu về thông tin của từng thực thể và phân tích chi tiết các hành động để tiến hành thiết lập cơ sở dữ liệu. <br> <br>
![Lược đồ ER](https://lh3.googleusercontent.com/yb9J9ueSidj0tOxYAc3SRMJwFznga2EAZSARb1Tr2DfTIR068fMbsQ7ntV5OUhCtQbN0_hwRW7MgxiIy8ztaCauorf2mWoCfwW8uGiCohTaU2-i5ua8GebmRFkkPO5YhzgAddBMqrCcUceLujnM_TXGSmSvjiP2r90MEMcd_ycj878iMB2LUQgp52KmYoKOj_Jyl8L2L7fLxaNhdD7Uy1AyWQcdmTwIOj6Els_WB6RJOavurrTU8Bx28e5N4d00JGckfHmLN47ljjeHzTliYNBEOscumnct2fr7x3EcGWqVsD2vkdMtidemokXqI02gOx2mxnM_UVIITIC94xhHq82bNTttuJjvRyOZJ5vJOT0VGVVffAek5ql8_kCuj01bKrEmhp81VdFSxVu7puhPsFUoFIiSsC8XhXRFcDJWhlHA7GI442ztTRLjoIVIn2nXeU7jYn2uNItG9UEPM1UUwlXuToEyYlkMuIP1Pi4xXBhi6iEn1sLIQNST9YI2MpOP4t5YEPNOWsl7E3dT3Gg5key6alQXF5AJhw0aL0AM7Gk-Xrxw5gEhSVORfSPH4lYY1cbhPlNvsi9pXMsv2r8g1bhVAiawYXUOYpH0-GvBB_cCWU5SM-rLYV_rQs5plETVA8GQrLFI8Q43gsEbDpR2wVmY4_ee7iR9jNKTsgJfmI_TYxz-y5UMGMnm1tjEaT8IxycJkRuNgiEtJW2G6YUaUAuYB=w1301-h916-no?authuser=0)

[P2: Triển khai cơ sở dữ liệu](GroceryStore2.md) <br>
[P3: Thiết kế giao diện người dùng](GroceryStore3.md) <br>
[P4: Lập trình kết nối và chức năng](GroceryStore4.md) <br>
[Về trang chủ](https://newtc22222.github.io/FiFineBlog/)
