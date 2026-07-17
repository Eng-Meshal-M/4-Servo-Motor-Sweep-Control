# ⚙️ 4-Servo Motor Sweep Control

> **Developed by:** Meshal Al Mehmady

---

## 📌 Project Overview

This project demonstrates how to control **four servo motors** using an Arduino Uno.

All four servos perform a synchronized sweep motion for **2 seconds**, then automatically move to **90°** and remain there briefly before repeating the sequence.

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5739df6-7690-410a-8908-b46de04ed282"
 width="85%" />
</p>

---

## 📂 Project Structure

```text
4-Servo-Motor-Sweep-Control/
│
├── Arduino_Code.ino
├── README.md
└── demo.mp4
```

---

## 🔌 Hardware Components

- Arduino Uno
- 4 × Servo Motors
- Jumper Wires
- Tinkercad Circuit

---

## 🔗 Servo Connections

| Servo | Arduino Pin |
|-------|-------------|
| Servo 1 | D3 |
| Servo 2 | D5 |
| Servo 3 | D6 |
| Servo 4 | D9 |

---

## ⚙️ Program Behavior

The Arduino program performs the following sequence:

- All servos start from **90°**.
- The four servos move together in a sweep motion for **2 seconds**.
- After the sweep, all servos return to **90°**.
- The sequence repeats continuously.

---

## 🎥 Demonstration

A short demonstration video of the simulation is included in this repository.

https://github.com/user-attachments/assets/f703b414-aa13-466a-b00b-fcc6a6ede830
