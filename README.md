# RC-Car-using-ESP32
MechaRush – An ESP32-powered RC Car controlled via FS-i4X transmitter, featuring BTS7960B motor drivers and Johnson motors.
# 🚗 MechaRush – ESP32-Based RC Car

**MechaRush** is a custom-built, high-performance **ESP32-powered Remote-Controlled Car** developed by **Team Trace X**. The project integrates high-torque Johnson DC motors, BTS7960B motor drivers, and FS-i4X wireless control to deliver precise, low-latency motion control. Safety and reliability are ensured through the use of an ESC with soft-start and overcurrent protection.

---

## 👨‍💻 Developed By
**Team Trace X**

---

## 🧰 Tech Stack
**ESP32, BTS7960B Motor Driver, FS-i4X Transmitter & Receiver, Johnson DC Motors, ESC, Li-ion Battery, Embedded Systems**

---

## 🔩 Components & Description

### 1. ESP32 Microcontroller
- Dual-Core 32-bit MCU @ 240 MHz  
- 4MB Flash, 520KB SRAM  
- Integrated Wi-Fi & Bluetooth  
- GPIO support: PWM, ADC, UART, SPI, I2C  

**Role:**  
Acts as the central control unit, processing receiver inputs and generating PWM signals for motor control.

---

### 2. BTS7960B Motor Driver
- Operating Voltage: 6V–27V  
- Continuous Current: 43A (Peak: 100A)  
- PWM Frequency: up to 25 kHz  
- Built-in overcurrent and thermal protection  

**Role:**  
Provides reliable high-current bidirectional motor control for Johnson DC motors.

---

### 3. FS-i4X Transmitter & Receiver
- Frequency: 2.4 GHz (AFHDS 2A)  
- 4-channel control  
- Operating range: ~500 meters  

**Role:**  
Enables wireless real-time user control for throttle and steering operations.

---

### 4. Johnson DC Motors
- Operating Voltage: 12V  
- Speed: ~900 RPM  
- High torque output  
- Current Draw: 0.5A–5A  

**Role:**  
Serves as the primary drive motors, providing strong torque and stable motion.

---

### 5. Electronic Speed Controller (ESC)
- Input Voltage: 6V–12V  
- Maximum Current: ~30A  
- PWM Control: 1 ms – 2 ms  
- Integrated BEC (5V/2A)  

**Role:**  
Ensures smooth acceleration, stable power delivery, and protects motors from electrical faults.

---

### 6. Supporting Hardware
- Rechargeable Li-ion Battery  
- DPDT Power Switch  
- Custom Controller Circuit  
- Jumper Wires & Breadboard  
- Wooden Chassis & Tyres  

**Role:**  
Provides mechanical structure, power management, and electrical interconnections.

---

## 📸 Project Media
- 🔹 **Front View:** [View Image](#)  
- 🔹 **Testing Video:** [Watch Video](#)  
- 🔹 **Track Run Video:** [Watch on Track](#)  

---

## ✨ Key Features & Highlights
- 🚀 Low-latency wireless control using FS-i4X  
- 🔁 Real-time PWM motor control via ESP32  
- 🔋 Efficient power handling using BTS7960B + Johnson motors  
- 🛡️ Enhanced safety with ESC soft-start & overcurrent protection  
- 🛠️ Modular and scalable hardware architecture  

---

## 🚀 Future Enhancements
- Wheel encoders for speed feedback  
- Wi-Fi / mobile app-based control  
- Obstacle detection using ultrasonic sensors  
- Autonomous navigation capabilities  

---

## 📎 License
This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements
- Open-source communities: Arduino, Espressif  
- Team Trace X collaborators  
- Inspiration from hobby-grade and competitive RC platforms
