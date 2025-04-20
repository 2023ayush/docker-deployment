# 🚀 Spring Boot Docker Deployment

This is a simple Spring Boot REST API deployed using **Docker** on an **AWS EC2 instance**.

## Demo Image



## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Maven
- Docker
- AWS EC2


## 📦 How to Run

### 1. Launch an EC2 instance (Amazon Linux 2)
 
### 2. Install Docker

### 3. Pull Docker image
docker pull ayush4857/docker

### 4. Run the container with port mapping
docker run -d -p 8080:8080 ayush4857/docker

### 5. Visit app in browser
http://<EC2_PUBLIC_IP>:8080/docker

✅ API Endpoint
GET /docker → "Hello from Docker"



