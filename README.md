# Patient-Management System (Backend)

In the patient management microservice system, each service is implemented as an independent module, with security filters applied to every API endpoint. Each module is packaged in its own Docker image.

---

## ✨ Features

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)

---

- ⚙️ **Java & Spring Boot** – Core technologies used to build modular microservices
- 🐳 **Dockerized Microservices** – Each module runs in its own Docker container
- 🗄️ **PostgreSQL Databases** – Reliable relational storage for persistent data
- 🔀 **Load Balancers & API Gateways** – Smart request routing and traffic management
- 📡 **Event-Driven Architecture (Kafka)** – Asynchronous communication between services
- ⚡ **Real-Time Communication** – Supports both **REST** and **gRPC** protocols
- 🔐 **Secure Authentication** – Bearer tokens for user authentication and API protection
- 🧪 **Integration Tests** – Ensures reliable inter-service interactions
- ☁️ **AWS Deployment with LocalStack** – Infrastructure as Code (IaC) setup for cloud deployment

---

🚀 *Built for scalability, security, and seamless communication across distributed services.*

## 🧰 Tech Stack

**Backend:**
> ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
> ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
> ![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Database & Messaging:**
> ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
> ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**Containerization & Deployment:**
> ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
> ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
> ![LocalStack](https://img.shields.io/badge/LocalStack-3D3D3D?style=for-the-badge&logo=localstack&logoColor=white)
> ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**Security:**
> ![Bearer Token](https://img.shields.io/badge/Bearer%20Token-000000?style=for-the-badge&logo=jwt&logoColor=white)
> ![OAuth2](https://img.shields.io/badge/OAuth2-3C3C3C?style=for-the-badge&logo=openid&logoColor=white)

**Testing:**
> ![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)
> ![Rest Assured](https://img.shields.io/badge/Rest%20Assured-00BFAE?style=for-the-badge&logo=testing-library&logoColor=white)

---

🚀 *Designed for scalability, observability, and high availability — ideal for modern healthcare systems.*

## 🏥 Patient Management Architecture
---

![Patient Management Architecture](./asset/Patient-Management.svg)

---

## ☁️ AWS Architecture
---

![AWS Architecture Diagram](./asset/aws_architecture.svg)

---

## ⚙️ Setup Instructions
To deploy the Patient Management microservices locally using **Docker** and **LocalStack**, follow these steps:

1. **Install prerequisites**
    - [Docker](https://docs.docker.com/get-docker/)
    - [LocalStack](https://docs.localstack.cloud/getting-started/installation/)

2. **Start all required services**

3. **Run localstack-deploy.sh under infrastructure

---

This keeps everything **Markdown-only**, clean, and ends with a clear confirmation sentence.

If you want, I can also **slightly tweak the setup instructions** so it’s **even easier to follow for first-time users**. Do you want me to do that?