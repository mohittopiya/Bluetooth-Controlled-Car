# Bluetooth-Controlled Car

This project demonstrates a Bluetooth-controlled car using Arduino. The car is remotely controlled via a smartphone using Bluetooth communication, with the help of an HC-05 Bluetooth module and an Arduino board. A motor driver is used to control the car's movement, enabling real-time control of the car's direction and speed.

## Components Used:
- **Arduino Uno** (or any compatible Arduino board)
- **HC-05 Bluetooth Module**
- **L298N Motor Driver**
- **DC Motors (2 for the car's wheels)**
- **Chassis** for the car
- **Jumper wires**
- **Smartphone with Bluetooth support**

## Features:
- Control the car's direction (forward, backward, left, right)
- Adjust speed using your smartphone
- Simple and intuitive interface

## Circuit Connections:
1. **HC-05 Bluetooth Module:**
   - VCC to 5V on Arduino
   - GND to GND on Arduino
   - TX to RX on Arduino
   - RX to TX on Arduino
2. **L298N Motor Driver:**
   - IN1, IN2, IN3, IN4 pins to Arduino (for motor control)
   - Motor terminals connected to the car's wheels
3. **DC Motors:**
   - Connected to L298N for motor control

## How to Use:
1. **Set up the hardware** by connecting the Arduino, Bluetooth module, and motor driver according to the wiring instructions.
2. **Upload the code** to the Arduino board using the Arduino IDE.
3. **Pair your smartphone** with the HC-05 Bluetooth module.
4. **Control the car** through a Bluetooth app (e.g., Bluetooth Terminal) using simple commands to move the car forward, backward, left, and right.

## Code:
The Arduino code controls the movement of the car based on Bluetooth input from the smartphone. It listens for commands via the Bluetooth module and activates the motor driver accordingly.

## License:
This project is open-source under the MIT License.
