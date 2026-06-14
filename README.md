# ZooCart E-Commerce Platform

A robust, full-stack e-commerce application built with a modern tech stack, focusing on scalability, type safety, and production-ready practices.

## 🚀 Tech Stack

### Backend
* **Framework:** [NestJS](https://nestjs.com/)
* **Database ORM:** [Prisma](https://www.prisma.io/)
* **Database:** PostgreSQL
* **Security:** JWT Authentication, Rate Limiting, CORS, Helmet
* **Payments:** Stripe Integration

### Frontend
* **Framework:** [Next.js](https://nextjs.org/)
* **Language:** TypeScript
* **Styling:** Sass CSS

### DevOps & Infrastructure
* **Containerization:** Docker
* **Cloud:** AWS
* **CI/CD:** Automated pipeline integration

## 🏗️ Project Architecture
The project follows a modular architecture where each domain feature (e.g., Users, Payments, Orders) is encapsulated within its own module, utilizing NestJS's dependency injection for clean, maintainable code.

## ⚙️ Prerequisites
Before running the project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (Latest LTS version recommended)
* Docker (for database and container services)
* Stripe Account (for payment processing)

## 📦 Getting Started

### 1. Installation
Clone the repository and install the dependencies:
```bash
git clone <your-repository-url>
cd zoocart
npm install