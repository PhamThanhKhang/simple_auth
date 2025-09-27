#  Simple Authentication 

## Giới thiệu
Dự án này là một phần trong bài lab **Security in Node.js**.  
Repository `simple_auth` minh họa 2 cơ chế xác thực cơ bản:
1. **Basic Authentication** – kiểm tra thông tin đăng nhập thông qua header `Authorization`.
2. **Cookie Authentication** – tạo và quản lý cookie sau khi đăng nhập, đồng thời lưu thông tin trong MongoDB.

## Chức năng chính
- **Basic Auth**
  - Người dùng gửi request với header `Authorization: Basic <username:password>` để truy cập tài nguyên.
- **Cookie Auth**
  - Người dùng đăng nhập → server tạo cookie.
  - Cookie được lưu trong MongoDB.
  - Người dùng có thể kiểm tra cookie khi gọi các API khác.
  - Khi logout, cookie sẽ bị xóa khỏi DB.

