# 🔐 Authentication App (Spring Boot Backend)

A complete, production-grade **authentication system** built using **Spring Boot**.  
Supports **JWT-based login**, **Refresh Tokens**, and **OAuth2 login with Google & GitHub**.  
Designed with clean architecture, layered services, and industry-standard security practices.

---

## 🏗️ Tech Stack (Backend)

- **Spring Boot 3.x**
- **Spring Security 6.x**
- **Spring Data JPA (MySQL)**
- **JWT Authentication (Access + Refresh Token)**
- **OAuth2 Client (Google & GitHub Login)**
- **Lombok**
- **Maven**

---

## ✨ Features

### 🔐 Authentication
- Username + Password login  
- JWT Access Token + Refresh Token  
- Stateless authentication using Spring Security  

### 🌍 OAuth2 Login
- Google OAuth2 login  
- GitHub OAuth2 login  
- Auto user creation on first login  

### 🛂 User Management
- Secure user registration  
- Password hashing using BCrypt  
- Role-Based Access Control (RBAC)  
- Custom UserDetails + AuthenticationProvider  

### ⚙️ Backend Architecture
- Layered: **Controller → Service → Repository**  
- DTO-based request/response  
- Global exception handling  
- Configurable JWT + OAuth2 properties  

---

## 📚 API Endpoints

### **Authentication APIs**
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | Login with username/password |
| POST | `/api/auth/refresh` | Generate new token using refresh token |

### **OAuth2 APIs**
| Endpoint | Description |
|----------|-------------|
| `/oauth2/authorization/google` | Google Login |
| `/oauth2/authorization/github` | GitHub Login |
| `/login/oauth2/code/*` | OAuth2 Redirect Handler |

---

## 📁 Project Structure

```
src/main/java/
 └── com.example.auth
      ├── controller
      ├── service
      ├── repository
      ├── security
      ├── config
      ├── model
      └── AuthApplication.java
```

---

## 👨‍💻 Developer

**Manjunath Yadgiri**  
Backend Developer — Java | Spring Boot | MySQL | JWT | OAuth2  
GitHub: https://github.com/Manjunathy10  

---

## ⭐ Support

If you like this project, please give it a **⭐ on GitHub**!

