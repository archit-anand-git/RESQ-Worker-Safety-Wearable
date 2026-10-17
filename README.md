# RESQ — Worker Safety and Emergency Response

### An Offline-Ready Intelligent Wearable for Worker Safety

RESQ is an ESP32-S3-based wearable safety project designed to monitor
important health and environmental parameters and support worker safety
in hazardous or remote environments.

The project combines sensor interfacing, embedded systems, health
monitoring and the proposed use of edge intelligence to support early
risk identification and emergency response.

## Problem Statement

Workers at construction sites, mines and other hazardous workplaces
may face health risks, accidents, heat exposure and delayed emergency
assistance.

RESQ aims to address these challenges through wearable monitoring,
local processing and a design that can support emergency communication
even when internet connectivity is limited.

## Key Objectives

- Monitor heart rate and blood oxygen saturation (SpO2).
- Measure body temperature and environmental conditions.
- Collect motion data for activity and potential fall analysis.
- Display sensor readings and system status on an OLED.
- Develop local risk assessment and alert mechanisms.
- Explore emergency communication and location-enabled SOS features.
- Investigate offline operation and TinyML-based risk detection.

## Hardware Components

| Component | Purpose |
| ESP32-S3 | Main microcontroller |
| MAX30102 | Heart rate and SpO2 sensing |
| TMP117 | Body temperature sensing |
| MPU6050 | Motion and activity data |
| AHT10 | Environmental temperature and humidity |
| OLED Display | Displaying sensor readings and status |
| NEO-6M GPS | Location data for emergency assistance |

Additional communication, alerting and power-management components
may be integrated as the prototype develops.

## System Workflow

1. Sensors collect health, motion and environmental data.
2. The ESP32-S3 reads and processes the sensor measurements.
3. The OLED displays the available readings.
4. Risk assessment logic can analyse the measurements.
5. Appropriate alerts and emergency communication can be developed
   as part of the next implementation stages.

## Current Implementation Status

- Wearable hardware prototype assembled.
- Sensor interfacing and data acquisition implemented.
- Sensor readings displayed on the OLED.
- Further integration, validation and testing remain ongoing.

## Planned Improvements

- Implement and validate risk classification.
- Develop fall-detection logic using motion data.
- Integrate local buzzer or vibration alerts, where supported by
  the hardware.
- Explore TinyML-based risk assessment on the ESP32-S3.
- Investigate offline communication and emergency notifications.
- Integrate GPS-based location sharing.
- Improve power consumption and wearable design.
- Conduct controlled testing to evaluate reliability.

## Technologies

- Embedded C/C++
- ESP32-S3
- Arduino IDE
- Sensor Interfacing
- I2C and UART
- Embedded Systems
- IoT and Wireless Communication
- Edge AI / TinyML (planned development)

## Applications

- Construction-site worker safety
- Industrial safety monitoring
- Remote and hazardous workplaces
- Emergency-response support

## Project Status

Prototype development and sensor integration.

The current prototype displays sensor readings. Advanced risk
classification, emergency communication and other planned features
should be considered under development until they have been implemented
and tested.

## Author

Archit Anand

Electronics and Communication Engineering

## Disclaimer

RESQ is a prototype under development. Its sensor readings and
risk-assessment capabilities are not a substitute for professional
medical evaluation or certified industrial safety equipment.
