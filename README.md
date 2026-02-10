Balloon Survival Game — CI/CD Deployment on Azure VM

A browser-based JavaScript game where the player controls a balloon and must avoid falling obstacles (stones). The game ends when the balloon collides with an obstacle.

The key objective of this project is to demonstrate a complete CI/CD pipeline that automatically deploys a web application to a Microsoft Azure Virtual Machine, following real-world DevOps practices.

🚀 Live Application

👉 Public Azure VM endpoint

http://131.163.81.38

🛠️ Technology Stack

Languages: HTML, CSS, JavaScript

Version Control: Git & GitHub

CI/CD Tool: GitHub Actions

Cloud Platform: Microsoft Azure

Deployment Target: Azure Virtual Machine (Linux)

Web Server: Nginx / Apache

🎮 Game Overview

Balloon survival gameplay

Random falling obstacles (stones)

Collision detection and game-over logic

Lightweight and browser-friendly design

⚙️ CI/CD Pipeline (Core Highlight)

This project implements a fully automated CI/CD pipeline using GitHub Actions to deploy the application on an Azure Virtual Machine.

Pipeline Workflow

Triggered on every push to the main branch

Builds and validates the frontend application

Uses secure SSH access to connect to the Azure VM

Deploys the latest build to the web server directory

Restarts the web server when required

This setup removes manual deployment steps and ensures consistent, reliable releases.

🔐 Security & Best Practices

SSH key-based authentication for VM access

Sensitive credentials managed using GitHub Secrets

Automated deployments reduce human error

📁 Project Structure
├── index.html
├── style.css
├── script.js
├── .github/
│   └── workflows/
│       └── ci-cd.yml
└── README.md

🧠 Key Learnings

Deploying web applications on Azure Virtual Machines

Designing CI/CD pipelines using GitHub Actions

Secure automated deployments with SSH

Applying DevOps principles to small-scale projects

📌 Future Enhancements

Add automated tests to the CI pipeline

Enable HTTPS using SSL/TLS

Improve game UI and animations

Add monitoring and logging on the Azure VM

👨‍💻 Author

Shivam
GitHub: (https://github.com/shivam58rai)
