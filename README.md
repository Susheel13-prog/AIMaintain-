**AIMaintain+**__
AI-Powered Predictive Maintenance & Smart Repair Assistance Platform

AIMaintain+ is an AI-driven platform designed to help industries and vehicle owners prevent unexpected breakdowns and costly downtimes.
It analyzes machine/vehicle logs, detects anomalies, predicts failures before they happen, and guides users toward quick repair solutions through an integrated chatbot and mechanic locator.

🚀 Features
🔮 Predictive Intelligence

Uses machine-learning models to forecast equipment or vehicle failures.

Analyzes historical and real-time telemetry data.

Generates severity-based alerts (Green / Yellow / Red).

⚠️ Anomaly Detection

Flags unusual patterns and performance degradation.

Helps operators take preventive action early.

🤖 Smart Assistance

Built-in AI chatbot for troubleshooting steps.

Instant repair suggestions and DIY guidance.

🗺️ Mechanic Locator

Shows nearby mechanics for rapid issue resolution.

Map navigation and contact support.

📊 Modern Dashboard

Responsive UI using React + Tailwind CSS.

Live KPIs, charts, device health metrics, and recent anomalies.

📁 CSV Log Upload

Upload machine/vehicle logs directly.

Instant backend analysis + prediction.

🏗️ Tech Stack
Frontend

React

Tailwind CSS

Framer Motion

Axios

Backend

Python Flask

Flask-CORS

MySQL / SQLite

REST API architecture

Machine Learning

scikit-learn

Pandas

Joblib

Deployment

Frontend: Vercel / Netlify

Backend: Railway / Render

Database: MySQL (cloud)

📁 Project Structure
AIMaintain+/
│
├── frontend/               # React + Tailwind UI
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Dashboard, Upload, Login, etc.
│   │   ├── api/            # Axios API utils
│   │   └── assets/         # Images, icons
│   └── package.json
│
├── backend/                # Flask API
│   ├── app.py              # Main backend server
│   ├── routes/             # API routes
│   ├── models/             # ML model loader, prediction logic
│   ├── database/           # MySQL connection
│   └── requirements.txt
│
├── ml/
│   ├── train.py            # Train ML model
│   ├── preprocess.py       # Data preprocessing logic
│   └── model.joblib        # Saved trained model
│
├── data/
│   └── sample_logs/        # Sample CSV logs
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/AIMaintainPlus.git
cd AIMaintainPlus

Install dependencies
pip install -r requirements.txt

Run the backend
python app.py

Backend runs at:
http://localhost:5000
