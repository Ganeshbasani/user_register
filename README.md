<div align="center">

# 🚀 AWS Serverless User Registration & Login System

![AWS](https://img.shields.io/badge/AWS-Serverless-orange?style=for-the-badge&logo=amazonaws)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![AWS Lambda](https://img.shields.io/badge/AWS-Lambda-FF9900?style=for-the-badge&logo=awslambda)
![API Gateway](https://img.shields.io/badge/API-Gateway-7B42BC?style=for-the-badge)
![DynamoDB](https://img.shields.io/badge/DynamoDB-NoSQL-4053D6?style=for-the-badge&logo=amazondynamodb)
![Amazon S3](https://img.shields.io/badge/Amazon-S3-569A31?style=for-the-badge&logo=amazons3)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

### 🔐 Secure • Scalable • Cloud-Native Authentication System

*A modern authentication system built using AWS Serverless technologies to provide secure user registration and login without managing backend servers.*

---

</div>

# 📖 Overview

The **AWS Serverless User Registration & Login System** is a cloud-native authentication application that enables users to securely register and log into a web application using AWS services.

Instead of using traditional backend servers, the application leverages **AWS Lambda**, **Amazon API Gateway**, **Amazon DynamoDB**, and **Amazon S3** to create a scalable, highly available, and cost-effective authentication platform.

This project demonstrates modern cloud architecture, REST API integration, serverless computing, and frontend-backend communication.

---

# ✨ Features

- 👤 User Registration
- 🔐 Secure Login Authentication
- ☁️ Fully Serverless Backend
- ⚡ REST API Integration
- 🗄️ Amazon DynamoDB Database
- 🌐 Static Website Hosting using Amazon S3
- 📱 Responsive User Interface
- 📊 CloudWatch Logging
- 🔒 IAM Security
- 📈 Auto Scaling
- 💰 Cost Efficient Architecture

---

# 🏗️ Solution Architecture

```text
                        User
                          │
                          ▼
        ┌────────────────────────────┐
        │ HTML • CSS • JavaScript UI │
        └────────────────────────────┘
                          │
                          ▼
                 Amazon API Gateway
                          │
              ┌───────────┴───────────┐
              ▼                       ▼
      Register Lambda          Login Lambda
              │                       │
              └───────────┬───────────┘
                          ▼
                  Amazon DynamoDB
```

---

# 📸 Application Preview

> Place the following screenshots inside the **screenshots/** folder.

## 🏠 Home Page

![Home](screenshots/home.png)

---

## 📝 Registration Page

![Register](screenshots/register.png)

---

## 🔑 Login Page

![Login](screenshots/login.png)

---

## ✅ Registration Successful

![Success](screenshots/success.png)

---

## 📊 User Dashboard

![Dashboard](screenshots/dashboard.png)

---

## 📱 Mobile Responsive View

![Mobile](screenshots/mobile.png)

---

# ⚙️ Technology Stack

| Category | Technology |
|----------|------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Python |
| Cloud Platform | Amazon Web Services |
| Compute | AWS Lambda |
| API | Amazon API Gateway |
| Database | Amazon DynamoDB |
| Storage | Amazon S3 |
| Monitoring | Amazon CloudWatch |
| Security | AWS IAM |

---

# ☁️ AWS Services Used

| Service | Description |
|----------|-------------|
| AWS Lambda | Executes backend business logic |
| API Gateway | Exposes REST API endpoints |
| DynamoDB | Stores user credentials |
| Amazon S3 | Hosts frontend website |
| IAM | Access & Permission Management |
| CloudWatch | Logs and Monitoring |

---

# 📂 Project Structure

```text
aws_register_login/

├── backend/
│   ├── register.py
│   ├── login.py
│   ├── requirements.txt
│   └── utils.py
│
├── frontend/
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   ├── css/
│   └── js/
│
├── infrastructure/
│   ├── template.yaml
│   ├── deployment.yml
│   └── cloudformation/
│
├── screenshots/
│   ├── home.png
│   ├── register.png
│   ├── login.png
│   ├── success.png
│   ├── dashboard.png
│   └── mobile.png
│
├── README.md
└── LICENSE
```

---

# 🔄 Application Workflow

```text
User Opens Website
        │
        ▼
Registration / Login Form
        │
        ▼
Amazon API Gateway
        │
        ▼
AWS Lambda Function
        │
        ▼
Amazon DynamoDB
        │
        ▼
Store / Retrieve User Information
        │
        ▼
Return Response
        │
        ▼
Display Success or Login Result
```

---

# 🔒 Security Features

- Secure REST APIs
- Input Validation
- AWS IAM Role-Based Permissions
- Serverless Security Architecture
- CloudWatch Monitoring
- Error Handling
- Scalable Infrastructure

---

# 📊 Key Features

| Feature | Status |
|----------|:------:|
| User Registration | ✅ |
| User Login | ✅ |
| REST APIs | ✅ |
| AWS Lambda | ✅ |
| DynamoDB | ✅ |
| Amazon S3 Hosting | ✅ |
| Responsive UI | ✅ |
| Cloud Deployment | ✅ |

---

# 📈 Benefits

- 🚀 Fully Serverless
- ⚡ High Performance
- 📈 Automatic Scaling
- 💰 Low Operational Cost
- 🔐 Secure Authentication
- ☁️ Cloud Native
- 🛠 Easy Deployment
- 🌍 Highly Available

---

# 🚀 Future Enhancements

- JWT Authentication
- Password Encryption
- Forgot Password
- Email Verification
- OTP Authentication
- AWS Cognito Integration
- Admin Dashboard
- User Profile Management
- Docker Deployment
- Terraform Support
- CI/CD Pipeline
- Multi-Factor Authentication (MFA)

---

# 📚 Learning Outcomes

This project demonstrates hands-on experience with:

- AWS Serverless Computing
- REST API Development
- Cloud Deployment
- DynamoDB Integration
- Lambda Functions
- API Gateway
- Frontend & Backend Integration
- Cloud Security
- Authentication Systems

---

# 🛠️ Installation

```bash
# Clone Repository

git clone https://github.com/Ganeshbasani/aws_register_login.git

# Move into project

cd aws_register_login
```

Deploy:

- Upload Lambda Functions
- Create API Gateway
- Configure DynamoDB Table
- Upload Frontend to Amazon S3
- Access the Hosted Website

---

# 👨‍💻 Author

## Ganesh Basani

**B.Tech – Computer Science & Engineering**

🌟 Aspiring Software Engineer | Cloud & Full Stack Developer

**GitHub:** https://github.com/Ganeshbasani

---

<div align="center">

## ⭐ Star this repository if you found it useful!

### Built with ❤️ using AWS Serverless Technologies

</div>
