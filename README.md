# Basic Spring Boot API with Docker and Java 17 🚀

This repository contains a basic **Spring Boot API** running in a **Docker** container with simple **'Hello, World!'** response.

## 📦 Features
- Built with **Java 17** and **Spring Boot 3**.
- Containerized using **Docker**.
- Supports **Docker Compose** for easier setup.
- Lightweight and fast.

## 🔧 Tech Stack
- Java 17.
- Spring Boot 3.
- Docker.
- Maven.
- Docker Compose.

## 🚀 Getting Started

### 🐳 Docker Image
This application is available on **Docker Hub**:

[![Docker Pulls](https://img.shields.io/docker/pulls/caiobom/docker-java-spring-boot-basic?style=flat-square)](https://hub.docker.com/r/caiobom/docker-java-spring-boot-basic)

### 📥 **Cloning the Repository**
To get started, first **clone the repository**:

```sh
git clone https://github.com/caaiobomfim/docker-java-spring-boot-basic.git
```

### 🔥 Running the Application with Docker Compose
Run the following command to build and start the containers:

```sh
cd docker-java-spring-boot-basic
docker-compose up -d --build
```

### 🌍 Testing the Application
Once the containers are running, access:

```sh
http://localhost:8080/api/hello
```

Or use curl:

```sh
curl http://localhost:8080/api/hello
```