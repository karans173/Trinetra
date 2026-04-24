# 🚨 Trinetra – AI Crowd Safety System

### Real-Time Crowd Risk Detection using Vision + ML

**Tech Stack:** Python • XGBoost • ResNet • React Native • Node.js • MongoDB • REST APIs

---

## 📌 Overview

**Trinetra** is an AI-driven crowd safety and monitoring system that predicts footfall and detects potential crowd hazards in real time.

It combines **Computer Vision**, **Machine Learning**, and **real-time analytics** to help authorities prevent dangerous situations like stampedes before they occur.

### 🧩 The system consists of:

- 🎥 **AI-powered backend** for video-based crowd analysis  
- 📱 **Mobile app (React Native)** for field officers  
- 🖥️ **Admin dashboard** for monitoring & alerts  

---

## 📱 Mobile App Screenshots

<img width="964" height="716" alt="image" src="https://github.com/user-attachments/assets/824d2eb6-d65c-4656-ac93-bb211a93f8db" />


*The Trinetra mobile app enables on-ground officers to monitor live crowd flow, queue lengths, and risk predictions through a simple UI.*

---

## 🖥️ Temple Dashboard

<img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/53e769e1-2751-409f-965d-8ca5f20d464a" />


---

## ✨ Key Features

### 🧠 Computer Vision-Based Detection
- Uses **ResNet-50** to analyze CCTV/drone footage  
- Detects individuals and computes:
  - Crowd density  
  - Motion patterns  
- ~85% detection accuracy  

---

### 📊 Predictive ML Pipeline
- **XGBoost model** trained on 80+ engineered features:
  - Motion vectors  
  - Density metrics  
  - Frame variance  
  - Color entropy  
- Predicts crowd risk levels:
  - 🟢 Low  
  - 🟡 Moderate  
  - 🔴 High  
- ~75% prediction accuracy  

---

### ⚡ Real-Time Processing & Alerts
- Live data streaming via **WebSockets**  
- Instant alerts for high-risk scenarios  
- Integrated with mobile + dashboard  

---

### 📱 Mobile App (React Native)
- Live camera feed monitoring  
- Alert notifications  
- Risk level visualization  
- Optimized for low-bandwidth usage  

---

### 🖥️ Admin Dashboard
- Centralized monitoring system  
- Live analytics & heatmaps  
- Alert tracking & response management  

---

### 🔐 Secure APIs & Role-Based Access
- Built with **Node.js + Express**  
- Secure authentication system  
- Scalable and cloud-ready  

---

## 🏗️ System Architecture

<img width="896" height="535" alt="image" src="https://github.com/user-attachments/assets/eee0b589-0533-429e-8489-cc81008298fd" />


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/trinetra.git
cd trinetra
```

---

### 2️⃣ Backend Setup

```bash
cd services/backend
npm install
npm run dev
```

---

### 3️⃣ ML Service Setup

```bash
cd services/ai_service

python3 -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt
python app.py
```

---

### 4️⃣ Frontend (React Native App)

```bash
cd mobile
npm install
npx expo start
```

---

## 🤖 Machine Learning Details

| Component               | Description                   |
| ----------------------- | ----------------------------- |
| **Model**               | XGBoost Classifier            |
| **Features**            | 80+ engineered metrics        |
| **Vision Model**        | ResNet-50 (Transfer Learning) |
| **Prediction Accuracy** | ~75%                          |
| **Detection Accuracy**  | ~85%                          |

---

## 📊 Results

| Metric                    | Value     |
| ------------------------- | --------- |
| Vision Detection Accuracy | 85%       |
| ML Prediction Accuracy    | 75%       |
| Latency (per frame)       | ~120 ms   |
| Alert Delay               | < 1.5 sec |

---

## 🌍 Example Use Cases

* 🎪 Large public gatherings (festivals, concerts)
* 🏟️ Stadium crowd monitoring
* 🏙️ Smart city surveillance
* 🚨 Emergency crowd control

---

## 🚀 Future Improvements

* 🔌 Integration with IoT sensors (temperature, CO₂, sound)
* 📡 Edge deployment (Jetson Nano, Raspberry Pi)
* 📈 Advanced deep learning models for higher accuracy
* 🧭 Crowd flow direction prediction

---


