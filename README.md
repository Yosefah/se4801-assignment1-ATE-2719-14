# se4801-assignment1-ATE-2719-14
enterprise individual assignment
<div align="center">

# 🌊 ShopWave-Starter
**Enterprise Application Development | Core Java & Spring Boot**

[![Java 21](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](#)
[![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)](#)
[![CI Status](https://img.shields.io/github/actions/workflow/status/YOUR-GITHUB-USERNAME/se4801-assignment1-ATE-2719-14/ci.yml?style=for-the-badge&logo=githubactions&logoColor=white)](#)

*A robust, layered-architecture Spring Boot service demonstrating Inversion of Control (IoC), Dependency Injection, and modern Java fundamentals.*

</div>

---

## 🎓 Academic Profile

| Role | Name | Identifier | Module |
| :--- | :--- | :--- | :--- |
| **Developer** | Yosef Ahmedin | `ATE-2719-14` | SE 4801 - Unit 1 |

---

## 🏗️ Architectural Overview
This application follows a strict **Layered Monolithic Architecture** to ensure separation of concerns and adherence to SOLID principles.

* **Controller Layer:** Manages incoming HTTP requests and RESTful routing.
* **Service Layer:** Encapsulates core business logic and transaction management.
* **Repository Layer:** Interfaces with the embedded H2 database via Spring Data JPA.

---

## 🚀 Getting Started

### 1. Build the Application
Ensure you have JDK 21 installed. This project utilizes the Maven Wrapper, so a local Maven installation is not strictly required.

```bash
# Windows
mvnw.cmd clean install

# macOS / Linux
./mvnw clean install
