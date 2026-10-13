# Solar Powered IoT Soil Moisture Sensor
## Preface
While I've done a lot of previous work with Arduino for basic microcontroller projects, I wanted to learn more about the ESP32 chip and its built-in wireless features. In addition, I wanted to integrate over-the-air data collection to truly make this an IoT project. This system is essentially a soil moisture monitor for a specific plant or garden that logs and inferences water absorption over time. To fully self-contain this design, the board is powered by a battery charging off a solar panel, mounted in an IP-rated enclosure.

## System Diagram

## Key Validation Tasks
* Power: Test the solar charging circuit
* Data: Calibrate and retrieve moisture data
* Backend: Set up local host device to run InfluxDB; enable WiFi on ESP32 with tags for sensor output
* Frontend: Set up local host to run Grafana; connect to InfluxDB source and query it to create custom dashboard

## Improvements/Scalability
Potential to build multiple nodes in a modular setup (e.g, for various houseplants or points throughout a garden). Potential to include additional sensors and conduct higher level analyses on multi-modal data.
