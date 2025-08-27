# 7-Segment Display with Arduino (0–9 Counter)

## 📌 Project Overview

This project demonstrates how to interface a **7-segment display** with an **Arduino Uno** to display digits from **0 to 9**. It will help you understand how to control each LED segment to form numbers.

---

## 🛠 Components Required

* Arduino Uno (or any compatible board)
* 7-segment display (Common Cathode)
* 8 × 220Ω resistors
* Breadboard
* Jumper wires

---

## 🔌 Circuit Connections

| Segment | Display Pin | Arduino Pin |
| ------- | ----------- | ----------- |
| A       | 11          | 11          |
| B       | 10          | 10          |
| C       | 7           | 7           |
| D       | 8           | 8           |
| E       | 9           | 9           |
| F       | 12          | 12          |
| G       | 13          | 13          |
| Common  | COM pins    | GND         |

⚡ **Note:** Connect both **common cathode pins** of the display to **GND** through the breadboard rail.


---

## ⚙️ How It Works

1. Each segment of the display is controlled individually using Arduino digital pins.
2. The `digits[][]` array stores **which segments should be ON/OFF** for numbers 0–9.
3. The `displayDigit()` function lights up the correct segments based on the number.
4. The loop cycles through **0–9** with a **1-second delay**.

---

## 📷 Circuit Diagram (for reference)

<img width="970" height="458" alt="image" src="https://github.com/user-attachments/assets/ae4e69da-aa00-41b7-a069-f54d179c7b9f" />


---

## 🚀 Future Improvements

* Add **push button** to increase/decrease digits manually.
* Add **two 7-segment displays** to count 00–99.
* Use a **shift register (74HC595)** to reduce pin usage.

## LINK to project

https://www.tinkercad.com/things/8XUKccrOeg0-ingenious-bruticus?sharecode=JRa3pDeBmMuh07Q-nmwCyS3YbUzefz3hY2SlM-6_WOU
---

