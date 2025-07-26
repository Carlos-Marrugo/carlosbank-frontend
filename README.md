# AngularBancoApp

![Angular](https://img.shields.io/badge/Angular-v18-red) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-v3-green) ![JWT](https://img.shields.io/badge/JWT-Auth-blue) ![Bootstrap](https://img.shields.io/badge/Bootstrap-v5-purple)

A modern **Angular 18** application with a secure login system integrated with a **Spring Boot** backend using **JWT** for authentication. This project demonstrates a complete frontend implementation with a login form, authentication service, HTTP interceptor, and protected routes.

## ✨ Features
- **Secure Login**: Authenticate users with username and password.
- **JWT Authentication**: Stores JWT in localStorage and attaches it to requests via an HTTP interceptor.
- **Protected Routes**: Uses Angular guards to restrict access to authenticated users.
- **Responsive UI**: Built with Bootstrap 5 for a clean and mobile-friendly design.
- **Modular Structure**: Organized with components, services, models, and interceptors.

## 🚀 Getting Started

### Prerequisites
- **Node.js** (>= 16.x) and **npm**
- **Angular CLI**: `npm install -g @angular/cli`
- **Spring Boot Backend**: Running locally on `http://localhost:8080` with a `/api/auth/login` endpoint returning a JWT token.
- **Java** and **Maven** for the backend.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/angular-login-app.git
   cd angular-login-app
