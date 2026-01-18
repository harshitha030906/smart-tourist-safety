# Smart Tourist Safety Application 🚨🌍
A Flask-based web application designed to assist tourists during emergencies by providing instant access to nearby hospitals and police stations using real-time geolocation.

## 📌 Project Overview
The **Smart Tourist Safety Application** enables tourists to quickly seek help during emergencies through an **Emergency SOS** feature. The system detects the user's current location and displays the nearest hospitals and police stations.

The application follows a clean **Flask MVC architecture** with separate dashboards for **Tourists** and **Administrators**, making it scalable and easy to maintain.

## ✨ Features

- 📍 Real-time **geolocation tracking**
- 🚨 **Emergency SOS** for instant assistance
- 🏥 Displays nearby **hospitals and police stations**
- 👤 Dedicated **Tourist dashboard**
- 🛠️ **Admin dashboard** for managing datasets
- 🌆 Currently supports **3 cities** (extendable)


## 🛠️ Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **APIs:** GeoLocation APIs  
- **Data Source:** Excel-based datasets (`.xlsx`)  

## 📂 Project Structure
TOURIST-SAFETY-APP/
│
├── data/
│ └── dataset2.xlsx
│
├── static/
│ ├── css/
│ │ └── style.css
│ └── js/
│ ├── admin.js
│ └── script.js
│
├── templates/
│ ├── admin.html
│ ├── alert.html
│ ├── base.html
│ ├── home.html
│ └── tourist.html
│
├── tourist.py
├── requirements.txt
└── README.md

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
git clone https://github.com/harshitha030906/smart-tourist-safety.git
cd smart-tourist-safety

### 2️⃣ Create and activate a virtual environment 
python -m venv venv
venv\Scripts\activate

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 4️⃣ Run the application
python tourist.py

### 5️⃣ Open in browser
http://127.0.0.1:5000/
