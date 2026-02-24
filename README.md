# ESP32 Bluetooth Voice Controlled Car 🚗📱

A Bluetooth-controlled smart car built using ESP32 and L298N motor driver.
The car responds to voice/text commands sent via a Bluetooth terminal app.

---

## 🔥 Features

- Bluetooth control using ESP32
- Forward, Backward, Left, Right, Stop
- PWM-based speed control
- Differential turning
- Modular and expandable code structure
- Adjustable speed via command

---

## 🛠 Hardware Used

- ESP32 Dev Board
- L298N Motor Driver
- 2x DC Motors
- Robot Chassis
- 7–12V Battery
- Jumper Wires

---

## 📱 Bluetooth Setup

1. Upload the code to ESP32
2. Power on the car
3. Pair with device name:
   ESP32-VOICE-CAR
4. Open any Bluetooth Terminal app
5. Enable newline (`\n`) in app settings
6. Send commands

---

## 🎮 Available Commands

| Command     | Action |
|------------|--------|
| forward     | Move Forward |
| back        | Move Backward |
| left        | Turn Left |
| right       | Turn Right |
| stop        | Stop Motors |
| speedXXX    | Set speed (0–255) |

Example:
speed200

---

## ⚙️ How It Works

- ESP32 receives command via BluetoothSerial
- Command is processed and matched
- Motor direction pins are controlled
- PWM (ledcWrite) controls motor speed
- Differential speed allows smoother turning

---

## 🚀 Future Improvements

- Obstacle Avoidance Mode
- Auto + Manual Mode Switching
- ESP32-CAM Live Streaming
- Custom Android App
- AI-based Voice Recognition

---

## 🧠 Project Type

Embedded Systems | Robotics | IoT | Wireless Control

---

## 📜 License

Open-source project for learning and educational use.
