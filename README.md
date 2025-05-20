# ⚖️ Nyaaya – EPortal for Case Management 

**Nyaaya** is a cutting-edge web-based platform designed to modernize the Indian judicial system by addressing inefficiencies in case registration, document management, and case progress tracking. By leveraging technology, Nyaaya streamlines processes for advocates, litigants, and court administration — fostering transparency, speed, and security.

---

## 📜 Problem Statement

Over **5.02 crore** cases are pending in Indian courts. Traditional offline systems are burdened by:
- Prolonged case registration times
- Ineffective document management
- Lack of real-time tracking for litigants

---

## ✅ Our Solution

Nyaaya provides a robust, user-friendly solution to:
- Enable **advocates** to manage cases seamlessly  
- Provide **litigants** with real-time case tracking and advocate selection  
- Empower **court administrators** to securely store and manage evidence and judgments  

---

## 🔍 Features

- 🔐 **Role-based Login**: Separate access for advocates, litigants, and administrators  
- 📝 **Case Filing and Tracking**: Full lifecycle management of cases  
- 📂 **Secure Document Uploads**: Centralized, role-specific access to case files  
- 👩‍⚖️ **Lawyer Profiles**: Search and connect with verified advocates  
- 🔔 **Real-time Notifications**: Instant updates for case progress  

---

## 🎯 Objectives

- Minimize manual processes and enhance efficiency  
- Centralize and protect sensitive legal data  
- Promote transparency and real-time communication  
- Ensure accuracy through standardized digital workflows  
- Deliver an intuitive and accessible user interface  

---

## 🧠 System Design & Workflow

### 👨‍💼 Advocates:
- Register with verified bar credentials  
- Manage client cases and upload documents  
- Access all assigned cases via unique case numbers  

### 👩‍💼 Litigants:
- Track the status of their cases  
- Search and connect with advocates  
- View court-approved documents securely  

### 🏛️ Court Administrators:
- Authenticate and update case records  
- Upload judgments and manage evidence securely  

---

## 🛠️ Technology Stack

### 🔧 Frontend
- HTML, CSS, JavaScript  
- Bootstrap  
- React.js  

### ⚙️ Backend
- Node.js  
- Express.js  

### 🗃️ Database
- MongoDB  

### 🧰 Tools
- Visual Studio Code  

---

## 💻 System Requirements

### Software
- OS: Windows 7/8/10  
- Node.js, MongoDB, Visual Studio Code  

### Hardware
- Processor: Intel Pentium Dual Core (2.9 GHz or higher)  
- RAM: 2 GB minimum  
- Storage: 2 GB minimum  

---

## 📚 Literature Survey

Nyaaya is inspired by digital legal platforms around the world:
- **Russia**: Judiciary portals for public awareness  
- **Ghana**: Case filing and assignment systems  
- **Australia**: Unified court management platforms  

---

## 🚀 How to Run Locally

### 📦 Prerequisites
- Node.js & npm installed  
- MongoDB running on default port (`27017`)  

### 🔄 Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/nyaaya.git
cd NyaayaG160

### 🖥️ Step 2: Setup Frontend
```bash
cd eportal
npm install
npm start

Open http://localhost:3000 in your browser.

🛠️ Step 3: Setup Backend
bash
cd ../server
npm install
node server.js

Backend runs on http://localhost:5000

⚙️ Step 4: Configure Environment Variables
Create a .env file inside the server/ folder with the following content:

ini
PORT=5000
MONGO_URI=mongodb://localhost:27017/nyaaya

🧪 Testing
✅ Functional Testing: User roles, case filings, document uploads

🔄 Integration Testing: Frontend-backend communication
