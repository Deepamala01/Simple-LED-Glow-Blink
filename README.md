# Simple-LED-Glow-Blink
This project shows how to turn ON an LED using the Arduino Uno. The LED is connected to digital pin 2, and the Arduino sends a HIGH signal to make the LED glow continuously. It is a basic beginner project for learning Arduino digital output control.

---
## 1. Introduction

- The LED Glow project is the most basic Arduino project used to learn how to control an output device.

### In this project:

- An LED is connected to digital pin 2
- Arduino sends a HIGH signal
- The LED turns ON and stays ON

### This project helps beginners understand:

- Digital output pins
- Basic Arduino programming
- LED interfacing
---

## 2. Components Required:
 
|Component|	Quantity|
|---------|---------|
|Arduino |UNO	1|
|LED	|1|
|220Ω Resistor	|1|
|Breadboard	|1|
|Jumper Wires	|2|
---

## 3. Circuit Diagram:

### Connections
- Arduino Pin	Component
- Pin 2	LED Anode (+)
- GND	LED Cathode (-) through resistor

### Connection Steps:

- Connect the LED positive leg (Anode) to Pin 2.
- Connect the LED negative leg (Cathode) to 220Ω resistor.
- Connect the other side of the resistor to GND.
---

## 4. Pin Configuration:

|Pin Number| Function|
|----------|---------|
|Pin 2	|Digital Output|
|GND	|Ground Connection|

---

## 5. Arduino Code:
```cpp
void setup() {
  pinMode(2, OUTPUT);   // Set pin 2 as output
}

void loop() {
  digitalWrite(2, HIGH); // Turn LED ON
}
```
---

## 6. Code Explanation:
```cpp
pinMode(2, OUTPUT);
```
- This command sets pin 2 as an output pin, allowing Arduino to send voltage to the LED.

```cpp
digitalWrite(2, HIGH);
```
- This command sends 5V to pin 2, which turns the LED ON.
- Since the command stays in the loop continuously, the LED remains ON permanently.

---

## 7. How It Works:

- Arduino powers up.
- The setup() function runs once.
- Pin 2 is configured as OUTPUT.
- The loop() function runs repeatedly.
- Arduino sends HIGH signal (5V) to pin 2.
- Current flows through the LED.
- The LED glows continuously.

---

## 8. Applications

This simple LED project is used in many applications such as:

- Learning Arduino basics
- Digital output testing
- Indicator lights
- Embedded system debugging
- Electronics learning projects
---
