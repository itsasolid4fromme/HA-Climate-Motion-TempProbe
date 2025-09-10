# ESP32 Motion Sensor for Ductless Mini-Split Automation

This project adds a motion-sensing “eco mode” to your ductless mini-split system using an ESP32-based controller and Home Assistant (HA).  
When no motion is detected, the system can automatically scale back heating or cooling to save energy and restore comfort settings when motion is detected again.  

---

## Overview
- Uses an **ESP32 controller** to act as the bridge between your mini-split and Home Assistant.  
- Adds a **motion sensor** to trigger automations for occupied vs. unoccupied states.  
- Designed to work seamlessly with [ESPHome](https://esphome.io/) and [Home Assistant](https://www.home-assistant.io/).  

---

##  Requirements
- ESP32-based mini-split controller (e.g., [smartlight.me device](https://smartlight.me))  
- [ESPHome](https://esphome.io/) installed and configured  
- Home Assistant running on your network  

---

##  Setup Instructions
1. **Flash the ESP32 Motion Sensor**  
   - Use ESPHome Device Builder to flash the motion sensor firmware onto your ESP32.  

2. **Add Motion Sensor to Home Assistant**  
   - Once flashed, add the ESP32 device into Home Assistant.  

3. **Add Automation**  
   - Import the included automation YAML into Home Assistant.  
   - Adjust thresholds, timers, and HVAC setpoints as needed.  
4. **Test**  
   - Verify that motion is detected correctly.  
   - Ensure HVAC responds to motion/no-motion states.  

---

##  Parts Used
- [HiLetgo HC-SR501 PIR Motion Sensor](https://www.amazon.com/dp/B07VCCZS54)  
- [ELEGOO ESP32 Development Board (EL-SM-012)](https://www.amazon.com/dp/B08D6Y6KD6)  

---

## License
This project is open source. Feel free to use and adapt for personal projects.  

---
