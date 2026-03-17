# 🌾 Farm Scheme - Agriculture Management System

## 📌 Overview

Farm Scheme is a Java-based web application designed to empower farmers through digital solutions. The system enables farmers to sell crops via online bidding and benefit from government schemes like insurance.

This project aims to modernize agriculture practices by providing a platform for farmers, bidders, and administrators to interact efficiently.

---

## 🎯 Problem Statement

Farmers often face challenges such as:

* Lack of awareness about government schemes
* Difficulty in getting fair prices for crops
* Inefficient manual processes

This system solves these issues by integrating:

* Crop Bidding System
* Insurance (Fasal Bima Yojna)



---

## 🎯 Objectives

* Encourage modern and innovative farming practices
* Provide better price discovery through bidding
* Ensure financial security via insurance schemes
* Digitize agricultural processes

---

## 👥 Users of the System

The application supports three types of users:

### 1. 👨‍🌾 Farmer

* Register and login
* Place crop for auction
* Apply for insurance
* Claim insurance
* View crop history

### 2. 💰 Bidder

* View available crops
* Participate in bidding
* Place bids on crops

### 3. 🛠 Admin

* Approve users
* Manage bidding process
* Approve crop sales
* Process insurance claims

---

## 🧩 Modules

### 🔹 1. Bidding Module

* Farmers can request crop auctions
* Bidders can place bids
* Admin approves final bids

**Features:**

* Marketplace for crops
* Real-time bidding
* Crop history tracking

---

### 🔹 2. Insurance Module (Fasal Bima Yojna)

Provides financial protection against:

* Natural calamities
* Pests and diseases

**Key Features:**

* Apply for insurance
* Premium calculation
* Claim insurance

**Premium Rates:**

* 2% for Kharif crops
* 1.5% for Rabi crops
* 5% for commercial crops

---

### 🔹 3. Authentication Module

* Secure login & registration
* Role-based access control
* Forgot password feature

---

### 🔹 4. Home Module

* Home page
* About Us
* Contact Us

---

## 🔄 System Workflow

1. User visits homepage
2. Registers as Farmer or Bidder
3. Logs into system
4. Access dashboard based on role
5. Performs operations (bidding / insurance)

---

## 🏗️ Project Architecture (Your Implementation)

### 🔧 Backend:

* Java
* Spring Boot
* Spring Security
* REST APIs
* JPA / Hibernate

### 🌐 Microservices:

* API Gateway
* Auth Service
* Bidding Service
* (Other services based on your implementation)

### 🗄️ Database:

* MySQL

### ☁️ Tools & Tech:

* Eureka Server (Service Discovery)
* JWT Authentication
* Angular (Frontend)

---

## 🚀 Features

* Role-based login system
* Online crop bidding
* Insurance application & claims
* Admin approval workflows
* Secure API communication

---

## 📂 Project Structure

```
farm-scheme/
│
├── api-gateway/
├── auth-service/
├── bidding-service/
├── frontend/
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔹 1. Clone Repository

```bash
git clone https://github.com/your-username/farm-scheme.git
cd farm-scheme
```

### 🔹 2. Run Services

Start services in order:

1. Eureka Server
2. API Gateway
3. Auth Service
4. Other Services

---

### 🔹 3. Configure Database

Update `application.properties`:

```
spring.datasource.url=jdbc:mysql://localhost:3306/farm_scheme
spring.datasource.username=root
spring.datasource.password=yourpassword
```

---

### 🔹 4. Run Application

```bash
mvn spring-boot:run
```

---

## 🔐 Security

* JWT-based authentication
* Role-based authorization
* Secure API endpoints

---

## 📈 Future Enhancements

* Mobile app integration
* AI-based crop price prediction
* Payment gateway integration
* Real-time notifications

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork and submit pull requests.

---

## 📞 Contact

For any queries or support, please contact the project administrator.

---

## ⭐ Conclusion

Farm Scheme is a step towards digital agriculture, helping farmers gain better profits, awareness, and security through technology.

---
