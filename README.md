Smart City Sentinel - Modular PCB for Intelligent Environmental Monitoring

⸻

Project Overview

The Smart City Sentinel is a modular PCB designed for intelligent environmental monitoring in urban spaces. This project integrates multiple sensors, power management systems, and real-time data transmission capabilities within a scalable architecture. The design follows strict connectivity and power constraints, ensuring stability, reliability, and modular expansion for future enhancements.

⸻

Features
	•	Modular PCB design with sensor interfacing for real-time environmental monitoring.
	•	Integrated buck-boost converter for stable voltage regulation.
	•	Fujitsu Relay implemented as a kill switch to protect components from potential damage.
	•	Efficient power management with battery monitoring and solar panel interface.
	•	Compliance with Electrical Rule Check (ERC) and Design Rule Check (DRC) standards.
	•	Compact 3D CAD model ensuring structural compatibility with the predefined solar panel.

⸻

Hardware Components

Component	Description
ESP32-S3-WROOM-1-N16R8	Main microcontroller for data processing and wireless communication.
TP4056	Rechargeable module for battery charging and management.
TLV61070ADBV	Buck-boost converter for stable 3.3V output.
Fujitsu Relay (FTR-LYCA005x)	Kill switch implementation for component protection.
MAX471	Dual-signal current and voltage sensor for accurate monitoring.
OLED Display	Visual data representation interface.
RTC DS3231	Real-time clock for precise timekeeping.
MQ-135 Gas Sensor	Detects harmful gases and air quality.
DHT11	Temperature and humidity sensor.
BME280	Environmental sensor for pressure, humidity, and temperature.
IM69D130	High-performance sound sensor.
A1301KHLT-T	Hall effect sensor for magnetic field detection.
Water Flow Sensor	Monitors fluid flow rates.
Soil Moisture Sensor	Detects soil moisture levels.
Rain Sensor	Identifies rainfall presence.
IR Flame Sensor	Detects flame presence for fire monitoring.
Dust Sensor	Measures airborne particle levels.
Rechargeable Battery (3.7V 2500mAh)	Power source for continuous operation.



⸻


Setup Instructions
	1.	Assemble the PCB according to the provided schematic.
	2.	Flash the ESP32 with the provided firmware.
	3.	Ensure the battery is charged and securely connected via the TP4056 module.
	4.	Monitor data outputs on the OLED display and via the ESP32 serial monitor.
	5.	Test the Fujitsu Relay kill switch by inducing abnormal conditions (e.g., overcurrent) to confirm it safely disconnects power.

⸻

Future Improvements
	•	Implement wireless data transmission for remote monitoring.
	•	Integrate predictive maintenance algorithms to prevent component failure.
	•	Expand modularity by adding additional sensor headers.

⸻


⸻

For further guidance or technical assistance, feel free to contact the project contributors.
