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
