# 🛍️ Product Catalog Microservice

![Java](https://img.shields.io/badge/Java-17-blue?logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7-green?logo=spring&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-Event%20Driven-black?logo=apachekafka)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue?logo=docker)
![OpenAPI](https://img.shields.io/badge/OpenAPI-3.0-yellow?logo=openapiinitiative)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🌟 Overview  
This is a **Spring Boot microservice** for managing a product catalog.  
📝 Provides REST APIs for **Create / Read / Delete products**  
📣 Publishes **product creation events** to **Kafka**  
🐳 Fully containerized with **Docker + Docker Compose**

---

## ⚙️ Tech Stack  
| Tech | Description |
|-------|-------------|
| ☕ **Java 17** | Main programming language |
| 🌱 **Spring Boot** | Framework for building microservice |
| 🗃️ **Spring Data JPA + H2** | Database access (can switch to MySQL/Postgres) |
| ⚡ **Kafka + Zookeeper** | Messaging / event streaming |
| 🐳 **Docker / Docker Compose** | Containerization & orchestration |
| 📄 **Swagger (OpenAPI 3)** | Auto-generated API documentation |

---

## 🏗️ Architecture  
✅ **Model:** Represents `Product` entity  
✅ **Repository:** JPA repository for DB operations  
✅ **Service:** Business logic + Kafka publishing  
✅ **Controller:** Exposes REST endpoints  

---

## 🚀 Run Locally  

### 1️⃣ Build the JAR
```bash
mvn clean package
