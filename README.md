# Product Catalog Microservice

## Overview
This is a Spring Boot microservice for managing products.  
It provides REST APIs to create, retrieve, list, and delete products, and publishes product creation events to Kafka.

## Tech Stack
- Java 17 + Spring Boot
- Spring Data JPA + H2 (can switch to any RDBMS)
- Kafka + Zookeeper
- Docker + Docker Compose
- Swagger (OpenAPI 3) for API docs

## Architecture
- **Model:** Represents product entity.
- **Repository:** Handles DB operations.
- **Service:** Contains business logic (e.g., saves product + publishes Kafka event).
- **Controller:** Exposes REST APIs.

## Run Locally
1️⃣ Build:
```bash
mvn clean package
