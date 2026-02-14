# Arduino Projects  

##  Overview

This repository contains a collection of structured embedded systems projects 
developed for the Arduino Mega 2560 using PlatformIO.

The goal of this repository is to demonstrate:

- Modular embedded architecture
- Hardware abstraction techniques
- Finite State Machine (FSM) design
- Sensor integration
- Real-time logic
- Clean build configuration using multiple PlatformIO environments
- Simulation mode vs Hardware mode separation

Each project is independent and buildable separately.

---

##  Development Environment

- Board: Arduino Mega 2560 
- Platform: atmelavr
- Framework: Arduino
- Language: C++
- Toolchain: PlatformIO

---

##  Repository Structure

```
arduino-projects/
│
├── platformio.ini
├── lib/                # Shared reusable modules
├── projects/           # Independent embedded projects
└── README.md
```

Each project contains:

- Dedicated `main.cpp`
- Configuration header
- Optional simulation mode
- Modular structure

---

##  Projects Included

1. LED Blink & Control  
2. Button Input & Debouncing  
3. Buzzer Tones & Melodies  
4. Temperature & Humidity Monitor 
5. Ultrasonic Distance Sensor 
6. Servo Motor Control System  
7. Traffic Light Controller 
8. Wireless Communication System 

---

##  Build Instructions

To build a specific project:

```
pio run -e <environment_name>
```

Example:

```
pio run -e led_blink_hw
```

To upload:

```
pio run -e led_blink_hw -t upload
```

To open serial monitor:

```
pio device monitor
```

---


