# TankLLevelIndicator
# Smart Water Tank Monitor

Raspberry Pi Pico W → Flask dashboard  
Measures water depth (via analog sensor and/or Ultrasonic Sensor)

## Hardware
- Raspberry Pi Pico W
- Analog depth sensor (ALS-MPM-2F Water Level Transmitter)
- RCWL-1670 Ultrasonic Ranging Module
- Raspberry Pi 5
- VM or computer for handling web server

## Setup

1. Flash `main.py` to Pico W (Thonny / rshell / ampy) using the Raspberry Pi Pico code.
2. Update `SSID`, `PASSWORD`, `SERVER_IP` in `main.py`
3. In terminal on VM or computer: nano tanklevelindicator.py, paste PC code inside and save.
4. On Raspbeery Pi 5, make a file for it's code to go in and paste Raspberry Pi 5 code and save.
5. Run Pico code.
6. Run Raspberry Pi 5 code.
7. On PC, python3 tanklevelindicator.py
8. Open http://your-pc-ip:5000/
