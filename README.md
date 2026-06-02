# 🏥 AWS Eye Hospital EMR System (Serverless Cloud Project)

A fully serverless **Electronic Medical Records (EMR)** system built using AWS services.  
This project demonstrates a real-world healthcare application using **S3, DynamoDB, Lambda, API Gateway, and IAM**.

---

## 🚀 Live Demo
👉 (http://jeet-eye-hospital-emr-demo.s3-website-us-east-1.amazonaws.com)

---

# 📌 Project Overview

This EMR system is designed to manage:
- Patient records
- Doctor notes
- Appointments
- Secure authentication flow
- Cloud-based API integration

It follows a **serverless architecture** using AWS services for scalability and cost efficiency.

---

# 🏗️ Architecture Diagram

![Architecture](screenshots/architecture-diagram.png)

---

# ⚙️ AWS Services Used

### 🪣 Amazon S3
![S3 Bucket](screenshots/s3-bucket.png)  
![Static Hosting](screenshots/s3-static-website-hosting.png)

- Hosts the EMR frontend website
- Enables static website deployment

---

### 🗄️ Amazon DynamoDB
![DynamoDB Dashboard](screenshots/dynamodb-dashboard.png)

- Stores patient records, appointments, and doctor notes
- NoSQL scalable database

---

### ⚡ AWS Lambda
![Lambda Function](screenshots/lambda-create-function.png)  
![Lambda Test](screenshots/lambda-test-success.png)

- Handles backend logic for creating/retrieving data
- Serverless execution layer

---

### 🌐 API Gateway
![API Resources](screenshots/api-gateway-resources.png)  
![API Live Response](screenshots/api-gateway-live-response.png)

- Exposes REST APIs
- Connects frontend with Lambda backend

---

### 🔐 IAM Roles & Security
![IAM Policy](screenshots/iam-role-policy.png)

- Secure permissions for Lambda & DynamoDB access
- Role-based access control

---

# 👨‍⚕️ Application Modules

## 🧑‍⚕️ Login Page
![Login](screenshots/login-page.png)

---

## 📊 Dashboard
![Dashboard](screenshots/dashboard-page.png)

---

## 🧾 Patient Records
![Patient Records](screenshots/patient-records-page.png)

![Patients Table](screenshots/patients-table.png)

---

## 📅 Appointments
![Appointments Page](screenshots/appointments-page.png)

![Appointments Table](screenshots/appointments-table.png)

---

## 📝 Doctor Notes
![Doctor Notes Page](screenshots/doctor-notes-page.png)

![Doctor Notes Table](screenshots/doctornotes-table.png)

---

# 🌐 Deployment

## Public Website
![Live EMR System](screenshots/public-emr-website.png)

## System Working Proof
![Working System](screenshots/working-emr-system.png)

---

# 📁 Project Structure

```text
aws-eye-hospital-emr/
│
├── frontend/
    ├── css/
        ├── styles.css
├── js/
    ├── app.js
│
├── README.md
│
├── screenshots/
│   ├── architecture-diagram.png
│   ├── s3-bucket.png
│   ├── s3-static-website-hosting.png
│   ├── dynamodb-dashboard.png
│   ├── lambda-create-function.png
│   ├── lambda-test-success.png
│   ├── api-gateway-resources.png
│   ├── api-gateway-live-response.png
│   ├── iam-role-policy.png
│   ├── login-page.png
│   ├── dashboard-page.png
│   ├── patient-records-page.png
│   ├── patients-table.png
│   ├── appointments-page.png
│   ├── appointments-table.png
│   ├── doctor-notes-page.png
│   ├── doctornotes-table.png
│   ├── public-emr-website.png
│   ├── working-emr-system.png
```
---

# 📈 Key Features

- 🔐 Secure login system
- 📋 Patient management module
- 📅 Appointment scheduling system
- 📝 Doctor notes storage
- ⚡ Serverless backend (Lambda)
- 🌐 API-driven architecture
- ☁️ Fully cloud-hosted system

---

# 🚀 Learning Outcomes

- AWS S3 static hosting
- DynamoDB NoSQL database design
- Lambda serverless computing
- API Gateway REST API integration
- IAM role and security configuration
- End-to-end cloud application deployment

---

🏷️ Project Tags

AWS • Serverless • S3 • DynamoDB • Lambda • API Gateway • IAM • Cloud Computing • EMR System • Healthcare IT

---

🔗 Connect With Me

GitHub: https://github.com/jeetzala
LinkedIn: https://www.linkedin.com/in/jeet-zala-6633832ba/

---

🏆 Credits

Built by Jeet Zala as part of my AWS Cloud learning journey and portfolio development.

---

👨‍💻 Author

Jeet Zala
AWS Cloud Portfolio Project


