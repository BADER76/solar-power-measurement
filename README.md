# 🌞 Solar Power Measurement System

This project monitors **solar panel voltage, current, and power** in real-time and visualizes the data using **ThingSpeak IoT cloud**. Built using the **STM32F103C8T6 (Blue Pill)** microcontroller, the system measures data using sensors and displays information on an **OLED screen**.

---

## 📌 Features

- 📟 Real-time Voltage, Current, and Power display on OLED
- 📡 Data transmission to **ThingSpeak IoT cloud**
- 📊 Live chart monitoring (Voltage, Current, Power)
- 📂 CSV data log supported
- 🔌 USB or battery-powered

---

## 🧠 Main Controller

- **STM32F103C8T6 (Blue Pill)**

---

## 🔍 Sensors Used

- **Voltage Sensor** (Resistor Divider)
- **Current Sensor** (ACS712)

---

## 📺 Display

- **0.96" OLED Display** (I2C protocol)

---

## 🌐 Cloud Platform

- **ThingSpeak** (for live data visualization)



---

## 🔧 Connections

| Component       | Pin on STM32 (Blue Pill) |
|----------------|---------------------------|
| Voltage Sensor | A0                        |
| Current Sensor | A1                        |
| OLED (SCL)     | B6                        |
| OLED (SDA)     | B7                        |
| ESP8266 TX     | A10                       |
| ESP8266 RX     | A9                        |
| GND/VCC        | GND / 3.3V                |

---

## 📂 Files in This Repo

- `main.c` – STM32 code to read sensors and transmit data
- `OLED_display_Code` – Functions to drive OLED screen
- `solar_data_logger.csv` – Sample data file
- `Final_Report.pdf` – Final project report
- `README.md` – This file
- Full STM32cubIDE file
---

## 📌 Future Enhancements

- ThingSpeak IoT cloud 
- Solar efficiency analytics
- ESP32-based standalone system

---

## 📜 License

This project is open-source under MIT License.
