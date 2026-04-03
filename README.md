# 📦 Smart Dustbin (Arduino Based)

An intelligent waste segregation system using Arduino and sensors that automatically detects **wet and dry waste** and opens the corresponding dustbin lid using a servo motor.

---

## 🚀 Project Overview

The **Smart Dustbin** is an embedded system designed to automate waste segregation.

It uses a **soil moisture sensor** to classify waste as **wet or dry**, and a **servo motor** to open the correct bin automatically.

### 🌍 Why this project?
- Promotes clean environment  
- Supports smart city solutions  
- Reduces manual waste handling  

---

## ⚙️ Features

- ♻️ Automatic Wet/Dry Waste Detection  
- 🤖 Servo Motor Controlled Lid  
- 📊 Real-Time Moisture Monitoring  
- 🔌 Low Cost & Easy Implementation  
- 🧠 Beginner Friendly  

---

## 🛠️ Technologies & Components Used

### 💻 Software
- Arduino IDE  
- Embedded C / C++  

### 🔩 Hardware
- Arduino UNO  
- Soil Moisture Sensor  
- Servo Motor (SG90)  
- Jumper Wires  
- Breadboard  
- Power Supply  

---

## 🧠 How It Works

1. Moisture sensor reads waste moisture level  
2. Arduino processes analog value  
3. If value < threshold → Dry Waste  
4. If value ≥ threshold → Wet Waste  
5. Servo rotates:
   - 0° → Dry Bin  
   - 180° → Wet Bin  
6. Returns to neutral (90°)  

---

## 🔌 Circuit Diagram

![Circuit Diagram](./circuit.png)

---

## 🔗 Connections

### 🌱 Moisture Sensor
- VCC → 5V  
- GND → GND  
- AO → A0  

### ⚙️ Servo Motor
- VCC → 5V  
- GND → GND  
- Signal → Pin 9  

---

## 📥 Installation & Setup

### 1️⃣ Clone Repository

git clone https://github.com/Ankit-ku-panda/SmartDustbin.git
cd SmartDustbin

2️⃣ Install Arduino IDE

Download from: https://www.arduino.cc/en/software

3️⃣ Upload Code
Open .ino file
Select Board → Arduino UNO
Select Port
Click Upload
⚠️ Calibration

Adjust this value in code:

int dryThreshold = 500;
Steps:
Open Serial Monitor
Observe values for:
Dry waste
Wet waste
Set threshold between them
📈 Future Improvements
Ultrasonic sensor (auto lid open)
IoT integration (ESP8266 / Blynk)
Garbage level detection
Mobile app control
Dual servo system
📊 Applications
Smart Homes
Colleges / Schools
Public Waste Systems
Smart Cities
🤝 Contributing
Fork the repo
Create a branch
Make changes
Submit PR
📄 License

MIT License

👨‍💻 Author

Ankit Kumar Panda
🔗 https://github.com/Ankit-ku-panda

⭐ Support

If you like this project, give it a ⭐ on GitHub!
