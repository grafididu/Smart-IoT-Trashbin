# ♻️ CERBIN: Smart Trash Bin with IoT using ESP32  

## 📖 Project Description  
**CERBIN (Cerdas Bin)** is a **smart trash bin** system designed to **classify and separate plastic and metal waste** using **ESP32** and **IoT** technology. The system rewards users with points when they dispose of waste correctly, which can be redeemed through a dedicated **web platform (cerbin.my.id)**.  

## 🎯 Objectives  
✔️ Encourage people to dispose of waste properly  
✔️ Implement **IoT-based waste classification**  
✔️ Provide an **automated reward system** for waste disposal  

## 🏗️ System Components  
### 🔹 **Hardware**  
- **ESP32**: Main microcontroller for processing data  
- **ESP32-CAM**: Captures QR codes for user authentication  
- **Ultrasonic Sensor HC-SR04**: Detects the presence of waste  
- **Inductive Proximity Sensor**: Identifies material type (plastic/metal)  
- **Servo Motor**: Sorts waste into the correct bin  
- **LCD 16x2**: Displays system status and user information  
- **Keypad Membrane 4x4**: Allows manual input of user ID  

### 🔹 **Software & Technologies**  
- **Arduino IDE**: Development environment for ESP32 firmware  
- **ESP-NOW Protocol**: Enables communication between ESP32 and ESP32-CAM  
- **HTTP Requests**: Sends waste classification data to a web server  
- **Web Dashboard (cerbin.my.id)**: Tracks user points and waste disposal history  

## 📂 Project Structure  
📦 CERBIN-Smart-Bin ├── 📁 firmware # ESP32 and ESP32-CAM firmware code ├── 📁 web # Web application source code ├── 📁 schematics # Circuit and system design files ├── 📄 README.md # Project documentation
