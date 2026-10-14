# Solar Powered IoT Soil Moisture Sensor
## Preface
The intent of this project was to learn more about the ESP32 chip and its built-in wireless features. In addition, I wanted to integrate over-the-air data collection and reporting to truly make this an IoT project. This system is essentially a soil moisture monitor for a specific plant or garden that logs and inferences water absorption over time. To fully self-contain this design, the board is powered by a 3.7V battery charging off a solar panel, mounted inside an IP67-rated enclosure.

## System Diagram

## Key Validation Tasks
* Power: Test the solar charging circuit
* Data: Calibrate and retrieve moisture data
* Backend: Set up local host device to run InfluxDB; enable WiFi on ESP32 with tags for sensor output
* Frontend: Set up local host to run Grafana; connect to InfluxDB source and query it to create custom dashboard

## Troubleshooting Tasks
* Troubleshooting docker script
* Ensure proper wiring of solar panel, ESP32, and battery across the charger board

## Improvements/Scalability
Potential to build multiple nodes in a modular setup (e.g, for various houseplants or points throughout a garden). Potential to include additional sensors and conduct higher level analyses on multi-modal data.
