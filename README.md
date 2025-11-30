### **Embedded Systems & IoT Developer**

Passionate about building real-world embedded solutions, working with microcontrollers, and developing IoT devices.

---


## 🧑‍💻 About Me
- 🎓 Bachelor's degree in Computer Engineering  
- 🔧 Focused on Embedded Systems, IoT, and low-level programming  
- 🚀 Experienced with ESP32, NodeMCU, and Arduino-based IoT projects  
- 📡 Interested in signal processing, microcontrollers, and communication interfaces  
- 📘 Currently learning STM32 development and advanced firmware design  

---


## ✈️ Current Project: ADS-B Transceiver System  
Developing firmware for an ADS-B (Automatic Dependent Surveillance–Broadcast) receiver and transmitter system using STM32 microcontrollers for Viratak company.  
Focused on communication interfaces, embedded processing, and real-time data handling.

---


## 🛠 Skills

### **Embedded Systems**
- STM32 (ARM Cortex-M family)
- C / C++
- UART / SPI / I2C / Ethernet
- Embedded TCP/UDP server implementation
- Low-level firmware development

### **IoT Development**
- ESP32 / NodeMCU
- Arduino IDE
- Blynk

### **Tools**
- CLion  
- STM32CubeMX  
- STM32CubeIDE  
- Git & GitHub  

---

## 📫 Contact
- **Email:** mohammadh_mahmoudi81@gmail.com
- **LinkedIn:** www.linkedin.com/in/mohammadhossein-mahmoodi-403094242  

---

Thanks for visiting my profile! 😊


# IoT Health Monitoring System

A comprehensive real-time health monitoring system using NodeMCU (ESP8266) and multiple sensors, with cloud connectivity through Blynk platform.

## System Overview

This project implements an IoT-based health monitoring solution that tracks vital signs and patient location in real-time. The system collects data from multiple sensors, processes it using a NodeMCU microcontroller, and transmits the information to the Blynk cloud platform for visualization and analysis.

## Hardware Components

### Microcontroller
- **NodeMCU ESP8266** - Main processing unit with built-in WiFi capability

### Sensors
1. **DS18B20** - Digital temperature sensor
   - Measures body/ambient temperature
   - One-wire digital communication
   
2. **MAX30102** - Heart rate and SpO2 sensor
   - Monitors heart rate (BPM)
   - Measures blood oxygen saturation levels
   - I2C communication protocol
   
3. **MPU6050** - 6-axis gyroscope and accelerometer
   - Detects motion and activity
   - Fall detection capability
   - I2C communication protocol
   
4. **GPS NEO-6M** - GPS module
   - Tracks real-time location coordinates
   - Serial UART communication

### Network Components
- WiFi Router/Modem for internet connectivity
- Blynk Cloud Server for data storage and processing

## System Architecture

```
[Sensors] → [NodeMCU] → [WiFi] → [Router] → [Internet] → [Blynk Cloud] → [Dashboard]
```

### Data Flow
1. **Data Acquisition**: Sensors continuously collect health metrics
2. **Processing**: NodeMCU processes sensor data and performs necessary conversions
3. **Transmission**: Data is sent via WiFi to the local router
4. **Cloud Upload**: Information is transmitted over the internet to Blynk servers
5. **Visualization**: Real-time data displayed on Blynk mobile/web dashboard

## Features

- ✅ Real-time temperature monitoring
- ✅ Continuous heart rate and SpO2 tracking
- ✅ Motion detection and fall alerts
- ✅ GPS location tracking
- ✅ Cloud-based data storage
- ✅ Mobile and web dashboard access
- ✅ Historical data analysis
- ✅ Alert notifications

## Software Requirements

### Development Environment
- Arduino IDE or PlatformIO
- ESP8266 Board Package
- Required Libraries:
  - OneWire (for DS18B20)
  - DallasTemperature (for DS18B20)
  - MAX30105 (for MAX30102)
  - MPU6050 (for gyroscope)
  - TinyGPS++ (for GPS NEO-6M)
  - BlynkSimpleEsp8266 (for Blynk connectivity)
  - ESP8266WiFi

### Cloud Platform
- Blynk IoT Platform account
- Blynk mobile app (iOS/Android) or web dashboard

## Communication Protocols

- **I2C**: MAX30102, MPU6050
- **One-Wire**: DS18B20
- **UART**: GPS NEO-6M
- **WiFi**: 2.4 GHz 802.11 b/g/n
- **MQTT/REST API**: Blynk Cloud communication

## Dashboard Features

The Blynk dashboard provides:
- 📊 Real-time charts for all sensor data
- 🔔 Configurable alerts and notifications
- 📍 GPS map showing current location
- 💾 Historical data storage and analysis
- 📱 Mobile and web interface access

## Use Cases

- Remote patient monitoring
- Elderly care and fall detection
- Fitness and activity tracking
- Health data logging
- Emergency alert system

## Installation & Setup

1. **Hardware Assembly**
   - Connect sensors to NodeMCU according to pin configuration
   - Ensure proper power supply for all components

2. **Software Configuration**
   - Install required libraries in Arduino IDE
   - Configure WiFi credentials
   - Set up Blynk authentication token
   - Upload code to NodeMCU

3. **Blynk Setup**
   - Create Blynk account
   - Configure dashboard widgets
   - Set up alert notifications

## Power Requirements

- Operating Voltage: 3.3V - 5V
- Recommended: USB power supply or 5V battery pack

## Future Enhancements

- [ ] ECG monitoring
- [ ] Blood pressure measurement
- [ ] Multiple patient support
- [ ] Machine learning for health predictions
- [ ] Emergency contact auto-notification
- [ ] Data encryption for security

## License

[Add your license here]

## Contributors

[Add contributor information]

## Contact

[Add contact information]

---

**Note**: This system is designed for educational and monitoring purposes. It is not a replacement for professional medical devices or medical advice.



