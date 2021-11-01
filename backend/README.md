I. Backend-Server
1) Tạo folder backend -> cd backend
2) npm init -y
3) npm install express
4) npm install mongoose
5) npm install dotenv
6) npm install nodemon
7) "start": "nodemon backend/index.js"
8) Tạo database trên mongoDB sau đó lấy đường link ép vào mongoose.connect(
9) Tạo file .env để ẩn đường link liên kết database
10) Github
- git init
- git add . (sau này nhớ chèn file .gitignore không nó node_modules vào mệt lắm)
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/nguyenthanhsang231195/NodeJs-Backend.git
- git push -u origin main

II. Test Api
1) Sử dụng POSTMAN trong test api
- POST: localhost:5000/api/user/userposttest
- Chọn body -> raw -> JSON -> { "username": "sang"} -> SEND
2) Folder backend/model

III. Setup routers
1) auth.js
- Vào MongoDB tạo database {ví dụ:shop(nằm ở liên hết lúc khởi tạo link vào MongoDB)}
- khi POST thành công sẽ có thư mục như sau:
shop
    - users:
        _id:ObjectId(617f761566baf63eb22b845d)
        username:"sang"
        email:"nguyenthanhsang231195@gmail.com"
        password:"123456"
        isAdmin:false
        createdAt:2021-11-01T05:07:33.877+00:00
        updatedAt:2021-11-01T05:07:33.877+00:00
        __v:0
- npm install crypto-js
- npm install jsonwebtoken
2) user.js
3) verifyToken.js

IV. router/product
1) stripe.js
2) product.js
3) order.js
4) cart.js
