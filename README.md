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

### 📸 Screenshots

<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/e7655eec-6d35-425b-bb9d-6dc320e7317f" />
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/0b39c0f9-7d91-4055-a420-48553fa1c60f" />
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/e310f7d8-2062-4dec-a06a-a4065c157f86" />
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/ca1d5ba9-f99f-48c2-9a39-9e0d1b377f3c" />
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/8b7f788f-5be1-4936-9b3c-8f392bad451b" />
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/be67dd7d-3ed5-44c3-9ba3-3e3555a55517" />
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/a2562e50-8fbd-44c3-a0d9-a0cac423242d" />


