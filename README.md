🚕🚓🚗 **Smart Parking Management System (SPMS)**  
<p align="center">
  <img src="https://github.com/MaheshaDinu/smart_parking_system_micro_services/blob/main/doc/localhost_8761_.png" alt="Eureka Dashboard" width="80%"/>
</p>

---

## 🧠 Overview
The **Smart Parking Management System (SPMS)** is a cloud-native, microservice-based backend suite designed to streamline urban parking operations. It empowers:

- **Drivers** to find, reserve, and pay for parking in real time.  
- **Parking-space owners** to manage availability and pricing.  
- **Admins** to monitor service health and usage metrics via Eureka.

---

## 🚀 Technologies Used

- 🔧 **Spring Boot** – Core framework for microservices  
- 🌐 **Spring Cloud Config** – Centralized configuration server  
- 🧭 **Spring Cloud Eureka** – Service registry & dashboard  
- 🚪 **Spring Cloud Gateway** – API Gateway for routing & filtering  
- 🔐 **Spring Security + JWT** – Authentication & role-based authorization  
- 🗄 **MySQL** – Relational data store  
- 🧪 **Postman** – API testing & automation  
- 🛠 **Maven** – Dependency management  

---

## 🔧 Prerequisites

Make sure you have the following installed locally:

- 🧩 **Java 17+**  
- 🐘 **Maven**  
- 🐬 **MySQL Server**  
- 📫 **Postman**  
- 💻 **Git**  
- ☁️ **Internet** (for dependency downloads)  

---

## 🏁 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/smart-parking-management-system.git
   cd smart-parking-management-system
2. **Configure MySQL**

Create databases: spms_user, spms_vehicle, spms_parking, spms_payment

Update credentials & URLs in config-server/src/main/resources/application.yml
