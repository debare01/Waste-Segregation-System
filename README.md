# Automated Waste Segregation System ♻️
Final Year Project - Automated separation into Wet, Dry, and Metallic waste.

**Accuracy: 90% overall | 100% Metallic, 90% Wet, 80% Dry**

### How It Works
- **CAD:** Designed in Fusion 360
- **Control:** Arduino Uno with rule-based logic
- **Sensors:** Inductive (Metal), Moisture (Wet/Dry), IR (Presence)
- **Actuation:** SG90 Servo + Stepper Motor + A4988 Driver
- **Power:** 7.4V Li-ion

**Logic:** IR detects waste -> stops -> Inductive checks for metal -> if not, Moisture checks wet/dry -> servo rotates plate to correct bin.

### Components
- Arduino Uno, SG90 Servo, Stepper Motor, A4988 Driver
- Inductive Proximity Sensor, Moisture Sensor, IR Sensor
- 2x 3.7V Li-ion Batteries

### Future Improvements
- Capacitive/NIR sensor for better accuracy
- OpenCV image processing
- BMS for power management
