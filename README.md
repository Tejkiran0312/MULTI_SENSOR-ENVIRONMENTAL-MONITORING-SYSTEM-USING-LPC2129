# Multi-Sensor Environment Monitoring System Using LPC2129

## 📌 Project Overview

The **Multi-Sensor Environment Monitoring System Using LPC2129** is an embedded systems project designed to monitor environmental conditions using multiple sensors.

The system uses the LPC2129 ARM7TDMI-S microcontroller to collect sensor data, process the measured values, and monitor environmental conditions in real time.

By integrating multiple sensors, the system can monitor different environmental parameters and provide useful information about the surrounding environment.

## 🎯 Objectives

- To monitor multiple environmental parameters using sensors.
- To interface different sensors with the LPC2129 microcontroller.
- To collect and process sensor data.
- To display real-time sensor readings.
- To improve environmental monitoring through an embedded system.

## 🛠️ Hardware Requirements

- LPC2129 ARM7 Development Board
- Environmental Sensors
- 16x2 LCD Display
- Power Supply
- Connecting Wires
- Sensor Interface Circuits

## 💻 Software Requirements

- Keil µVision IDE
- Embedded C Programming
- Flash Magic (for programming the microcontroller)

## ⚙️ Working Principle

1. Multiple sensors collect environmental information.
2. The sensor outputs are connected to the LPC2129 microcontroller.
3. The LPC2129 reads analog sensor values using its built-in ADC wherever required.
4. The microcontroller processes the collected sensor data.
5. The measured values are displayed on the LCD.
6. The system continuously monitors the environmental conditions.

## 🧠 Microcontroller Used

**LPC2129 (ARM7TDMI-S)**

Key features used in this project:

- 32-bit ARM7TDMI-S processor.
- GPIO pins for sensor interfacing.
- 10-bit ADC for analog sensor readings.
- Timers for periodic operations.
- UART for serial communication.

## 📂 Project Structure

```text
Multi-Sensor-Environment-Monitoring-System/
│
├── source/
│   ├── main.c
│   ├── adc.c
│   ├── lcd.c
│   └── sensor.c
│
├── header/
│   ├── adc.h
│   ├── lcd.h
│   └── sensor.h
│
└── README.md
```

*Note: Modify the folder structure according to your actual project files.*

## 🚀 Applications

- Environmental monitoring systems.
- Industrial environment monitoring.
- Smart agriculture.
- Indoor environmental monitoring.
- Embedded monitoring applications.

## 🔮 Future Scope

- Add IoT connectivity for remote monitoring.
- Upload sensor readings to cloud platforms.
- Develop a mobile application for monitoring.
- Implement automatic alerts when sensor values exceed predefined limits.
- Store historical sensor data for analysis.

## 📚 References

- LPC2129 Microcontroller Datasheet.
- ARM7TDMI-S Technical Reference.
- Embedded C Programming.
- LPC2129 User Manual.

## 👨‍💻 Author

**Tejkiran**

Embedded Systems | ARM7 | LPC2129 | Embedded C

---
⭐ If you find this project useful, consider giving this repository a star!
