# 🌱 Speak to Soil – Voice-Controlled Smart Irrigation System

**Speak to Soil** is an IoT-based smart irrigation solution that integrates voice control using Alexa and real-time soil moisture sensing through ESP32. The system automatically waters the plant when soil moisture drops below a threshold, and also allows the user to control the pump via voice commands through Amazon Alexa, making it a highly accessible and scalable precision agriculture tool.

---

## 📌 Project Summary

This project was developed as part of the MSc Cloud Computing dissertation. It is designed to help farmers or garden users manage irrigation intelligently using voice, sensors, and cloud-based automation. The prototype demonstrates a low-cost, accessible, and environmentally friendly solution for automated plant care.

---

## 🛠️ Technologies & Tools

- **Microcontroller**: ESP32  
- **Sensors**: Soil Moisture Sensor  
- **Cloud**: AWS Lambda, API Gateway, DynamoDB  
- **Voice Interface**: Amazon Alexa  
- **Programming**: Arduino IDE (C++), Python (for Lambda)  
- **Protocol**: MQTT (for real-time communication)

---

## 🚀 Features

- Real-time monitoring of soil moisture using analog sensors
- Voice control using Alexa (custom skill)
- Automatic watering based on soil moisture threshold
- Manual ON/OFF control via Alexa voice commands
- Data logging into AWS DynamoDB
- Modular system – expandable to multiple plants

---

## 📐 Architecture Diagram

_A simplified cloud-integrated architecture of the system:_

