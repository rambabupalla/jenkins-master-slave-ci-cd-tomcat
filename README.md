🚀 Jenkins Master-Slave CI/CD Pipeline with Tomcat Deployment
📌 Project Overview

This project demonstrates a complete CI/CD pipeline implementation using Jenkins Master-Slave architecture to automate the build and deployment of a Java web application to a remote Apache Tomcat server.

The build process runs on a separate slave node, and deployment is handled automatically using SSH.

🖥 Infrastructure Setup

Three Linux virtual machines were configured:

VM 1 – Jenkins Master

VM 2 – Jenkins Slave (Build Node)

VM 3 – Tomcat Server (Deployment Server)

All servers are connected through secure SSH communication.

🛠 Tools & Technologies Used

Jenkins (Pipeline + Nodes)

Apache Tomcat

GitHub

Maven

Linux

SSH

Java

🔄 CI/CD Workflow

Developer pushes code to GitHub

Jenkins Pipeline starts automatically

Build is executed on Jenkins Slave node

WAR file is generated using Maven

Artifact is transferred using Publish Over SSH

Application is deployed to Tomcat server

Application becomes live

🔥 Key Features

✅ Configured Jenkins Master-Slave architecture

✅ Implemented Pipeline-based CI/CD

✅ Automated Java build using Maven

✅ Remote deployment using SSH

✅ Fully automated deployment workflow

✅ Distributed build execution

📂 Project Structure
.
├── Jenkinsfile
├── sample-app/
│   ├── pom.xml
│   └── src/
└── screenshots/

📸 Screenshots

Add screenshots inside the screenshots/ folder and reference them like this:

![Pipeline Success](screenshots/pipeline-success.png)
![Tomcat Deployment](screenshots/tomcat-deployment.png)

📊 Project Outcome

Reduced manual deployment effort

Improved build reliability

Achieved consistent deployments

Implemented real-world CI/CD architecture

👨‍💻 Author

Rambabu Palla
DevOps & Linux Enthusiast
