# Smart-Classroom-Energy-Saving-System

Project Overview

The Smart Classroom Energy Saving System automatically controls classroom lights and fans based on the number of students present.

Components Used

- Arduino UNO R3
- 2 IR Sensors
- 16x2 I2C LCD Display
- Relay Modules
- 5V LED Light
- 5V DC Fan
- Buzzer
- Reset Button
- Breadboard and Jumper Wires
- 5V Power Adapter

Working

1. IR Sensor 1 detects student entry, followed by IR Sensor 2.
2. When a student enters, the count increases.
3. When a student exits, the count decreases.
4. If the student count is greater than zero, the light and fan turn ON.
5. If the count becomes zero, the light and fan turn OFF.
6. The LCD displays the student count and device status.
7. The buzzer gives an alert during entry, exit, and reset.

## Pin Configuration

| Component | Arduino Pin |
|---|---|
| IR Sensor 1 | D2 |
| IR Sensor 2 | D3 |
| Reset Button | D4 |
| Buzzer | D5 |
| Relay Module | D6 |

Code

The Arduino source code is available in "SmartClassroom.ino".

Project Type

College Mini Project – B.Tech Computer Science and Engineering. 