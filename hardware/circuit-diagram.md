# Circuit Diagram & Pinout

## Pin Connections

### ESP8266 NodeMCU to Motor Driver (L298N / L293D)
- IN1 -> D1 (GPIO5) - Motor A Direction 1
- IN2 -> D2 (GPIO4) - Motor A Direction 2
- IN3 -> D3 (GPIO0) - Motor B Direction 1
- IN4 -> D4 (GPIO2) - Motor B Direction 2
- ENA -> D5 (GPIO14) - Motor A Speed Control (PWM)
- ENB -> D6 (GPIO12) - Motor B Speed Control (PWM)

### Power System Connections
- Li-ion Battery Pack (+) via BMS -> Motor Driver VCC
- Li-ion Battery Pack (-) via BMS -> Common GND
- TP4056 / Battery Module 5V Out -> ESP8266 VIN
- ESP8266 GND -> Common GND
- <img width="2400" height="1350" alt="Wifi Controlled Car Schematic" src="https://github.com/user-attachments/assets/943e60a3-4834-4a92-a7d4-871b0b93c7bf" />
