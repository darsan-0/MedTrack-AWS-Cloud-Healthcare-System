

---

# 🏥 MedTrack – AWS Cloud Healthcare System

### ☁️ Scalable Digital Healthcare Platform Powered by AWS

<p align="center">

<img src="https://img.shields.io/badge/Cloud-AWS-orange?style=for-the-badge&logo=amazonaws">
<img src="https://img.shields.io/badge/Backend-Python-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Framework-Flask-black?style=for-the-badge&logo=flask">
<img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-yellow?style=for-the-badge">
<img src="https://img.shields.io/badge/Database-SQLite-green?style=for-the-badge">
<img src="https://img.shields.io/badge/Cloud-DevOps-red?style=for-the-badge">

</p>

---

# 🌍 Project Overview

**MedTrack – AWS Cloud Healthcare System** is a **cloud-enabled medical management platform** designed to help hospitals, doctors, and patients manage healthcare data efficiently.

The platform demonstrates how **cloud computing and web technologies can modernize healthcare systems** by providing secure, scalable, and accessible patient data management.

This project integrates **Flask-based APIs with AWS cloud infrastructure** to simulate a real-world **cloud healthcare application**.

---

# 🚀 Key Features

## 👩‍⚕️ Patient Features

✔ Patient Registration & Login
✔ Book Doctor Appointments
✔ View Medical Records
✔ Track Health Reports
✔ Secure Patient Dashboard

---

## 👨‍⚕️ Doctor Features

✔ Doctor Authentication
✔ Manage Patient Records
✔ View Appointments
✔ Prescribe Treatments
✔ Monitor Patient Medical History

---

## ☁️ Cloud Features

✔ AWS Cloud Deployment
✔ Scalable Infrastructure
✔ Secure Medical Data Storage
✔ Cloud-based APIs
✔ High Availability Architecture

---

# 🧠 System Architecture

```
           Users (Patients / Doctors)
                     │
                     ▼
         Frontend (HTML | CSS | JavaScript)
                     │
                     ▼
          Backend API (Flask / Python)
                     │
                     ▼
               AWS Cloud Layer
                     │
        ┌────────────┼────────────┐
        │            │            │
        ▼            ▼            ▼
     AWS EC2      AWS S3       AWS RDS
 Application     Medical      Patient
  Hosting      File Storage   Database
        │
        ▼
     AWS IAM
 Authentication & Access Control
```

---

# 🛠️ Tech Stack

| Technology | Purpose                     |
| ---------- | --------------------------- |
| Python     | Backend logic               |
| Flask      | Web framework               |
| HTML       | Structure                   |
| CSS        | Styling                     |
| JavaScript | Client-side interaction     |
| SQLite     | Local database              |
| AWS EC2    | Application hosting         |
| AWS S3     | File storage                |
| AWS RDS    | Cloud database              |
| AWS IAM    | Security and access control |

---

# 📂 Project Structure

```
MedTrack-AWS-Cloud-Healthcare-System
│
├── app.py
├── requirements.txt
│
├── templates
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│
├── static
│   ├── css
│   │   └── style.css
│   ├── js
│   │   └── script.js
│
└── database
    └── medtrack.db
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/darsan-0/MedTrack-AWS-Cloud-Healthcare-System.git
```

---

## 2️⃣ Navigate to the Project Directory

```bash
cd MedTrack-AWS-Cloud-Healthcare-System
```

---

## 3️⃣ Install Required Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run the Application

```bash
python app.py
```

---

## 5️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

# ☁️ AWS Deployment Guide

Steps to deploy this project on AWS:

### 1️⃣ Create an EC2 Instance

* Launch **Ubuntu EC2 instance**
* Allow **Port 22 (SSH)** and **Port 5000 (HTTP)**

---

### 2️⃣ Connect to EC2

```bash
ssh -i key.pem ubuntu@your-ec2-ip
```

---

### 3️⃣ Clone the Repository

```bash
git clone https://github.com/darsan-0/MedTrack-AWS-Cloud-Healthcare-System.git
```

---

### 4️⃣ Install Python & Dependencies

```bash
sudo apt update
sudo apt install python3-pip -y
pip3 install -r requirements.txt
```

---

### 5️⃣ Run the Application

```bash
python3 app.py
```

---

### 6️⃣ Access via Public IP

```
http://your-ec2-public-ip:5000
```

---

# 📊 Future Enhancements

🚀 AI-Based Health Prediction
🚀 Video Telemedicine Integration
🚀 IoT Health Monitoring Devices
🚀 Blockchain Medical Records
🚀 Mobile App Integration
🚀 AI Doctor Recommendation System

---

# 🔐 Security Features

✔ Secure Authentication
✔ Role-based Access Control
✔ Cloud Infrastructure Security
✔ Data Protection Mechanisms

Healthcare systems must ensure **secure handling of sensitive patient information**, which is a core focus of this architecture.

---

# 📸 Screenshots

Add screenshots here:

```
/screenshots/home.png
/screenshots/dashboard.png
/screenshots/appointments.png
```

Example:

```
screenshots/
 ├── home.png
 ├── dashboard.png
 └── appointment.png
```

---

# 👨‍💻 Author

| Name              | Role      |
| ----------------- | --------- |
| **Darsan Mannem** | Developer |

GitHub:
[https://github.com/darsan-0](https://github.com/darsan-0)

---

# 🤝 Contributing

Contributions are welcome!

Steps:

```
1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request
```

---

# ⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
📢 Share with developers

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 💡 Vision

To build a **scalable, secure, and cloud-enabled healthcare ecosystem** that improves hospital efficiency and patient care through modern technology.

---

<p align="center">

🚀 **Transforming Healthcare with Cloud Technology**

</p>

---
