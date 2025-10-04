# 🎓 Knowledge Bridge  

An **EdTech Platform** built with the **MERN stack** to bridge the gap between learners and instructors.  
Knowledge Bridge provides secure authentication, role-based dashboards, and a scalable system for course management, ratings, and payments.  

---

## ✨ Features
- 🔑 **Authentication & Security**  
  - JWT-based auth, OTP verification, bcrypt password hashing  
  - Password reset & email verification with NodeMailer  

- 📚 **Course Management**  
  - Instructors can create, edit, and delete courses  
  - Students can enroll, access content, and leave ratings  

- 💳 **Payment Integration**  
  - Razorpay checkout for seamless course payments  

- ☁️ **Cloud Services**  
  - Media hosting via Cloudinary for scalable and reliable content delivery  

- 📊 **Dashboards**  
  - Role-based dashboards for instructors and learners  
  - Course progress tracking & rating system  

- 🎨 **Modern UI/UX**  
  - Built with React.js + TailwindCSS for responsive and clean interfaces  

---

## 🛠️ Tech Stack
- **Frontend:** React.js, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** JWT, OTP, bcrypt  
- **Payments:** Razorpay API  
- **Media Management:** Cloudinary  

---

## 🚀 Getting Started

### Prerequisites
Make sure you have installed:  
- [Node.js](https://nodejs.org/) (>=16.x)  
- [MongoDB](https://www.mongodb.com/) (local or Atlas)  
- [Razorpay Account](https://razorpay.com/) for payments  
- [Cloudinary Account](https://cloudinary.com/) for media uploads  

### Installation
```bash
# Clone the repository
git clone https://github.com/WisKeyOp/Knowledge_main.git
cd Knowledge_main

# Install dependencies for backend
cd server
npm install

# Install dependencies for frontend
cd ../client
npm install
Configuration
Create .env files in both server and client directories. Example (server):

env
Copy code
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_HOST=smtp.example.com
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
Run the Application
bash
Copy code
# Run backend (server)
cd server
npm start

# Run frontend (client)
cd ../client
npm start
Visit http://localhost:3000 to use the app.

```
👨‍💻 Contributors
- This project was developed and maintained by:
- Aayush Shukla – Full Stack Developer
- Keshav Dutt Gautam – Full Stack Developer

📜 License
This project is licensed under the MIT License – feel free to use and modify with attribution.

⭐ If you like this project, consider giving it a star on GitHub!

