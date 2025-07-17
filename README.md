IOT-Projects.
💧 Water Level Monitoring System (Offline, Arduino-Based)

This project is a simple yet effective Water Level Monitoring System designed to detect and alert when a water tank reaches its full capacity. Built using Arduino Uno, HC-SR04 Ultrasonic Sensor and a Buzzer, the system operates entirely offline without requiring any internet connection making it ideal for rural areas, homes, and small-scale usage where cost and reliability are key concerns.

🚀 Overview

Water wastage due to tank overflows is a common issue in many regions. To address this, we developed a cost-effective and reliable monitoring system that alerts users when the tank is full. This project emphasizes simplicity, low power consumption and ease of installation making it accessible even for beginners in electronics and IoT.

 🔧 Key Components

- Arduino Uno: Acts as the main controller, processing data from the sensor and controlling outputs.
- HC-SR04 Ultrasonic Sensor: Measures the distance between the sensor and the water surface to determine water level.
- Buzzer: Provides an audible alert when the tank is full.
- LEDs & Resistors (Optional): Offer additional visual alerts when the water level reaches a set threshold.
- Breadboard & Jumper Wires: Used to create the circuit without permanent soldering.

⚙️ How It Works

1. The ultrasonic sensor emits a sound pulse and calculates the time it takes to bounce back from the water surface.
2. The Arduino Uno uses this timing to calculate the distance and determine how full the tank is.
3. When the water level crosses a certain threshold (i.e., tank is full) a buzzer is triggered to notify the user.
4. Optional LEDs can be configured to light up based on water levels, offering visual cues alongside the buzzer.

🔌 The system is completely standalone it requires no Wi-Fi, cloud platform, or mobile application to operate.

🔌 Circuit Description

- The HC-SR04 sensor is connected to the Arduino digital pins (e.g., Trig to D9, Echo to D10).
- The buzzer is connected to another digital pin (e.g., D6) with a suitable resistor.
- LEDs (if used) are connected to digital pins with current-limiting resistors.
- The system is powered via USB or a 9V battery adapter.

🛠️ Setup Instructions

1. Connect the Components:
   - Follow the standard HC-SR04 and buzzer circuit connections to the Arduino Uno.
2. Upload the Code:
   - Open the `.ino` file in the Arduino IDE.
   - Select the correct board (Arduino Uno) and port.
   - Click Upload to flash the code.
3. Power the System:
   - Once powered, the system continuously monitors the water level and triggers the buzzer when full.

✅ Features

- Offline Operation – No internet required
- Simple and Cost-Effective– Minimal components used
- Customizable Alert Threshold– Modify code to adjust sensitivity
- Beginner-Friendly– Easy to build, modify, and expand
- Environmentally Conscious- Helps conserve water and prevent overflow

🌱 Future Enhancements

- Add an LCD display for real-time distance and level display.
- Integrate a relay module to control a water pump automatically.
- Add multi-level detection (e.g., low, medium, full).
- Upgrade to solar-powered operation for remote areas.

👩‍💻 Author
Rejina Phuyal 
Cybersecurity & Networking Student  
Islington College, London Metropolitan University
Technology doesn’t have to be complex to be impactful sometimes simplicity saves the most.
