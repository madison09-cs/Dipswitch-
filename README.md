# 💡 Dipswitch LED Control System

A simple and smart Arduino-based system that mimics the behavior of household light switches using a **DIP switch** to control one or more **LEDs**. This project demonstrates digital input reading from a DIP switch and toggling LEDs accordingly.

---

## 📝 Description

The **Dipswitch** project simulates the function of light switches by using a **DIP switch** to control LEDs via an Arduino. Each DIP switch controls a specific LED by connecting to designated digital input pins on the Arduino.

By flipping each switch, you can turn the LED on or off — just like how physical light switches work in real life. This project is perfect for learning about digital inputs, conditional logic, and basic circuit design.

---

## 🔧 Components Used

| Component         | Quantity |
|-------------------|----------|
| Arduino Uno R3    | 1        |
| Breadboard        | 1        |
| Jumper Cables     | Several  |
| DIP Switch        | 1        |
| Red LED           | 1 (or more) |
| 220Ω Resistor     | 1        |
| 10kΩ Resistor     | 1        |

---

## 🚀 Installation & Setup

1. **Connect the DIP Switch**:
   - Each switch terminal → Digital pin on Arduino (e.g., pin 2)
   - Other side → GND through a 10kΩ pull-down resistor

2. **Connect the LED**:
   - Anode (long leg) → Digital pin (e.g., pin 8) via a 220Ω resistor
   - Cathode (short leg) → GND

3. **Upload the Code**:
   - Open the Arduino IDE and write or paste your sketch.
   - Select your **board** and **COM port** from the Tools menu.
   - Click **Upload** to flash the code onto the Arduino.

---

## ⚙️ How It Works

- The DIP switch acts as a digital input device.
- The Arduino reads the state of each switch using `digitalRead()`.
- When a switch is flipped to **HIGH**, it turns the corresponding LED **on**.
- When set to **LOW**, the LED turns **off**.
- This mimics the function of traditional wall-mounted light switches.

This logic can be extended to control multiple LEDs or devices by adding more DIP switch positions.

---

## 💼 Portfolio

Learn more and explore additional Arduino projects:  
🔗 [My Portfolio](https://sites.google.com/d/1kRYFgoPpI5KiRHlfU4u9C--i8z4OA6I5/p/1_ZLDAirpPNf5aijgyz-LQdDFrC5D1Gd2/edit)

---

## 🔬 Simulation

Try it online with this **Tinkercad simulation**:  
▶️ [Tinkercad - Dipswitch LED Control](https://www.tinkercad.com/things/fGMdI5d98OD-copy-of-power-an-led)

---

## 🙌 Credits

- Project created by **[Madison Diggs]**
- Built with **Arduino Uno R3**
- Inspired by real-world lighting control systems

---

## 📄 License

This project is licensed under the Code in the Schools.

---
