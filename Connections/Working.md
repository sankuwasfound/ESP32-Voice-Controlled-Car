## 📌 About This Project

The ESP32 Bluetooth Voice Controlled Car is a wireless robotic vehicle that can be controlled using voice or text commands sent from a smartphone via Bluetooth.

This project demonstrates practical implementation of:
- Embedded Systems
- Wireless Communication
- Motor Control using PWM
- Real-time command processing
- Robotics fundamentals

The ESP32 acts as the brain of the system, receiving commands over Bluetooth and controlling two DC motors through an L298N motor driver module.

This project is ideal for:
- Robotics enthusiasts
- Embedded systems learners
- Engineering mini-projects
- Fest demonstrations
- IoT-based control systems

---

## ⚙️ How It Works

1. The ESP32 initializes Bluetooth using the BluetoothSerial library.
2. A smartphone connects to the ESP32 via Bluetooth.
3. The user sends commands such as:
   - forward
   - back
   - left
   - right
   - stop
4. The ESP32 reads the incoming command.
5. Based on the command:
   - Motor direction pins are set HIGH/LOW.
   - PWM signals control motor speed.
6. The L298N motor driver amplifies the control signals.
7. The motors rotate accordingly, moving the car.

For speed control:
- The command format "speedXXX" (0–255) changes the PWM value.
- Higher value = faster rotation.
- Lower value = slower rotation.

Differential turning is implemented by varying left and right motor speeds for smoother directional control.

---

## 🧠 Core Technologies Used

- ESP32 Microcontroller
- Bluetooth Serial Communication
- PWM (Pulse Width Modulation)
- L298N Motor Driver
- DC Motor Control
- Arduino Framework

---

## 🚀 Applications

- Wireless robotic vehicles
- Smart mobility systems
- Educational robotics kits
- IoT-based control systems
- Fest demo projects
