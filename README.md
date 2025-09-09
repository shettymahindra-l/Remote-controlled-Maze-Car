# Bluetooth-Controlled Maze Car

This is an **ESP32-based Bluetooth remote-controlled maze car** that allows you to drive it using a smartphone. The project uses the **DabbleESP32 library** to interface with a gamepad and control the car’s motors through PWM signals. It can move forward, backward, and turn left or right, making it ideal for maze navigation and robotics learning.

---

## 📹 Demo

![Demo GIF](https://github.com/shettymahindra-l/Remote-controlled-Maze-Car/blob/7eb82bda9d149f623f12533d393f6a1ad6b19d3e/maze%20car.gif)


---

## ✅ Features

- Control the car wirelessly using Bluetooth.
- Smooth motor control with PWM for speed adjustment.
- Independent control of left and right motors for precise navigation.
- Simple and modular hardware setup using ESP32 and a motor driver.

---

## 📦 Components Required

- ESP32 development board  
- Motor driver module (L298N or similar)  
- Two DC motors  
- Jumper wires and power supply  
- Smartphone with Bluetooth  
- Dabble app installed (available on Android/iOS)

---

## ⚙ How It Works

1. The ESP32 connects to the Dabble app via Bluetooth.
2. Button presses from the gamepad control the motor speeds and directions.
3. PWM signals manage the speed, while GPIO pins control motor direction.
4. The car can navigate a maze or be used in robotics experiments.

---

## 📂 Software Setup

1. Install [Arduino IDE](https://www.arduino.cc/en/software).
2. Install the **DabbleESP32** library via the Library Manager.
3. Upload the code to the ESP32.
4. Pair your smartphone with the ESP32.
5. Use the gamepad feature in the Dabble app to control the car.

---

## 📖 Usage

- **Up Button**: Move forward.
- **Down Button**: Move backward.
- **Left Button**: Turn left.
- **Right Button**: Turn right.

---
