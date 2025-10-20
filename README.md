# 🌱 Soil Moisture Monitoring for Smart Irrigation

## 📘 Overview
This project implements an **IoT-based Smart Irrigation System** designed to monitor **soil moisture levels in real-time** and automatically control water flow using a **relay-driven pump**.  
Built using the **ESP32 microcontroller** and integrated with the **Blynk IoT platform**, this system ensures **efficient water usage**, **remote monitoring**, and **automated irrigation** — making it ideal for modern precision agriculture.

---

## 👩‍💻 Team Members
- **Pooja S Nair**
- **Nidhi T Aneesh**
- **Anvi Elsa Vijo**

**Branch:** S3 Electronics and Computer Engineering (ER)  
**College:** Saintgits College of Engineering  
**Date of Submission:** 17.10.2025

---

## 🚀 Features
- 🌾 **Automatic irrigation** based on real-time soil moisture readings.  
- 📶 **Wi-Fi enabled ESP32** for cloud connectivity.  
- 📊 **Live monitoring dashboard** using **Blynk IoT app**.  
- 💧 **Water conservation** by controlling irrigation precisely when needed.  
- 📱 **Manual control option** via Blynk for flexibility.

---

## ⚙️ Components Used
| Component | Function |
|------------|-----------|
| **ESP32** | Main microcontroller handling sensor input, logic, and Wi-Fi communication |
| **Soil Moisture Sensor** | Measures the moisture content in the soil |
| **Relay Module (1-Channel)** | Controls the water pump based on ESP32 signals |
| **DC Water Pump** | Waters the plants when activated |
| **Blynk IoT Platform** | Displays real-time data and allows remote pump control |

---

## 🧩 System Architecture
### Functional Blocks
1. **Input (Sensing)** – The soil moisture sensor measures soil water content.  
2. **Processing (Control & Communication)** – ESP32 processes the sensor data and communicates with Blynk via Wi-Fi.  
3. **Output (Actuation)** – Relay and DC pump operate automatically or manually depending on the conditions.

---

## 🔌 Circuit Connections
| Component | ESP32 Pin |
|------------|------------|
| Soil Moisture Sensor (AOUT) | VP / A0 |
| Relay Module (IN) | D2 |
| Relay VCC & GND | 3.3V & GND |
| Soil Sensor VCC & GND | 3.3V & GND |
| Water Pump | Connected to Relay (NO and COM terminals) |

---

## 📲 Blynk Integration
- Create a **Blynk Template** with two **Datastreams**:
  - **V0** – Soil Moisture Value (Input)
  - **V1** – Pump Control (Switch Widget)
- Use **Blynk Auth Token**, **Wi-Fi SSID**, and **Password** in the ESP32 code.

---

## 🧠 Expected Outcomes
✅ Real-time soil moisture data display on Blynk.  
✅ Automated pump activation at low moisture levels.  
✅ Manual pump control from mobile app.  
✅ Efficient water usage and minimal human intervention.  
✅ Demonstration of complete IoT workflow (sensor → ESP32 → cloud → actuator).

---

## 💡 Future Enhancements
- 🌤️ Integrate weather prediction for smarter irrigation scheduling.  
- 🔋 Add solar power for energy-efficient operation.  
- 🌐 Expand system to handle multiple zones or fields.

---

## 🧾 License
This project is open-source and available under the **MIT License**.  
Feel free to use, modify, and improve it!

---

## 📸 Preview


---![WhatsApp Image 2025-10-20 at 22 56 34_800b73a6](https://github.com/user-attachments/assets/875c137e-0254-4424-95ee-71bb46524f95)


### 🌿 “Smart irrigation isn’t just about watering plants — it’s about nurturing sustainability.” 🌿
