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


## 🔧 How It Works  
1️⃣ **User Authentication**  
   - Users scan their **QR Code** (or manually enter ID via keypad).  
   - The system verifies user identity via a **web database**.  

2️⃣ **Waste Detection & Classification**  
   - The **ultrasonic sensor** detects the presence of waste.  
   - The **inductive sensor** classifies it as **plastic** or **metal**.  
   - The **servo motor** directs waste to the correct bin.  

3️⃣ **Reward System**  
   - Users earn points based on the waste type (**Plastic: +1 point, Metal: +2 points**).  
   - Points are updated **in real-time** on **cerbin.my.id**.  

## 📊 Testing & Results  
🔹 **System tested with multiple users and waste types**  
🔹 **Successful waste classification accuracy: 98%**  
🔹 **Real-time data updates on the web dashboard**  

## 📡 Installation & Usage  
1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/username/CERBIN-Smart-Bin.git
cd CERBIN-Smart-Bin
```
2️⃣ **Install Dependencies** 
```bash
pip install -r requirements.txt
```
3️⃣ **Upload Code to ESP32** 
- Open Arduino IDE
- Select ESP32 Board and upload firmware

## 🏆 Contributors 
👤 Alexius Andrianno Alfa R.  👤 Alif Akbar Grafidi  👤 Guruh Putra Nusantara  👤 Muhammad Afifudin Arsyada  👤 Naufal Farras Trikusuma  👤 Talitha Dwi Arini  📌 Supervisor: Agung Setia Budi, S.T., M.T., M.Eng., Ph.D.

🚀 **Developed for the Embedded System Course, Universitas Brawijaya.**
