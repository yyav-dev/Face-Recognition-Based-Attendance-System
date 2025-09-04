# 📌 Face Recognition Based Attendance System

A web-based attendance management system that uses Face Recognition to automate attendance marking. Built with Flask (Python) for the backend and Excel (openpyxl/pandas) for storing attendance records.

## 🚀 Features

🔹 Real-time face detection & recognition using OpenCV and face-recognition library.

🔹 Flask-based web interface for user interaction.

🔹 Automatic attendance marking once the face is recognized.

🔹 Attendance records stored and managed in Excel sheets.

🔹 Easy to generate reports and export data.

## 🛠️ Tech Stack

Frontend: HTML, CSS (Flask templates)

Backend: Python (Flask)

Libraries: OpenCV, face-recognition, numpy, pandas/openpyxl

Database: Excel sheets (.xlsx)

## 📂 Project Structure
```bash
Face-Recognition-Attendance/
│── app.py                # Main Flask application
│── requirements.txt      # Required Python libraries
│── static/               # CSS, JS, images
│── templates/            # HTML files for Flask
│── dataset/              # Stored face images of users
│── attendance/           # Excel files for attendance records
└── README.md             # Project documentation
```

## ⚙️ Installation

### Clone the repository
```bash
git clone https://github.com/yyav-dev/Face-Recognition-Based-Attendance-System.git
cd Face-Recognition-Based-Attendance-System
```

### Install Dependencies
```
pip install -r requirements.txt

```
### Run the Flask App
```
python app.py

```
(OR)
```
flask run
```
### Open in browser:
```
http://127.0.0.1:5000/
```
## 📊 How It Works

- Register users by storing their images in the dataset/ folder.

- Flask app uses OpenCV & face-recognition to train and match faces.

- When a face is detected, attendance is marked automatically.

- Records are saved in Excel file inside the attendance/ folder.
