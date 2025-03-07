# Smart Street Lighting System  

## Overview  
This project implements an energy-efficient Smart Street Lighting System using an LDR (photoresistor) and IR sensors. The system works as follows:  
- At night, the street lights remain dimly lit.  
- When motion is detected, the brightness increases.  
- After a short time, the lights return to dim mode.  
- In the morning, the lights turn off completely.  

## Components Used  
- **Arduino Board**  
- **LDR Sensor (Photoresistor)** – Detects ambient light levels.  
- **IR Sensors** – Detect motion to adjust brightness.  
- **LEDs** – Simulate street lights.  
- **Resistors & Wires**  

## Circuit Connections  
- **LDR Sensor** → Analog Pin `A0`  
- **IR Sensors** → Digital Pins `2`, `3`, `4`  
- **LEDs** → Digital Pins `5`, `6`, `7`  

## Working Principle  
1. **Daytime:** The LDR detects high light intensity and turns off all LEDs.  
2. **Nighttime:** LEDs remain dimly lit.  
3. **Motion Detection:** IR sensors detect movement, and the respective LED increases brightness.  
4. **After Few Seconds:** The LED dims again if no motion is detected.  

## Future Enhancements  
- Add **PIR sensors** for improved motion detection.  
- Implement **IoT integration** for remote monitoring and control.  
- Use **solar panels** for sustainable energy consumption.  

