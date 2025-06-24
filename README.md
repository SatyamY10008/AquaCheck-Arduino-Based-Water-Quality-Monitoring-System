# 📘 AquaCheck – Arduino-Based Water Quality Monitoring System #
AquaCheck is an Arduino-powered system designed for real-time monitoring of water quality. The system integrates multiple sensors to detect critical water parameters like pH, turbidity, temperature, and dissolved oxygen, offering an efficient and affordable way to analyze water conditions for environmental or agricultural applications.

🛠️ Tech Stack & Tools
Hardware: Arduino UNO, pH sensor, turbidity sensor, DS18B20 temperature sensor, DO (Dissolved Oxygen) sensor

Software: Arduino IDE, Embedded C, Serial Monitor, optional IoT platforms (e.g., Blynk, ThingSpeak)

*Libraries:*
OneWire.h (for DS18B20)
DallasTemperature.h
SoftwareSerial.h
LiquidCrystal_I2C.h (if LCD used)

*🔍 Features*
Real-time water quality monitoring
Displays live data on serial monitor / LCD
Threshold-based alert system (optional)
Modular and expandable design
Optional IoT integration for remote monitoring
