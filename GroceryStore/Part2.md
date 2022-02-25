# Ứng dụng Cửa hàng tiện lợi - P2: Triển khai cơ sở dữ liệu
## Tiến hành thiết lập cơ sở dữ liệu
Trong ứng dụng này, tôi sử dụng Hệ quản trị cơ sở dữ liệu là **Microsoft SQL Server** vì ứng dụng chính sẽ được viết trên IDE **Microsoft Visual Studio 2019** ~~bản community~~. Việc sử dụng **Microsoft SQL Server** sẽ tăng tính bảo mật của thông tin, ~~(một phần là do tôi quen với cái này)~~ tuy nhiên các bạn hoàn toàn có thể dùng MySQL, SQLite, ... tùy ý theo nhu cầu và khả năng của mình.
## 1. Các bảng bên trong cơ sở dữ liệu
`
CREATE TABLE [dbo].[Product](
	[ID] [char](20) NOT NULL,
	[Name] [nvarchar](255) NOT NULL,
	[TypeProduct] [nvarchar](50) NULL,
	[Unit] [nvarchar](50) NULL,
	[Quantity] [int] NOT NULL,
	[Image] [image] NULL,
	[Note] [nvarchar](255) NULL,
	[Price] [float] NOT NULL,
	[SupplierID] [char](20) NULL,
PRIMARY KEY CLUSTERED 
(
	[ID] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON, OPTIMIZE_FOR_SEQUENTIAL_KEY = OFF) ON [PRIMARY]
) ON [PRIMARY] TEXTIMAGE_ON [PRIMARY]
GO
`<br>
*Bảng sản phẩm*<br>
`
CREATE TABLE [dbo].[Staff](
	[ID] [char](20) NOT NULL,
	[Name] [nvarchar](255) NOT NULL,
	[Gender] [nchar](8) NOT NULL,
	[DateOfBirth] [date] NOT NULL,
	[CitizenID] [char](12) NOT NULL,
	[Address] [nvarchar](255) NOT NULL,
	[Phone] [char](15) NOT NULL,
	[Email] [varchar](50) NULL,
	[Images] [image] NULL,
PRIMARY KEY CLUSTERED 
(
	[ID] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON, OPTIMIZE_FOR_SEQUENTIAL_KEY = OFF) ON [PRIMARY]
) ON [PRIMARY] TEXTIMAGE_ON [PRIMARY]
GO
`<br>
*Bảng nhân viên*<br>
## 2. Tạo các Trigger
`Đang cập nhật`
## 3. Các thủ tục (Store Procedure)
`Đang cập nhật`
## 4. Các hàm (Function)
`Đang cập nhật`

### [Source code sql]()

[P1: Phân tích và mô hình hóa](./Part1.md) <br>
[P3: Thiết kế giao diện người dùng](./Part3.md) <br>
[P4: Lập trình kết nối và chức năng](./Part4.md) <br>
[Về trang chủ](/FiFineBlog/)
