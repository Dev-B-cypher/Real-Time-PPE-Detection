"# Real-Time-PPE-Detection-" 
# 🛡️ Real-Time PPE Detection with Email Alert System

This project detects the presence (or absence) of Personal Protective Equipment (PPE) like helmets, vests, and masks in real-time using computer vision techniques. Upon detecting a violation, it can send automatic alerts via email.

---

## 📸 Features

- Real-time PPE detection using webcam or video feed
- Deep learning model integration (YOLO/Ultralytics)
- Email alert system for PPE violations
- Lightweight and modular codebase
- Easy to configure and extend

---

## 📁 Project Structure

Real-Time-PPE-Detection/
├── detectors/ # YOLO, OpenCV models and scripts
├── email_alert/ # Email alert system integration
├── utils/ # Helper functions
├── main.py # Main entry point
├── requirements.txt # List of required libraries
└── README.md # You're here

yaml
Copy
Edit

---
## 📄 Project Report

👉 [Download PPE_Model_Report.pdf](./PPE_Model_Report.pdf)  
[![PDF Report](https://img.shields.io/badge/Download-Project_Report-blue.svg)](./PPE_Model_Report.pdf)


## ⚙️ Setup Instructions

### ✅ 1. Clone the Repository

```bash

git clone https://github.com/Dev-B-cypher/Real-Time-PPE-Detection.git
cd Real-Time-PPE-Detection
✅ 2. Create a Virtual Environment (Optional but Recommended)
bash
Copy
Edit
python -m venv .venv
Activate it:

Windows:

Copy
Edit
.venv\Scripts\activate
Linux/Mac:

bash
Copy
Edit
source .venv/bin/activate
✅ 3. Install Required Libraries
Use the provided requirements.txt file:

bash
Copy
Edit
pip install -r requirements.txt
✅ 4. Run the Program
bash
Copy
Edit
python main.py
Modify main.py or the appropriate script to configure webcam/video input or email settings.

📦 Major Dependencies
Some key libraries used in this project:

opencv-python

ultralytics (YOLO models)

cvzone

imutils

torch, torchvision, torchaudio

numpy, matplotlib, pandas, seaborn

filterpy, scikit-learn, scikit-image

📧 Email Integration
Ensure you configure your sender email and app-specific password inside the email module (usually in email_alert/ or a config file).

Commonly used libraries for email:

smtplib (built-in)

email (built-in)

⚠️ Notes
This project may require GPU acceleration for optimal performance with large models.

Tested on Python 3.9+. Check compatibility if using another version.

🧠 Contributions
Feel free to contribute via pull requests or open issues for improvements.

📄 License
This project is open-source and available under the MIT License.

yaml
Copy
Edit

---

Would you like me to include:
- Google Drive model link support?
- Screenshot placeholders or badges?
Let me know, I’ll update it!
