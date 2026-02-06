# TankLLevelIndicator
# Smart Water Tank Monitor

Raspberry Pi Pico W → Flask dashboard  
Measures water depth (via analog sensor) + temperature

## Hardware
- Raspberry Pi Pico W
- Analog depth sensor (e.g. resistive or ultrasonic → voltage)
- Temperature sensor (e.g. DS18B20 or onboard)

## Setup

1. Flash `pico/main.py` to Pico W (Thonny / rshell / ampy)
2. Update `SSID`, `PASSWORD`, `SERVER_IP` in `main.py`
3. Run Flask server: `python app.py`
4. Open http://your-pc-ip:8080/
