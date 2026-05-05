# CODEALPHA-bus-pass-system
# 🚌 Cloud-Based Bus Pass System (AWS + Flask)

A scalable and secure cloud-based bus pass & ticket booking system designed to eliminate ticket loss, prevent fraud, and handle high traffic efficiently.

---

## 📌 Project Overview

This project is a cloud-hosted web application that allows users to book bus tickets online and generate a **digital bus pass**. The system ensures security, scalability, and reliability using cloud computing principles.

---

## 🎯 Objectives

- Develop an online ticket booking system hosted on the cloud  
- Prevent ticket loss, duplication, and theft  
- Ensure accurate pricing without manipulation  
- Handle high traffic using scalable architecture  
- Provide seamless booking experience for users  

---

## ✨ Key Features

- 🧾 **Digital Bus Pass System** (No physical tickets required)  
- 🔐 **Secure Authentication System**  
- 💰 **Accurate Fare Calculation System**  
- 📊 **Admin Dashboard** for monitoring users and bookings  
- ☁️ **Cloud Deployment (AWS EC2)**  
- ⚡ **High Availability & Reliability**  
- 🔄 **Scalable Architecture for High Traffic Handling**  

---

## 🏗️ System Architecture

User → Web Interface → Flask Backend → MySQL Database → Cloud Server (AWS EC2)

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** Python (Flask)  
- **Database:** MySQL  
- **Cloud:** AWS EC2  
- **Tools:** Git, GitHub  

---

## 🔐 Security Features

- Protection against ticket duplication  
- Secure user authentication  
- Data validation to prevent incorrect pricing  
- Basic protection against common vulnerabilities  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/your-username/bus-pass-system.git
cd bus_pass_system  

2. Create a virtual environment
python -m venv myenv
source myenv/bin/activate   # Linux
myenv\Scripts\activate      # Windows

3. Install dependencies
pip install -r requirements.txt

4 .Setup MySQL Databse
Create a database (e.g., buspassdb)
Import schema if available
5. Configure Databse
MYSQL_HOST = 'localhost'
MYSQL_USER = 'root'
MYSQL_PASSWORD = 'your_password'
MYSQL_DB = 'buspassdb'
6. Run the application
python app.py
<img width="1920" height="1080" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/54cc9e03-12b9-49b7-8674-6bf78b4df30f" />
<img width="1920" height="1080" alt="Screenshot (85)" src="https://github.com/user-attachments/assets/d4b41a3e-373c-4c64-ac36-f2d6d89a58d0" />
<img width="1920" height="1080" alt="Screenshot (84)" src="https://github.com/user-attachments/assets/99e7b392-eff5-4b3f-9acf-034c23a91b3b" />
<img width="1920" height="1080" alt="Screenshot (83)" src="https://github.com/user-attachments/assets/7a40b068-c12f-443c-9204-11e79de811ed" />


