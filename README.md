# Secure Auth Service 🔐

Secure authentication & authorization service built with Java, Spring Boot, JWT, and Role-Based Access Control (RBAC).

### 🚀 Features
- User Registration & Login with encrypted passwords (BCrypt)
- JWT Token Generation & Validation (stateless auth)
- Role-Based Access Control (USER, ADMIN roles)
- Protected REST APIs
- MySQL database integration
- Exception handling & validation
- 80% test coverage with JUnit & Mockito

### 🛠 Tech Stack
- Java 17, Spring Boot 3, Spring Security 6
- JWT (jjwt), Spring Data JPA, MySQL
- JUnit 5, Mockito, Maven
- Postman for API testing

### 🔧 How to Run
1. Clone: git clone https://github.com/vasantha-c-16/Secure-Auth-Service.git
2. Configure MySQL in application.properties
3. Run: mvn spring-boot:run

### 📊 APIs
- POST /api/auth/register
- POST /api/auth/login
- GET /api/user/profile (protected)

### ✅ Testing
- Unit tests: mvn test
- Coverage: 80%+

Built for Siemens Gamesa Intern - Backend & Testing focus
