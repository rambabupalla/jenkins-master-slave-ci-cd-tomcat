Jenkins Master-Slave CI/CD Pipeline with Tomcat Deployment
Project Overview

This project demonstrates a complete CI/CD pipeline implementation using Jenkins Master-Slave architecture to automate the build and deployment of a Java web application to a remote Apache Tomcat server.

The build process runs on a Jenkins Slave node, and the deployment is performed automatically using SSH.

Infrastructure Setup

Three Linux virtual machines were created:

VM 1 – Jenkins Master

VM 2 – Jenkins Slave (Build Node)

VM 3 – Tomcat Server (Deployment Server)

All servers are connected through SSH.

Tools & Technologies

Jenkins (Pipeline + Nodes)

Apache Tomcat

GitHub

Maven

Linux

SSH

Java

CI/CD Workflow

Developer pushes code to GitHub

Jenkins pipeline starts

Build is executed on Jenkins Slave

WAR file is generated using Maven

Artifact is transferred using Publish Over SSH

Application is deployed to Tomcat

Application becomes live

Key Features

Configured Jenkins Master-Slave architecture

Implemented Pipeline-based CI/CD

Automated Java build using Maven

Remote deployment using SSH

Fully automated deployment process

Project Structure
.
├── Jenkinsfile
├── sample-app/
│   ├── pom.xml
│   └── src/
└── screenshots/

Screenshots

Add your screenshots inside the screenshots/ folder and reference them like this:

![Pipeline](screenshots/pipeline-success.png)
![Tomcat](screenshots/tomcat-deployment.png)

Outcome

Reduced manual deployment effort

Improved build consistency

Enabled automated CI/CD workflow

Implemented distributed build system
