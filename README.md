# 🚀 Dockerized Node.js App with GitHub Actions CI/CD

This project demonstrates a simple **Node.js application** that is fully containerized using **Docker** and deployed using **GitHub Actions** for Continuous Integration and Deployment (CI/CD).

---

## 📦 Features

- Simple Node.js server
- Dockerized for container-based deployment
- GitHub Actions pipeline for:
  - Automated build on push
  - Docker container run on GitHub-hosted runners

---

## 🛠️ Technologies Used

- Node.js
- Docker
- GitHub Actions
- Bash

---

## 📁 Project Structure

docker-node-app/
├── index.js # Main Node.js server file
├── Dockerfile # Docker build instructions
├── package.json # Node.js metadata and start script
└── .github/
└── workflows/
└── docker-build.yml # GitHub Actions workflow
