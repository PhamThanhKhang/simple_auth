#  Simple Authentication (Basic & Cookie Auth)

##  Giới thiệu
Repo này minh họa hai cơ chế xác thực cơ bản trong Node.js:  
1. **Basic Authentication**  
2. **Cookie Authentication**

Các ảnh dưới đây là kết quả test bằng **Postman**.

---

##  Kết quả test

### 1. Basic Auth
![Basic Auth](basic_auth.png)

---

### 2. Cookie Auth
#### a. Login
![Login](login.png)

#### b. Show Cookie trong MongoDB
![Show Cookie](show_cookie.png)

#### c. Logout
![Logout](logout.png)

#### d. Kiểm tra Cookie sau khi Logout
![Show Cookie After Logout](show_cookie_afterlogout.png)

---

## ✅ Kết luận
- Basic Auth: yêu cầu gửi đúng thông tin trong header `Authorization`.  
- Cookie Auth: đăng nhập thành công sẽ tạo cookie, lưu vào MongoDB, và bị xóa sau khi logout.  
