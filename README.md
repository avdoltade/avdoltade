<div align="center">

# 🚀 FixItNow: On-Demand Service Platform

[![Deploy Status](https://img.shields.io/badge/Deploy-Success-brightgreen?style=for-the-badge&logo=github-actions)](#)
[![Docker](https://img.shields.io/badge/Docker-Containerized-blue?style=for-the-badge&logo=docker)](#)
[![AWS](https://img.shields.io/badge/AWS-Cloud_Hosted-FF9900?style=for-the-badge&logo=amazonaws)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](#)

*A scalable, real-time service booking platform deployed with a fully automated CI/CD pipeline and containerized microservices.*

[Explore the Docs](#) · [Report Bug](#) · [Request Feature](#)

</div>

---

## 📖 Overview

**FixItNow** is a robust on-demand service booking application featuring role-based dashboards and real-time updates. From a DevOps perspective, this project demonstrates modern cloud-native deployment practices, utilizing Docker for consistent environments, GitHub Actions for continuous integration, and AWS for scalable hosting.

## ✨ Key Features

* **🔐 Role-Based Access Control (RBAC):** Secure authentication for Users, Providers, and Admins.
* **⚡ Real-Time Communications:** Instant booking updates and notifications powered by Socket.IO.
* **🐳 Fully Containerized:** Isolated frontend and backend environments using `docker-compose`.
* **🔄 Automated CI/CD:** Automated testing, Docker image builds, and AWS deployment via GitHub Actions.
* **☁️ Highly Available Infrastructure:** Provisioned cloud resources ensuring high uptime and scalability.

---

## 🛠️ Tech Stack & Infrastructure

This project leverages a modern stack, bridging full-stack development with enterprise-grade infrastructure.

### **Cloud & DevOps**
* ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) 
* ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
* ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
* ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

### **Application Stack**
* ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
* ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
* ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
* ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

---

## 🏗️ Architecture & Pipeline

*(Consider adding a visual architecture diagram here using Draw.io or Excalidraw)*

1. **Code Commit:** Developer pushes code to the `main` branch.
2. **CI Phase:** GitHub Actions triggers unit tests and linting.
3. **Build Phase:** Multi-stage `Dockerfile` builds lightweight images for the Node.js backend and React frontend.
4. **Registry:** Images are tagged and pushed to Amazon ECR / Docker Hub.
5. **CD Phase:** The updated containers are deployed to the AWS environment (EC2/EKS).

---

## 🚀 Getting Started

Follow these instructions to run the application and infrastructure locally.

### Prerequisites

Ensure you have the following installed:
* [Docker & Docker Compose](https://www.docker.com/)
* [Git](https://git-scm.com/)
* [AWS CLI](https://aws.amazon.com/cli/) (Configured with your credentials)

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone [https://github.com/avdoltade/FixItNow.git](https://github.com/avdoltade/FixItNow.git)
   cd FixItNow
