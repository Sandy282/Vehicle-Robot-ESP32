# 🚗 Autonomous Vehicle Robot using ESP32

This project is an autonomous vehicle robot built using **ESP32**, capable of obstacle avoidance and environment monitoring.

## 🔧 Components Used
- ESP32
- Ultrasonic Sensor (HC-SR04)
- DHT11 Temperature & Humidity Sensor
- LDR (Light Sensor)
- OLED Display (SSD1306)
- L298N Motor Driver
- DC Motors
- Robot Chassis

## ⚙️ Features
- Obstacle detection using ultrasonic sensor
- Automatic movement control
- Temperature & humidity monitoring
- Light intensity detection
- Real-time data display on OLED

## 📌 Pin Configuration
| Component | ESP32 Pin |
|---------|----------|
| DHT11 | GPIO 4 |
| Ultrasonic TRIG | GPIO 5 |
| Ultrasonic ECHO | GPIO 18 |
| LDR | GPIO 32 |
| OLED SDA | GPIO 21 |
| OLED SCL | GPIO 22 |

## ▶️ How to Run
1. Install required libraries:
   - Adafruit SSD1306
   - Adafruit GFX
   - DHT Sensor Library
2. Select **ESP32 Board** in Arduino IDE
3. Upload the code
4. Power the robot 🚀

## 📷 Output
OLED displays:
- Distance
- Light intensity
- Temperature
- Humidity

## 👨‍💻 Author
**Sandesh Ramdas Rathod**
