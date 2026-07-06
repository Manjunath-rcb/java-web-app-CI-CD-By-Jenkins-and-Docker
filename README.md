# Java Web Application CI/CD using Jenkins & Docker

A complete **CI/CD pipeline project** for a Java Web Application using **Jenkins**, **Maven**, **Docker**, and **GitHub**. This project demonstrates how to automate the software development lifecycle from source code checkout to Docker image deployment.

---

# 📌 Project Overview

This project showcases the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Java web application.

Whenever code is pushed to the GitHub repository, Jenkins automatically:

- Checks out the latest source code
- Builds the application using Maven
- Generates a WAR file
- Builds a Docker image
- Deploys the application inside a Docker container

This project provides hands-on experience with modern DevOps practices and automation. :contentReference[oaicite:0]{index=0}

---

# 🚀 Features

- Java Web Application
- Maven Build Automation
- Jenkins CI/CD Pipeline
- Docker Containerization
- GitHub Source Control
- Automatic Build Process
- WAR File Packaging
- Automated Deployment
- Easy Local Setup

---

# 🛠️ Tech Stack

## Backend

- Java
- Maven

## Web Technologies

- HTML
- CSS
- JSP
- Servlet

## DevOps

- Git
- GitHub
- Jenkins
- Docker

## Application Server

- Apache Tomcat

---

# 📂 Project Structure

```
java-web-app-CI-CD-By-Jenkins-and-Docker
│
├── src
│   └── main
│       ├── java
│       ├── resources
│       └── webapp
│
├── Dockerfile
├── Jenkinsfile
├── pom.xml
├── README.md
└── target
```

---

# ⚙️ Prerequisites

Install the following before running the project:

- Java JDK 17 (or compatible version)
- Apache Maven
- Git
- Docker
- Jenkins
- Apache Tomcat (optional)

---

# 📥 Clone Repository

```bash
git clone https://github.com/Manjunath-rcb/java-web-app-CI-CD-By-Jenkins-and-Docker.git

cd java-web-app-CI-CD-By-Jenkins-and-Docker
```

---

# 🔨 Build Project

```bash
mvn clean package
```

or

```bash
mvn clean install
```

---

# ▶️ Run Application

Deploy the generated WAR file to Apache Tomcat.

Start Tomcat and open:

```
http://localhost:8080/
```

---

# 🐳 Docker

## Build Docker Image

```bash
docker build -t java-web-app .
```

## Verify Image

```bash
docker images
```

## Run Docker Container

```bash
docker run -d -p 8080:8080 java-web-app
```

## Verify Running Containers

```bash
docker ps
```

Open:

```
http://localhost:8080
```

---

# 🔄 Jenkins CI/CD Pipeline

The Jenkins pipeline automates the following stages:

- Checkout source code from GitHub
- Build project using Maven
- Package application as WAR
- Build Docker image
- Run Docker container
- Deploy latest application automatically

This workflow reflects a common CI/CD automation pattern used in Java projects. :contentReference[oaicite:1]{index=1}

---

# ⚡ Pipeline Workflow

```
Developer
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins
      │
      ▼
Source Code Checkout
      │
      ▼
Maven Build
      │
      ▼
WAR File Generation
      │
      ▼
Docker Image Build
      │
      ▼
Docker Container
      │
      ▼
Java Web Application
```

---

# 📦 Useful Maven Commands

Compile

```bash
mvn compile
```

Run Tests

```bash
mvn test
```

Package

```bash
mvn package
```

Clean

```bash
mvn clean
```

Install

```bash
mvn install
```

---

# 📚 Learning Outcomes

This project helped me understand:

- Java Web Application Development
- Maven Build Lifecycle
- Jenkins Pipeline Creation
- Continuous Integration (CI)
- Continuous Deployment (CD)
- Docker Image Creation
- Docker Container Management
- GitHub Version Control
- DevOps Automation

---

# 🚀 Future Enhancements

- Add Unit Testing
- SonarQube Code Analysis
- Docker Hub Integration
- Kubernetes Deployment
- Helm Charts
- GitHub Webhooks
- Email Notifications
- Prometheus Monitoring
- Grafana Dashboard
- AWS Deployment

---

# 👨‍💻 Author

**Manjunath Gowda**

Cloud & DevOps Engineer

### GitHub

https://github.com/Manjunath-rcb

### LinkedIn

https://www.linkedin.com/in/manjunath-gowda/

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Create a Pull Request

---

# ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.

---

# 📄 License

This project is intended for educational and learning purposes.

Feel free to fork, modify, and improve it.

---

## 🙏 Thank You

Thank you for visiting this repository.

Happy Learning & Happy Coding! 🚀
