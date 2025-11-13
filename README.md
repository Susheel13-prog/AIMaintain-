**# AIMaintain+**

### AI-Powered Predictive Maintenance & Smart Repair Assistance Platform

AIMaintain+ is an AI-driven platform designed to help industries and vehicle owners prevent unexpected breakdowns and costly downtimes. It analyzes machine/vehicle logs, detects anomalies, predicts failures before they happen, and guides users toward quick repair solutions through an integrated chatbot and mechanic locator.

---

## 🚀 Features

### 🔮 Predictive Intelligence
- Uses machine-learning models to forecast equipment or vehicle failures.
- Analyzes historical and real-time telemetry data.
- Generates severity-based alerts (Green / Yellow / Red).

### ⚠️ Anomaly Detection
- Flags unusual patterns and performance degradation.
- Helps operators take preventive action early.

### 🤖 Smart Assistance
- Built-in AI chatbot for troubleshooting steps.
- Instant repair suggestions and DIY guidance.

### 🗺️ Mechanic Locator
- Shows nearby mechanics for rapid issue resolution.
- Map navigation and contact support.

### 📊 Modern Dashboard
- Responsive UI using React + Tailwind CSS.
- Live KPIs, charts, device health metrics, and recent anomalies.

### 📁 CSV Log Upload
- Upload machine/vehicle logs directly.
- Instant backend analysis + prediction.

---

## 🏗️ Tech Stack

### Frontend
- React
- Tailwind CSS
- Framer Motion
- Axios

### Backend
- Python Flask
- Flask-CORS
- MySQL / SQLite
- REST APIs

### Machine Learning
- scikit-learn
- Pandas
- Joblib

### Deployment
- Frontend: Vercel / Netlify
- Backend: Railway / Render
- Database: MySQL (cloud)

---

## 📁 Project Structure

AIMaintain+/
- frontend/
  - src/
    - components/
    - pages/
    - api/
    - assets/
  - package.json

- backend/
  - app.py
  - routes/
  - models/
  - database/
  - requirements.txt

- ml/
  - train.py
  - preprocess.py
  - model.joblib

- data/
  - sample_logs/

- README.md


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/Susheel13-prog/AIMaintain-

cd AIMaintain-

---

## 2️⃣ Backend Setup (Flask)

### Create virtual environment
cd backend
python -m venv venv
source venv/bin/activate


### Install dependencies
pip install -r requirements.txt

### Run the backend
python app.py

Backend will start at:
http://localhost:5000

---

## 3️⃣ Frontend Setup (React)

cd ../frontend
npm install
npm run dev

Frontend will start at:
http://localhost:5173

---

## 🔌 API Endpoints

### **POST /upload**  
Upload machine/vehicle logs.

**Body:** CSV file  
**Returns:** Parsed data summary

---

### **POST /predict**  
Run ML model on uploaded data.

**Returns (example):**
```json
{
  "failure_probability": 0.87,
  "severity": "high",
  "message": "Potential engine failure predicted within 72 hours."
}
POST /chat
Interact with AI assistant.

Example request:

json
Copy code
{ "message": "Engine making noise" }
Example response:

json
Copy code
{ "reply": "Please check the belt tension and coolant levels." }
📸 Screenshots
(Add your screenshot images inside /assets/screenshots)

bash
Copy code
/assets/screenshots/dashboard.png
/assets/screenshots/upload.png
/assets/screenshots/chat.png
🚧 Roadmap
✔️ Version 1.0 (MVP)
Frontend dashboard

Log upload

Basic ML prediction

Chatbot (rule-based)

Mechanic locator

📘 Version 2.0
Real-time telemetry (MQTT → WebSockets)

Advanced anomaly detection models (LSTM, Isolation Forest)

User roles: Admin, Technician, Operator

🚀 Version 3.0
Mobile App (Flutter)

Cloud IoT device integration

On-device inference for vehicles

🧪 Sample Demo Flow
User logs in

Uploads machine logs

System predicts failure risk

Dashboard highlights anomalies

User chats with AI assistant

System shows nearest mechanics

✨ Why AIMaintain+?
Prevent breakdowns before they occur

Reduce maintenance costs

Faster troubleshooting

Modular & scalable architecture

Usable for industries and vehicle owners

👨‍💻 Contributors
Team Code Geass (Vishal Shenoy K, Varun PV, Vejay Varun P)

Hackathon: Proyog

Domain: Digital-Physical Systems
