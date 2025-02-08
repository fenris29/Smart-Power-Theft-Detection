The system will consist of a microcontroller of ESP32 S3, two ACS712 current sensors, relay module, an energy meter, MCB, and WiFi. The two ACS712 sensors will be placed in different points within the circuit, where the first sensor measures the current before reaching the energy meter, and the second measures after the meter and before reaching the load. It continuously compares these readings. If the difference is more than a predetermined threshold, then that could be an indication of potential power theft. In such cases, the system initiates relay cut-off control of the power supply and sends an alert message through the Blynk IoT platform.



