# Ecommerce Backend - Spring Boot 🚀

A scalable and production-ready **Ecommerce Backend** built using **Spring Boot**, following clean layered architecture and modern backend engineering best practices.  
This project is designed with an **industry-level structure** suitable for real-world applications and interviews.

---

## ✨ Features

- User Registration & Login
- Spring Security based authentication
- Clean layered architecture (Controller → Service → Repository)
- DTO-based request and response handling
- Role-based design (USER / ADMIN)
- Maven-based project setup
- GitHub version control (professional workflow)

---

## 🛠 Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **Hibernate**
- **MySQL / H2 (development)**
- **Maven**
- **Git & GitHub**

---

## 📁 Project Structure

```text
com.ecommerce.backend
 ├── controller        # REST Controllers
 ├── dto               # Request & Response DTOs
 ├── model             # JPA Entities
 ├── repository        # Database access layer
 ├── service           # Business interfaces
 │    └── impl         # Business logic implementation
 ├── security          # Spring Security configuration
 ├── exception         # Global exception handling
 └── EcommerceBackendApplication
🔐 Authentication APIs
Method	Endpoint	Description
POST	/api/auth/register	Register new user
POST	/api/auth/login	Login existing user
▶️ How to Run the Project
# Clone the repository
git clone https://github.com/Ashu2621/ecommerce-backend-springboot.git

# Navigate to project directory
cd ecommerce-backend-springboot

# Run the application
mvn spring-boot:run


The application will start on:

http://localhost:8080
