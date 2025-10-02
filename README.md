# 🌌 Exo Planet Finder

A full-stack web application for exoplanet research and citizen science collaboration.  

## 🚀 Features
- User Authentication (Login/Register with JWT)
- Dashboard with role selection:
  - **Citizen Scientist** → Chatbot with text & voice input + CSV upload
  - **Researcher** → Input KOI dataset, Upload CSV, Train AI Model
- Sidebar navigation with:
  - Dashboard
  - Citizen Scientist
  - Researcher
  - User Info
  - Password Update
  - Logout

## 🛠️ Tech Stack
- **Frontend** → HTML, CSS, JavaScript, Bootstrap
- **Backend** → Node.js, Express.js, MongoDB
- **Authentication** → JWT
- **File Uploads** → Multer
- **CSV Handling** → json2csv

## 📦 Setup
```bash
git clone https://github.com/Jishu3217/exo-planet-finder.git
cd exo-planet-finder/backend
npm install
node server.js
