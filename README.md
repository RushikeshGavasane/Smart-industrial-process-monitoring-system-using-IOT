# Smart-industrial-process-monitoring-system-using-IOT

This project is an **IoT-based industrial monitoring system** designed to enhance safety, automation, and efficiency in industrial environments. It enables real-time data acquisition, remote monitoring, and alert generation using a combination of sensors, microcontrollers, and IoT platforms.

## 🚀 Features

- 📡 Real-time monitoring of industrial parameters (temperature, gas, etc.)
- 📲 Wireless data transmission using Wi-Fi (ESP8266/NodeMCU)
- 🔔 Alert notifications on abnormal conditions
- 💾 Data logging and visualization via cloud platforms (e.g., ThingSpeak)
- ⚙️ Easy integration with industrial systems

## 🧰 Components Used

- **Microcontroller:** NodeMCU (ESP8266)
- **Sensors:**
  - MQ-2 (Gas/Smoke sensor)
  - DHT11/DHT22 (Temperature & Humidity sensor)
- **IoT Platform:** ThingSpeak (or any compatible platform)
- **Other:**
  - Power supply
  - Breadboard and jump wires

## 🔧 How It Works

1. Sensors collect real-time data from the environment.
2. The microcontroller processes the sensor data.
3. Data is transmitted via Wi-Fi to the IoT platform.
4. Users can view data on the dashboard and receive alerts if thresholds are breached.


## 📷 Images

*Add images of your hardware setup, circuit diagram, and platform dashboard here.*

## 🛠️ Setup Instructions

### 1. Hardware Setup:
- Connect sensors to NodeMCU as per the circuit diagram.
- Ensure proper power supply and stable Wi-Fi connectivity.

### 2. Software Setup:
- Use Arduino IDE or PlatformIO for programming the ESP8266.
- Install required libraries:
  - `DHT`
  - `ESP8266WiFi`
  - `ThingSpeak`
- Upload the code to NodeMCU.

### 3. Cloud Configuration:
- Create a ThingSpeak channel.
- Add fields for each sensor value.
- Get the API key and add it in the code.




