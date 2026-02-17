🚀 Jenkins Master-Slave CI/CD Pipeline with Tomcat Deployment
📌 Project Overview

Designed and implemented a complete CI/CD pipeline using Jenkins Master-Slave architecture to automate build and deployment of a Java web application to Apache Tomcat.

🏗 Infrastructure Setup

3 Linux Virtual Machines:

Jenkins Master

Jenkins Slave (Build Node)

Tomcat Deployment Server

⚙️ Tools & Technologies

Jenkins (Pipeline + Nodes)

Apache Tomcat

GitHub

Maven

Linux

SSH

Java

🔄 CI/CD Workflow

Developer pushes code to GitHub

Jenkins pipeline triggers build

Build executed on Jenkins Slave node

WAR artifact generated using Maven

Artifact transferred using Publish Over SSH

Application deployed to Tomcat server

Application becomes live

🔥 Key Features

Distributed build architecture using Jenkins Nodes

Automated build and deployment process

Remote deployment using SSH

WAR-based application deployment

Fully functional CI/CD pipeline

📊 Outcome

Reduced manual deployment effort

Achieved consistent and automated deployments

Improved build and deployment reliability
