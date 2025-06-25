🏠 Sinric Pro Home Automation
This project demonstrates a Wi-Fi-enabled Home Automation System using Sinric Pro and an ESP8266/ESP32 microcontroller. You can control appliances (like lights, fans, etc.) using Amazon Alexa, Google Assistant, or directly via the Sinric Pro mobile app.

🔧 Features
🔌 Control devices remotely via Alexa, Google Assistant, or Sinric Pro app

📱 Real-time status updates and two-way sync

🌐 OTA (Over-the-Air) firmware updates (optional)

🔒 Secure communication with Sinric Pro servers

💡 Works with ESP8266 and ESP32 boards

🧰 Hardware Used
✅ ESP8266 (NodeMCU) or ESP32 board

✅ 2/4/8-channel relay module

✅ 230V appliances (Bulb, Fan, etc.)

✅ Optional: DHT11/22, PIR Sensor, etc.

✅ Jumper wires, Breadboard

✅ 5V Power Supply

🧪 Software & Libraries
Arduino IDE (with ESP8266 or ESP32 board support)

Libraries:

SinricPro by Sinric

ESP8266WiFi or WiFi.h (depending on board)

ArduinoJson

ArduinoOTA (optional for OTA support)

📲 Sinric Pro Setup
Go to https://portal.sinric.pro

Create an account and log in.

Create a new device (e.g., Switch, Light, Fan).

Note down your:

APP_KEY

APP_SECRET

DEVICE_ID of each created device
