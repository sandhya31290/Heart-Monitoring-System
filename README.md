# 💓 Heart Monitoring System  

## 📌 Overview  
The **Heart Monitoring System** is an **IoT-based project** designed to **track and monitor heart rate** in real-time. This system helps detect **irregular heartbeats** and provides critical health insights, making it useful for **patients, doctors, and fitness enthusiasts**.  

## 🔧 Features  
- ✅ **Real-time heart rate monitoring**  
- ✅ **Alerts for abnormal heart rate**  
- ✅ **LCD display for live data**  
- ✅ **Data visualization for analysis**  
- ✅ **Secure and efficient data handling**  

## ⚙️ Components Used  
- 🔹 **Arduino Uno**  
- 🔹 **Pulse Sensor** (for detecting heartbeat)  
- 🔹 **LCD Display (16x2 with I2C module)**  
- 🔹 **Breadboard** (for wiring connections)  
- 🔹 **Jumper Wires** (for connections)  

## 🚀 How It Works  
1. The **pulse sensor** detects heart rate by measuring changes in blood flow.  
2. The **Arduino Uno** processes the sensor's data.  
3. The **LCD display** shows the live heart rate.  
4. If any irregularity is detected, the system can trigger alerts.  

## 🔌 Circuit Diagram  
![Circuit diagram](https://github.com/user-attachments/assets/3e174688-dbe0-4c3f-9c4a-4d11c0b9149c)
  

### 🛠 Connection Guide  
| Component       | Arduino Pin |  
|----------------|------------|  
| **Pulse Sensor** | **A0 (Signal), 5V (+), GND (-)** |  
| **LCD Display** | **SDA → A4, SCL → A5, VCC → 5V, GND → GND** |  

The **breadboard** is used to simplify connections, ensuring proper voltage distribution and secure wiring.

