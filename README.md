# 🚀 Spring Boot Docker Deployment

This is a simple Spring Boot REST API deployed using **Docker** on an **AWS EC2 instance**.
### 📸 Demo Image

![Docker Deployment Screenshot](https://github.com/2023ayush/docker-deployment/raw/ffe7b306d7138d53d01daa035fad14cdf164ad9d/docker_deployment_ss.PNG)

[Jenkins Deployment Screenshot - 1](https://github.com/2023ayush/docker-deployment/blob/main/Capture%20Jenkins.PNG)

[Jenkins Deployment Screenshot - 2](https://github.com/2023ayush/docker-deployment/blob/main/Capture%20jenkins%201.PNG)

[Jenkins Deployment Screenshot - 3](https://github.com/2023ayush/docker-deployment/blob/main/Capture%20jenkins%201.PNG)

[Jenkins Deployment Screenshot - 4](https://github.com/2023ayush/docker-deployment/blob/main/Capture%20jenkins%203.PNG)
 




## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Maven
- Docker
- Jenkins
- AWS EC2


## 📦 How to Run

### 1. Launch an EC2 instance (Amazon Linux 2)
 
### 2. Install Docker

### 3. Install Jenkins

### 3. Pull Docker image
docker pull ayush4857/docker

### 4. Run the container with port mapping
docker run -d -p 8080:8080 ayush4857/docker

docker run -d -p 9091:8080 ayush4857/docker

### 5. Visit app in browser
http://<EC2_PUBLIC_IP>:8080/docker

✅ API Endpoint
GET /docker → "Hello from Docker"

GET /docker → "Hello from Docker, Jenkins now"




