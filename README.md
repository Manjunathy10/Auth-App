# 🔐 Authentication App (Spring Boot Backend)

A complete, production-grade **authentication system** built using **Spring Boot**.  
Supports **JWT-based login**, **Refresh Tokens**, and **OAuth2 login with Google & GitHub**.  
Designed with clean architecture, layered services, and industry-standard security practices.

---

## 🏗️ Tech Stack (Backend)

- **Spring Boot 3.x**
- **Spring Security 6.x**
- **Spring Data JPA** (MySQL)
- **JWT Authentication** (Access + Refresh Tokens)
- **OAuth2 Client** (Google & GitHub Login)
- **Maven**
- **Lombok**
- **HikariCP (Fast Connection Pooling)**

---

## ✨ Features

### 🔐 **Authentication**
- Username + Password Login
- JWT Access & Refresh Token system
- Stateless authentication using Spring Security

### 🌍 **OAuth2 Login**
- Google OAuth2 Login
- GitHub OAuth2 Login
- Automatic user provisioning on first login

### 🛂 **User Management**
- Secure user registration
- Password encryption (BCrypt)
- Role-Based Access Control (RBAC)
- Custom user details service

### ⚙️ **Backend Architecture**
- Multi-layer design: **Controller → Service → Repository**
- DTO-based request/response handling
- Exception handling with global controller advice
- Uses HikariCP for optimized DB performance

---

## 📚 API Endpoints (Main)

### **Auth APIs**
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | Login with username/password |
| POST | `/api/auth/refresh` | Generate new JWT using refresh token |

### **OAuth2 APIs**
| Endpoint | Description |
|----------|-------------|
| `/oauth2/authorization/google` | Google Login |
| `/oauth2/authorization/github` | GitHub Login |
| `/login/oauth2/code/*` | OAuth2 Redirect URI Handler |

---

## ⚙️ Project Setup

### 1
