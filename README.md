<!-- Repository Banner -->
<p align="center">
  <img src="img/banner.png" width="100%" alt="Project Banner" />
</p>

---

## 🔹 Overview  

A complete IoT-based greenhouse automation system built using **Cisco Packet Tracer**. This project simulates a real smart-agriculture environment with sensors, actuators, IoT servers, and a remote monitoring interface. The system automatically maintains ideal plant-growth conditions through environmental sensing, automation logic, and user-controlled IoT devices.
<p align="center">
  <img src="img/demo.gif" alt="water" width="1000px">
</p>
 
>Full system description referenced from project documentation.

---

## 🔹 Key Features

>### 🌡️ Environment Monitoring
- Temperature monitoring with heater/cooler control  
- Humidity detection with automated humidifier  
- Soil moisture sensing with automatic sprinklers  
- CO₂ level monitoring with exhaust fan activation  
- Fire detection with alarm + sprinkler response  

>### 💡 Facility Automation
- Smart lighting control  
- Smart door system with e-card authentication  
- CCTV camera simulation  
- Garage door automation  
- Water level monitoring  

>### 📡 IoT Connectivity
- All devices connected through Home Gateway  
- IoT Server + DNS for device registration  
- Web dashboard: `www.greenhouse.com`  
- Remote monitoring on laptop/smartphone  
- Wireless IoT network simulation  

---

## 🔹 Architecture

>## Project Structure

```bash
IoT-Greenhouse-Monitoring-System/
├── greenhouse_final.pkt
├── documentation/
│   └── WDN-Assignment-Group22.pdf
├── images/
    ├── architecture.png
    ├── soil-moisture.png
    ├── temperature-system.png
    ├── lighting-system.png
    ├── co2-system.png
    └── fire-system.png
```
>### Architecture Summary
<p align="center">
  <img src="img/diagram.png" width="100%" alt="water" />
</p>

---

## 🔹 System Workflow

>1. Sensors collect temperature, humidity, soil moisture, CO₂, and fire data  
>2. IoT devices send data to the IoT Server  
>3. Threshold values trigger actuators automatically
>4. User logs in to web portal for manual control  
>5. CCTV and smart door enhance security  
>6. Solar power system supports device power  

---

>### ▶️ How to Run (Cisco Packet Tracer)

1. Open `greenhouse_final.pkt`  
2. Click the laptop or smartphone  
3. Open the Web Browser  
4. Enter the URL:
5. Login:
```bash
Username: admin  
Password: admin  
```
>You can now view real-time sensor values, activate lights, open the smart door, or monitor sprinkler operations.

---

## 🔹 Components Used

### Sensors  
- Temperature sensor  
- Humidity sensor  
- Soil moisture sensor  
- CO₂ sensor  
- Smoke detector  

### Actuators  
- Heater & cooler  
- Sprinklers  
- Humidifier  
- Exhaust fan  
- Smart lights  
- Smart door  
- Alarm siren  

### Networking  
- IoT Server  
- DNS Server  
- Wireless Home Gateway  
- Laptop + Smartphone  

---

## 🔹 Future Improvements

- AI-powered plant-health prediction  
- Integration with real IoT hardware (ESP32 / Raspberry Pi)  
- Mobile app with notifications  
- Advanced water/soil chemistry sensors  
- Cloud dashboards (AWS IoT / Azure IoT)  

---

## 🔹 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

---

## 🔹 Citation

If you use this work, please cite:
```bash
Perera, H.A.K.D., Kasthuriarachchi, S.D. (2021). IoT Smart Greenhouse Monitoring System. Available at: https://github.com/sadeep654/IoT-Based-Greenhouse-Design (Accessed: date-you-accessed).
```

---

## 🔹 Authors

>- **Kasthuriarachchi, S.D.**  
>- **Perera, H.A.K.D.**
```bash
Copyright (c) 2020 Sadeep Dilshan Kasthuriarachchi
```

