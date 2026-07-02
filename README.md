<div align="center">

# 🚀 AWS Serverless User Registration & Login System

<p>
A secure, scalable, and serverless authentication system built using AWS cloud services. This project demonstrates how modern web applications can implement user registration and login using AWS Lambda, API Gateway, DynamoDB, and Amazon S3 without managing traditional servers.
</p>

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Lambda](https://img.shields.io/badge/AWS-Lambda-yellow)
![API Gateway](https://img.shields.io/badge/API-Gateway-red)
![DynamoDB](https://img.shields.io/badge/DynamoDB-NoSQL-blue)
![S3](https://img.shields.io/badge/Amazon-S3-green)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

# 📌 Overview

This project is a cloud-native authentication system that enables users to securely register and log in through a responsive web interface. It leverages AWS Serverless technologies to provide high availability, scalability, and cost efficiency without managing backend infrastructure.

The application follows a REST-based architecture where the frontend communicates with AWS Lambda functions through API Gateway, and user information is securely stored in DynamoDB.

---

# ✨ Features

- 👤 User Registration
- 🔐 Secure User Login
- ☁️ Fully Serverless Architecture
- ⚡ Fast REST API using API Gateway
- 🗄️ DynamoDB Database Integration
- 🌐 Static Website Hosting on Amazon S3
- 📱 Responsive Frontend
- 📊 Scalable Cloud Infrastructure
- 🔒 Secure API Communication
- 📜 CloudWatch Logging Support

---

# 🏗️ Architecture

```
                    User
                      │
                      ▼
          Frontend (HTML, CSS, JavaScript)
                      │
                      ▼
              Amazon API Gateway
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
 Registration Lambda        Login Lambda
          │                       │
          └───────────┬───────────┘
                      ▼
                Amazon DynamoDB
```

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python |
| Cloud Platform | AWS |
| Compute | AWS Lambda |
| API | API Gateway |
| Database | DynamoDB |
| Storage | Amazon S3 |
| Monitoring | CloudWatch |

---

# 📁 Project Structure

```
aws_register_login/

├── backend/
│   ├── Register Lambda
│   ├── Login Lambda
│   └── Backend Logic
│
├── frontend/
│   ├── Login Page
│   ├── Registration Page
│   ├── CSS
│   └── JavaScript
│
├── infrastructure/
│   ├── Deployment Files
│   ├── Cloud Resources
│   └── Configuration
│
├── screenshots/
│   └── Project Screenshots
│
└── README.md
```

---

# ⚙️ Workflow

```
User Opens Website
        │
        ▼
Registration/Login Form
        │
        ▼
API Gateway
        │
        ▼
AWS Lambda
        │
        ▼
DynamoDB
        │
        ▼
Success Response
        │
        ▼
User Logged In
```

---

# 🔐 Security Highlights

- Input Validation
- REST API Architecture
- AWS IAM Role-Based Permissions
- Serverless Security Model
- Secure Data Storage
- CloudWatch Monitoring

---

# 🚀 Key Benefits

- Fully Serverless
- Cost Effective
- Highly Scalable
- Easy Deployment
- Minimal Infrastructure Management
- Cloud-Native Design
- Production-Ready Architecture

---

# 📸 Screenshots

Add screenshots of:

- 🏠 Home Page
- 📝 Registration Page
- 🔑 Login Page
- ✅ Successful Registration
- ☁️ AWS Lambda
- 🌐 API Gateway
- 🗄️ DynamoDB Table
- 📊 AWS Console

---

# 🌟 Future Enhancements

- JWT Authentication
- Password Encryption
- Email Verification
- Forgot Password
- OTP Authentication
- AWS Cognito Integration
- User Dashboard
- Admin Panel
- Docker Support
- CI/CD Pipeline

---

# 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

- AWS Serverless Computing
- REST API Development
- Cloud Architecture
- Backend Development
- Frontend Integration
- NoSQL Database Design
- Authentication Workflow
- Cloud Deployment

---

# 👨‍💻 Author

**Ganesh Basani**

B.Tech Computer Science & Engineering

GitHub: https://github.com/Ganeshbasani

---

<div align="center">

⭐ If you found this project helpful, consider giving it a star!

</div>
