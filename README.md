# 🔐 RFID-Based Door Lock System

## 📌 Overview
An embedded security system designed to control door access using RFID (Radio Frequency Identification) technology. The system allows only authorized RFID cards to unlock the door, ensuring secure and efficient access control.

---

## 🎯 Purpose
- Provide secure access using RFID authentication  
- Replace traditional lock systems with contactless technology  
- Demonstrate real-world embedded system implementation  

---

## ⚙️ Components Used
- Microcontroller (ESP32 / Arduino)  
- RFID Reader Module (RC522)  
- RFID Cards / Tags  
- Servo Motor (Door Lock Mechanism)  
- Buzzer  
- LEDs (Status Indicators)  
- Breadboard & Connecting Wires  

---

## 🔧 Working Principle
- RFID card is scanned using the RFID reader  
- Microcontroller reads the unique ID (UID) of the card  
- UID is compared with stored authorized IDs  
- If authorized:
  - Servo motor unlocks the door  
  - Green LED turns ON  
- If unauthorized:
  - Access is denied  
  - Buzzer alerts  
  - Red LED turns ON  

---

## 🎥 Demonstration
(Add your project video here)

---

## 💡 Key Features
- Contactless authentication system  
- Secure UID-based access control  
- Real-time response and feedback  
- Visual and audio alerts  
- Automated locking mechanism  

---

## 🧠 Learning Outcomes
- RFID technology and communication  
- Embedded system development  
- Hardware interfacing and integration  
- Security system design  
- Real-time system control  

---

## 📌 Applications
- Office and industrial access systems  
- Smart homes  
- Attendance systems  
- Security checkpoints  

---

## 🚀 Conclusion
This project demonstrates practical implementation of embedded systems, RFID-based authentication, and secure access control mechanisms for real-world applications.
