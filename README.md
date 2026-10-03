🔥 IoT-Based Early Fire Detection System

An embedded IoT system designed for the early detection and monitoring of potential forest fires.

🎯 Project Overview

This project uses multiple ESP32-based sensor nodes to monitor environmental conditions over a 200 × 200 m area.

The system collects temperature, humidity, smoke and flame data to evaluate the fire risk and provide an early warning.

🛠️ Hardware

* ESP32
* DHT11 temperature & humidity sensors
* MQ-2 smoke sensors
* KY-026 flame sensors
* SIM800L GSM module
* MOSFET power control

📡 System Architecture

The system consists of:

* 1 Master ESP32
* 3 Slave ESP32 nodes
* Environmental and fire detection sensors
* Wireless communication between nodes
* Web monitoring interface
* SMS alert system

🔄 System Workflow

Sensor Acquisition → Data Transmission → Risk Evaluation → Monitoring → Alert

The sensor nodes periodically collect environmental data and send the information to the master node.

The master node evaluates the collected data and determines the level of fire risk.

🌐 Web Monitoring

A web interface allows the user to monitor the different sensor nodes on an interactive map.

The nodes are identified on the map using their ESP32 IDs.

📱 SMS Alert

The SIM800L module is used to send an SMS when a fire is detected.

🎥 Project Demonstration

[▶️ Watch the project demonstration on YouTube](https://youtu.be/iWoYFWZAJeo?si=dTE7njW4WAGPYW-y)

📷 Project Images

Project photos showing the sensor nodes, master node and complete prototype.

👥 Team

Developed with my project partner as part of an academic project in Embedded Systems.

💻 Technologies

ESP32 · C/C++ · IoT · Embedded Systems · Sensors · GSM · Web Server · Leaflet

📌 Project Status

Prototype developed for academic purposes.
