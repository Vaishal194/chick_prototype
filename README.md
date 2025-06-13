🐣 ChickMate – Real-Time Chick Counting System

> ChickMate is a software-based prototype developed to automate the process of chick counting in poultry farms using computer vision and AI. Powered by YOLOv8 and OpenCV, it provides real-time detection, tracking, and logging of chick counts using a webcam.




---

📌 Problem Statement

Manual chick counting during transfers or deliveries is error-prone, time-consuming, and labor-intensive. Inaccuracy leads to mismatched records, wastage of resources, and revenue loss.


---

💡 Solution

ChickMate replaces manual counting with an AI-powered system that:

Detects chicks in real-time using a webcam.

Tracks and counts each chick with high accuracy.

Logs counts with batch info, timestamps, and user data.

Offers a user-friendly web dashboard.



---

🚀 Key Features

✅ Real-time chick detection using YOLOv8 and OpenCV

✅ Web-based login & dashboard (Flask-based)

✅ Batch-wise data storage in SQLite

✅ Count logs with timestamps

✅ CSV export of batch data

✅ Live video feed with count overlay

✅ Lightweight and works offline



---

🛠 Tech Stack

Component	Technology

Frontend	HTML, CSS, Bootstrap
Backend	Flask (Python)
Database	SQLite
AI Model	YOLOv8 (custom trained)
CV Tools	OpenCV
Input Device	Webcam



---

📂 Folder Structure

ChickMate/
│
├── static/                  # CSS/JS files
├── templates/              # HTML templates
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── video_feed.html
│   ├── show_count.html
│   └── logout.html
│
├── best.pt                 # YOLOv8 custom-trained model
├── app.py                  # Main Flask app
├── users.db                # SQLite database (auto-created)
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies


---