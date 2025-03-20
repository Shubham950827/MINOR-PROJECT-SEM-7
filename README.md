# MINOR-PROJECT-SEM-7

**Short Description:**  
This project is a **face recognition-based attendance system** built using **Flask, OpenCV, HTML, and MySQL**. It allows users to **register, log in, and mark attendance** using facial recognition. The system captures and stores user images, matches them during login, and records attendance automatically.

. Key Features
✅ User Registration – Users can sign up by entering their details and capturing their face.
✅ Face Recognition Login – The system verifies identity using OpenCV.
✅ Automated Attendance Marking – Attendance is recorded in a database or CSV file.
✅ Flask Web Interface – A user-friendly UI built with HTML, CSS.
✅ Database Storage – MySQL is used to store user details and attendance records.
✅ Real-Time Face Detection – Uses OpenCV to capture and process images.

🔹 Backend: Flask (Python)
🔹 Frontend: HTML, CSS, JavaScript (Bootstrap for styling)
🔹 Database: MySQL
🔹 Face Recognition: OpenCV, DeepFace

. How It Works
1️⃣ User Registration:

User enters name & ID.
Camera captures the face image and stores it.
2️⃣ User Login & Attendance:

Camera captures real-time face.
Compares with stored images using face recognition.
If matched, attendance is recorded in the database.
3️⃣ Data Storage:

User details and images are stored in MySQL.
Attendance logs are saved in a MYSQL or DATABASE.
