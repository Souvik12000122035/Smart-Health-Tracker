# 🏥 Smart Health Tracker  

A web-based **Smart Health Tracker** with **Role-Based Access (Patient & Doctor)**, **Real-Time Wearable Integration**, and **Live Heart-Rate Monitoring** using WebSockets.  
This project helps track patient health, manage data securely, and provide doctors with real-time insights.  

---

## 🚀 Features  

- 👤 **Role-Based Users**  
  - **Patient**: View personal health data, track vitals.  
  - **Doctor**: Access assigned patients’ data, monitor live stats, give feedback.  

- ❤️ **Real-Time Heart-Rate Monitoring** (via WebSockets).  
- 📊 **Health Dashboard**: Charts for heart-rate, calories, steps, and more.  
- 🔒 **Secure Authentication** using Flask-Login.  
- 🧑‍🤝‍🧑 **Doctor-Patient Management** with role-based access control.  
- 🌐 **REST API Endpoints** for easy data integration.  

---

## 🛠 Tech Stack  

- **Backend**: Python (Flask, Flask-SocketIO)  
- **Frontend**: HTML, CSS, Bootstrap, JavaScript  
- **Database**: SQLite (can be replaced with MySQL/PostgreSQL)  
- **Realtime**: WebSockets (Flask-SocketIO)  
- **Visualization**: Chart.js  

---

## ⚙️ Setup & Installation  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/smart-health-tracker.git
   cd smart-health-tracker
