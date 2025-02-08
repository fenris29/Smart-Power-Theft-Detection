# Smart Power Theft Detection System

# Overview
This project detects unauthorized power theft using an ESP32, ACS712 sensors, a relay, and Blynk IoT notifications.

# Features
- Detects power theft by comparing current readings.
- Sends alerts via Blynk IoT.
- Auto power cutoff using a relay.

## Circuit Diagram
(Insert the circuit diagram image link)

# Hardware Required
- ESP32 S3
- ACS712 Current Sensors (2)
- Relay Module
- Energy Meter
- MCB

# How It Works
1. The ESP32 reads current values from the ACS712 sensors.
2. If the difference between source and load currents is high, it detects theft.
3. The relay is triggered to cut off power.
4. An alert is sent to the user via Blynk.

# How to Use
1. Upload the provided code to ESP32.
2. Connect the circuit as per the diagram.
3. Monitor theft alerts on Blynk.

# License
This project is open-source.
}



