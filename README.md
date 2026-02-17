# Jenkins Master-Slave CI/CD Pipeline with Tomcat Deployment

## Project Overview
This project demonstrates the implementation of a complete **CI/CD pipeline** using **Jenkins Master-Slave architecture**.

The goal was to automate the **build and deployment** of a Java web application to a remote **Apache Tomcat server** using a distributed build system and **SSH-based deployment**.

---

## Technologies Used
- **Jenkins**
- **Apache Tomcat**
- **GitHub**
- **Maven**
- **Linux**
- **SSH**
- **Java**

---

## Infrastructure Setup

### 1. Virtual Machine Configuration
- Created **three Linux virtual machines**
- Configured **VM 1 as Jenkins Master**
- Configured **VM 2 as Jenkins Slave (Build Node)**
- Configured **VM 3 as Tomcat Deployment Server**
- Established secure **SSH connectivity** between servers

### 2. Jenkins Master-Slave Setup
- Installed **Jenkins** on Master server
- Configured **Slave node** using Jenkins Nodes
- Connected Slave using **SSH authentication**
- Verified **distributed build execution**

---

## CI/CD Pipeline Implementation

### 1. Source Code Integration
- Connected Jenkins with **GitHub repository**
- Created a **Pipeline project**
- Defined build stages in **Pipeline script**

### 2. Build Automation
- Executed **Maven build** on Jenkins Slave
- Generated **WAR artifact**
- Verified successful **build execution**

### 3. Automated Deployment
- Configured **Publish Over SSH plugin**
- Transferred **WAR file** to Tomcat server
- Deployed application to **Tomcat webapps directory**
- Verified successful **application deployment**

---

## CI/CD Workflow
1. Developer pushes code to **GitHub**
2. **Jenkins Pipeline** starts
3. Build runs on **Jenkins Slave**
4. **WAR file** is generated
5. Artifact transferred via **SSH**
6. Application deployed to **Tomcat**
7. Application becomes **live**

---

## Key Features Implemented
- **Distributed build architecture**
- **Pipeline-based CI/CD automation**
- Automated **WAR generation using Maven**
- Remote deployment using **SSH**
- Fully automated **deployment workflow**

---

## Screenshots
Screenshots of **pipeline execution**, **slave configuration**, and **Tomcat deployment** are available in the `/screenshots` folder.

---

## Learning Outcomes
- Hands-on implementation of **distributed Jenkins builds**
- Understanding of **CI/CD pipeline architecture**
- Experience with **automated remote deployment**
- Practical integration of **GitHub with Jenkins**
- Real-world **DevOps workflow implementation**

---

## Author
**Rambabu Palla**
