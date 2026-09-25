# ⚡ Smart Electricity Monitoring Dashboard

A web-based **Smart Electricity Monitoring Dashboard** designed to monitor, visualize, and analyze electricity consumption across different circuits and zones. The system provides insights into active power demand, voltage, current, power factor, energy consumption, peak demand, carbon emissions, and load patterns.

The dashboard is designed around an **IoT-based energy monitoring architecture**, using ESP32 microcontrollers, current sensors, PZEM modules, and telemetry communication for monitoring electrical loads.

## 🚀 Live Demo

[Smart Electricity Monitoring Dashboard](https://enery-monitoring-dashboard.netlify.app/)

## 🎯 Objectives

* Monitor electricity consumption across different sub-circuits.
* Display electrical parameters such as voltage, current, and active power.
* Identify unusual or high-energy-consuming loads.
* Analyze consumption patterns and peak demand.
* Track energy efficiency and carbon emissions.
* Provide a centralized dashboard for energy monitoring.
* Support data-driven energy conservation and management.

## ✨ Key Features

* **Real-Time Power Monitoring** – Displays active power demand and live electrical parameters.
* **Sub-Circuit Monitoring** – Tracks electricity usage across individual rooms, laboratories, lighting systems, and server infrastructure.
* **Load Analysis** – Provides a breakdown of energy consumption by subsystem.
* **Anomaly Detection** – Highlights circuits with unusually high or abnormal loads.
* **Energy Consumption Tracking** – Displays daily and weekly energy consumption.
* **Peak Demand Monitoring** – Records and displays maximum power demand.
* **Carbon Emission Estimation** – Estimates emissions associated with electricity consumption.
* **IoT Sensor Monitoring** – Displays connected ESP32 nodes and their telemetry information.
* **Energy Efficiency Index** – Provides an overall energy-efficiency indicator.
* **Environmental Management Tracking** – Includes Plan-Do-Check-Act monitoring for energy-management activities.

## 🔧 IoT Architecture

The proposed monitoring architecture uses:

* **ESP32 microcontrollers** for sensor-node communication
* **SCT-013 Current Transformers** for non-invasive current measurement
* **PZEM-004T** for AC electrical parameter measurement
* **MQTT / Wi-Fi** for telemetry communication
* **HTTP POST** for selected sensor-node data transmission
* Web dashboard for visualization and analysis

## 📊 Dashboard Monitoring

The dashboard provides information such as:

| Parameter         | Description                            |
| ----------------- | -------------------------------------- |
| Active Power      | Current electrical load                |
| Voltage           | Mains voltage                          |
| Current           | Current drawn by the monitored circuit |
| Power Factor      | Electrical power factor                |
| Daily Consumption | Energy consumed during the day         |
| Weekly Load       | Total weekly energy consumption        |
| Peak Demand       | Maximum recorded power demand          |
| Carbon Emissions  | Estimated grid-related emissions       |
| Efficiency Index  | Energy-efficiency indicator            |
| Sensor Status     | Status of connected IoT nodes          |

## 🏫 Example Monitoring Zones

The dashboard demonstrates monitoring of different institutional electrical loads, including:

* Data Structures Laboratory
* Microprocessor Laboratory
* Corridor and Lighting Systems
* Server / Network Rack
* HVAC and Air Conditioning
* Laboratory Workstations

## 🛠️ Technologies

* HTML
* CSS
* JavaScript
* IoT / ESP32
* MQTT
* PZEM-004T
* SCT-013 Current Transformer
* Data Visualization
* Netlify

## 📁 Repository Contents

This repository contains the complete project submission:

```text
Smart-Electricity-Monitoring/
│
├── source-code/
│   └── Project source files
│
├── PPT/
│   └── Project presentation
│
├── Individual-Report/
│   └── Individual project report
│
├── README.md
│
└── screenshots/
    └── Dashboard screenshots
```

## 🌱 Sustainability

The project supports energy-awareness and efficient electricity management by making consumption patterns visible and helping identify unnecessary or abnormal energy usage.

The dashboard can be extended for use in educational institutions, offices, laboratories, commercial buildings, and other facilities where monitoring electricity consumption is important.

## 📌 Project Status

**Status:** Completed / Prototype

This project demonstrates a functional concept of an IoT-enabled electricity monitoring and analytics dashboard.

## 👩‍💻 Project Submission

This repository contains:

* Project source code
* PowerPoint presentation
* Individual report
* Project documentation
* README file
* Dashboard implementation

## 🔗 Live Application

https://enery-monitoring-dashboard.netlify.app/
