🐾 Animal Intrusion Monitoring System
An AI-powered smart surveillance system that detects animal intrusion in farms, plantations, and restricted areas using Raspberry Pi, PIR sensors, and Deep Learning. The system captures images, identifies animals, and sends instant Telegram alerts to users.

Dataset Link: https://drive.google.com/drive/folders/1G1w57rr8-ZS8vRcBXNV5wmIlRkErSIqu?usp=sharing

🚀 Features


Real-time animal detection


PIR sensor-based motion triggering


AI-powered image classification


Telegram alert notifications


Confidence score display


Automatic image capture


Lightweight and cost-effective system



🛠️ Tech Stack


Python


Raspberry Pi


OpenCV


TensorFlow / YOLO


Telegram Bot API



🔧 Hardware Components


Raspberry Pi


PIR Motion Sensor


Raspberry Pi Camera Module


Jumper Wires


Breadboard


Power Supply



📌 Working


PIR sensor detects motion.


Raspberry Pi activates the camera.


Captured image is processed using the AI model.


Animal is identified with confidence score.


Telegram alert is sent with captured image.



📂 Project Structure
Animal-Intrusion-Monitoring-System/│── main.py│── model/│── images/│── alerts/│── requirements.txt│── README.md

⚙️ Installation
Clone the Repository
git clone https://github.com/your-username/Animal-Intrusion-Monitoring-System.gitcd Animal-Intrusion-Monitoring-System
Install Dependencies
pip install -r requirements.txt
Run the Project
python main.py

📲 Telegram Alert Example
🚨 ANIMAL INTRUSION ALERT 🚨Animal: ELEPHANTConfidence: 96.5%Time: 2026-05-03 21:30:00

🌟 Applications


Smart Agriculture


Farm Protection


Wildlife Monitoring


Rural Security Systems



🔮 Future Enhancements


Live video streaming


Mobile app integration


Cloud storage support


Multiple animal detection


Solar-powered deployment



👨‍💻 Author
Pranav P
Computer Science Engineering Student
Passionate about AI, IoT, and Smart Surveillance Systems
