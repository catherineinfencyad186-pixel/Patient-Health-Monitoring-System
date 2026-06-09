📌 Project Overview – Patient Health Monitoring System:

The Patient Health Monitoring System is an IoT-based healthcare project designed to continuously monitor a patient's vital parameters such as body temperature, heart rate, blood oxygen level (SpO₂), and environmental conditions. The system uses an ESP32 microcontroller to collect sensor data and display it in real time.

This project helps in remote patient monitoring by providing instant health information to doctors, caregivers, or family members. If any health parameter exceeds the predefined safe limit, the system can trigger alerts using LEDs, buzzers, or notifications. The solution improves patient safety, reduces manual monitoring efforts, and supports modern smart healthcare applications.

🛠 Hardware Used
-ESP32 Development Board – Main microcontroller for processing and communication.
-DHT22 Sensor – Measures temperature and humidity.
-LED (Green & Red) – Indicates normal and abnormal health conditions.
-Buzzer – Provides alert during critical conditions.
-Push Button (Optional) – For emergency or manual input.
-Breadboard – Used for circuit prototyping.

📊 Working Principle
-The ESP32 microcontroller continuously reads data from the DHT22 sensor.
-The sensor measures environmental parameters such as temperature and humidity.
-The collected data is processed by the ESP32 and displayed through the Serial Monitor or IoT platform.
-The system compares the measured values with predefined threshold limits.
-When the readings remain within the safe range, the green LED indicates normal conditions.
-If the readings exceed the set limits, the red LED and buzzer are activated to alert caregivers or users.
-The monitoring process runs continuously, providing real-time health-related environmental information.

📚 Key Learning Outcomes
-Understanding IoT-based healthcare systems.
-Working with ESP32 microcontroller.
-Sensor interfacing and data acquisition.
-Real-time monitoring and alert generation.
-Embedded systems and wireless communication concepts.

🏥 Real-World Applications
-Hospitals and clinics.
-Home healthcare monitoring.
-Elderly patient care.
-Remote healthcare services.
-Smart healthcare and IoT-based medical systems.

📂 Project Files
-main.ino – Main program code
-diagram.json – Circuit design file
-README.md – Project documentation
-Circuit Diagram – Connection layout
-Output Screenshots – Project results

🚀 Future Improvements
-Add Heart Rate and SpO₂ sensors.
-Develop a mobile app for monitoring.
-Send emergency alerts to caregivers.
-Store data in the cloud.
-Create a web dashboard.
-Improve sensor accuracy.
-Support remote patient monitoring.
-Add more health monitoring features.
