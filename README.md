# 🔐 Spring Boot JWT Authentication API

Proyecto backend desarrollado con **Spring Boot 4.0.1**, **Java 17**, **Maven** y **JWT Authentication**.  
Realizado como proyecto de **aprendizaje y práctica**, siguiendo y adaptando el contenido del video de **Irina Rojas**.

---

## 🚀 Tecnologías

- Java 17
- Spring Boot 4.0.1
- Spring Security
- JWT (JSON Web Tokens)
- Spring Data JPA / Hibernate
- MySQL 8
- Maven
- Lombok

---

## 🎯 Funcionalidades

- Registro de usuarios
- Login con JWT
- Encriptación de contraseñas con BCrypt
- Endpoints protegidos
- Persistencia con MySQL

---

## 🗄 Base de datos

**Nombre:** `securitydb`

```sql
CREATE DATABASE securitydb;
CREATE USER 'demo_user'@'localhost' IDENTIFIED BY 'demo_pass';
GRANT ALL PRIVILEGES ON securitydb.* TO 'demo_user'@'localhost';
FLUSH PRIVILEGES;
```

## 🔐 Autenticación

El token JWT debe enviarse en cada request protegido:

Authorization: Bearer <token>

## 🧪 Testing

Los endpoints pueden probarse con:

- Postman
- Insomnia
- Curl

## 📚 Créditos

Este proyecto se basa en el tutorial de Irina Rojas:
🔗 [https://www.youtube.com/watch?v=KxqlJblhzfI](https://www.youtube.com/watch?v=nwqQYCM4YT8)
