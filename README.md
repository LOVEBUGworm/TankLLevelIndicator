# TankLLevelIndicator
# Smart Water Tank Monitor

Raspberry Pi Pico W → Flask dashboard  
Measures water depth (via analog sensor and/or Ultrasonic Sensor)

## Hardware
- Raspberry Pi Pico W
- Analog depth sensor (ALS-MPM-2F Water Level Transmitter)
- RCWL-1670 Ultrasonic Ranging Module

## Setup

1. Flash `main.py` to Pico W (Thonny / rshell / ampy) using the Raspberry Pi Pico code.
2. Update `SSID`, `PASSWORD`, `SERVER_IP` in `main.py`
3. In terminal: nano tanklevelindicator.py, paste PC code inside and save.
4. Run Pico code.
5. On PC, python3 tanklevelindicator.py
6. Open http://your-pc-ip:5000/
