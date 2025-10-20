# 🎯 Scalable Task Manager (NestJS, PostgreSQL, Kafka, Redis)

<p align="center">
  <a href="http://nestjs.com/" target="_blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[![NestJS Badge](https://img.shields.io/badge/Framework-NestJS-E0234E?style=for-the-badge&logo=nestjs)](https://nestjs.com/)
[![Database](https://img.shields.io/badge/Database-PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Message Broker](https://img.shields.io/badge/Broker-Apache%20Kafka-231f20?style=for-the-badge&logo=apache-kafka)](https://kafka.apache.org/)
[![Caching/Queue](https://img.shields.io/badge/Cache%20&%20Queue-Redis-DC382D?style=for-the-badge&logo=redis)](https://redis.io/)
[![Language](https://img.shields.io/badge/Language-TypeScript-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![License](https://img.shields.io/github/license/sattarrasouli/task-manager)](./LICENSE)
[![CircleCI](https://img.shields.io/circleci/build/github/nestjs/nest/master)](https://circleci.com/gh/nestjs/nest)
[![NPM Version](https://img.shields.io/npm/v/@nestjs/core.svg)](https://www.npmjs.com/~nestjscore)

<p align="center">
  A highly efficient and scalable backend for a task management application, leveraging microservices architecture with NestJS, PostgreSQL for data persistence, Kafka for asynchronous messaging, and Redis for caching and session management.
</p>

---

## 🚀 Features

This application demonstrates a robust, enterprise-grade backend for managing user tasks, with a focus on **scalability** and **resilience**.

* **Core CRUD API:** Full support for creating, reading, updating, and deleting tasks.
* **Persistent Storage:** Uses **PostgreSQL** for reliable data storage.
* **Asynchronous Processing:** Implements **Kafka** for handling asynchronous events (e.g., task status updates, notifications) via microservices.
* **High Performance:** Utilizes **Redis** for fast caching of frequently accessed data and for managing user sessions/rate limits.
* **NestJS Architecture:** Clean, modular, and testable code adhering to NestJS best practices.

---

## 🛠️ Tech Stack & Architecture

The project is structured around the following key technologies:

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Framework** | **NestJS (TypeScript)** | Primary application and microservice framework. |
| **Database** | **PostgreSQL** | Primary relational data persistence (using TypeORM/Prisma). |
| **Messaging** | **Apache Kafka** | Asynchronous communication between services (e.g., event-driven processing). |
| **Caching** | **Redis** | In-memory data store for caching and session management. |

---

## ⚙️ Project Setup (Local Development)

This project requires **Node.js**, **pnpm**, and **Docker** to run the services (Postgres, Kafka, Redis).

### 1. Prerequisites

* Node.js (LTS version)
* pnpm
* Docker & Docker Compose

### 2. Clone the Repository

```bash
git clone [https://github.com/sattarrasouli/task-manager.git](https://github.com/sattarrasouli/task-manager.git)
cd task-manager
