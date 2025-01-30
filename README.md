# Permitron

## 🚀 Project Overview
Permitron is an AI-powered **parking enforcement system** that integrates **hardware, software, and machine learning** to automate parking permit validation. The system captures vehicle license plates using **Raspberry Pi cameras**, processes the images using **machine learning (OCR & OpenCV)**, and verifies permits against a **backend database**. Admins can review violations and manage permits through a **React-based dashboard**.

## 📌 Features
- **License Plate Recognition (LPR)** using OpenCV & Tesseract OCR
- **Raspberry Pi Camera System** for real-time image capture
- **Permit Validation System** with database integration
- **React Dashboard** for admin control & enforcement review
- **FastAPI / Node.js Backend** for managing API requests & ML model inference
- **Cloud Deployment** for scalable performance

## 🏗️ System Architecture
```
📂 Permitron
 ├── 📂 frontend/ (React + Next.js)
 ├── 📂 backend/ (FastAPI / Node.js)
 ├── 📂 ml_model/ (OCR & License Plate Recognition)
 ├── 📂 hardware/ (Raspberry Pi Scripts)
 ├── 📜 README.md (Project overview)
 ├── 📜 LICENSE
 ├── 📜 .gitignore
```

## 🔧 Tech Stack
### **Frontend**
- React (Next.js)
- Tailwind CSS
- WebSockets (for live updates)

### **Backend**
- FastAPI (Python) / Express.js (Node.js)
- PostgreSQL / MongoDB (Database)
- AWS S3 (for image storage)
- JWT Authentication

### **Machine Learning & Hardware**
- OpenCV & Tesseract OCR (License Plate Detection)
- Raspberry Pi 4 with Camera Module
- MQTT / WebSockets (for real-time communication)

## 📌 Setup Instructions
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-repo/permitron.git
cd permitron
```

### **2️⃣ Backend Setup**
```sh
cd backend
pip install -r requirements.txt  # If using Python FastAPI
npm install  # If using Node.js Express
```

### **3️⃣ Frontend Setup**
```sh
cd frontend
npm install
npm run dev
```

### **4️⃣ Running the Raspberry Pi Camera Script**
```sh
cd hardware
python camera_capture.py
```

## 📅 Project Milestones
- **Jan - Feb 2025**: Initial setup (hardware testing, ML model research, UI wireframing)
- **Mar - Apr 2025**: Core development (frontend, backend, ML model integration)
- **May - Jun 2025**: Testing & optimization (real-world deployment & debugging)

## 👥 Team Members
- **[Your Name]** - ML Engineer & System Integrator
- **[Frontend Developer]** - UI/UX & Dashboard Development
- **[Backend Developer]** - API & Database Management
- **[Hardware Engineer]** - Raspberry Pi & Camera Integration

## 📜 License
This project is licensed under the MIT License.

---
📌 **Need help?** Open an issue or reach out to the team! 🚀

