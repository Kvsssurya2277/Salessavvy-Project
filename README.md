# SalesSavvy E-Commerce Application 🛒

SalesSavvy is a dynamic and user-friendly e-commerce application that allows customers to buy products and admins to manage inventory. This project is built using **Spring Boot** and **MySQL**, ensuring efficient data handling and secure transactions.

## 🚀 Features
---

### **👤 Customer Features**
- Browse and search for products.  
- Add products to the cart and place orders.  
- View order history and manage their profile.  
- Secure payments using **Razorpay integration**.  

### **🛠 Admin Features**
- Add, update, and delete products.  
- Manage orders and track customer purchases.  
- View sales analytics for business insights.  

## 🛑 Prerequisites
---
Ensure you have the following installed before running the project:  
- Java JDK 17+  
- MySQL 8+  
- Spring Boot  
- Node.js and npm (for frontend)  
- Git  

## 🔧 Installation & Setup
1️⃣ Clone the Repository,
Run the following command:
- git clone https://github.com/your-repo/sales-savvy.git
- cd sales-savvy

2️⃣ Configure the Database
- Open application.properties in src/main/resources/
  - Update your MySQL credentials:
  - spring.datasource.url=jdbc:mysql://localhost:3306/sales_db <!--your database name-->
  - spring.datasource.username=root  <!--your user-name-->
  - spring.datasource.password=yourpassword  <!--your password-->

3️⃣ Set Up Razorpay
- Get your Razorpay API Key & Secret from Razorpay Dashboard
  - Add them to application.properties:
  - razorpay.key_id=your_api_key <!--your api key it is unique to everyone--> 
  - razorpay.key_secret=your_api_secret  <!--your password-->
  
4️⃣ Run the Backend
 - Select the project and Run as spring-boot application in the sts to start the backend server:

5️⃣ Start the Frontend
- Navigate to the frontend folder and start the application:
  - cd frontend  
  - npm install  
  - npm start  

📌 Deployment

For deployment, you can use Render, Vercel, or AWS. Follow their guidelines for hosting Spring Boot and React applications.
