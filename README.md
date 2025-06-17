# HomeAUTO
Smart Home Automation Project with ESP8266, ESP32, and MQTT – Hardware-Centric Highlights

Integrated Microcontroller System Design
Developed a functional smart home prototype using ESP8266 and ESP32 microcontrollers to collect environmental data (temperature, gas, light, motion) and control actuators (LEDs, fan, servo motors, buzzer) via MQTT protocol and Adafruit IO dashboard.

Hardware Implementation and Electrical Design
Engineered reliable power distribution and voltage management (12V→5V/3.3V using step-down converters), signal integrity (Cat5e UTP/STP wiring), and grounding strategies for noise reduction and hardware safety. Modular cabling and Wago connectors enabled maintainable and secure assembly.

System Architecture and Real-Time Performance
Designed a distributed architecture with ESP8266 units handling sensor data acquisition and actuator control, while the ESP32 served as the central controller performing JSON parsing and command logic. Achieved real-time responsiveness (95%) and network stability (99%) during system testing.

