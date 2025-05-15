# ai-surveillance-system
“AI-based face recognition surveillance with real-time alerts”
# 🛡️ AI-Based Smart Surveillance System

This project is a smart AI-powered surveillance system that detects and recognizes human faces in real-time using a live video stream. It triggers alerts when unknown individuals are detected, and can optionally interface with IoT hardware like an ESP32 to activate alarms or control door locks.

---

## 🚀 Features

- 🎯 Real-time face detection using OpenCV
- 🧠 Face recognition using DeepFace
- 📩 Email alerts when an unknown face is detected
- 🔗 Optional IoT integration with ESP32 for alarms or door control
- 🌐 Flask-based web interface for live monitoring

---

## 🧰 Technologies Used

- Python
- OpenCV
- DeepFace / Dlib
- Flask
- face_recognition library
- SMTP (for email notifications)
- ESP32 (optional for IoT integration)

---

## 📁 Project Structure

ai-surveillance-system/
│
├── app.py # Main application script
├── dataset/ # Known faces dataset
├── templates/
│ └── index.html # Web UI template
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore

yaml
Copy
Edit

---

## ⚙️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-surveillance-system.git
   cd ai-surveillance-system
   
2. Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt


3. Run the application:
bash
Copy
Edit
python app.py

4. Open your browser and go to:
cpp
Copy
Edit
http://127.0.0.1:5000/



Example Output
The system will:

Display a live camera stream

Label known faces with their names

Capture and send alerts for unknown individuals

Example screenshot can be added here

🔮 Future Enhancements
Liveness detection to prevent spoofing

Cloud-based storage for face logs

WhatsApp or Telegram integration for alerts

Enhanced dashboard for viewing logs and events

👨‍💻 Author
Chethan Gowda R
GitHub Profile

📜 License
This project is licensed under the MIT License.
