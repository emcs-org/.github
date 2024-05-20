
[![License](https://img.shields.io/badge/license-emcs_clv1-brightgreen.svg?style=for-the-badge)](./license.md)
![Languages](https://img.shields.io/badge/languages-C-brightgreen.svg?style=for-the-badge)


# Environment Monitoring and Control System (EMCS)

## Table of Contents
- [Overview](#overview)
- [Project Objective](#project-objective)
- [Project Scope](#project-scope)
	- [Subprojects Details](#subprojects-details)
		- [Sensor Module](#sensor-module)
		- [Control Module](#control-module)
		- [Control Panel](#control-panel)
	- [Examples of Usage](#examples-of-usage)
- [License](#license)


## Overview
Welcome to the EMCS (Environment Monitoring and Control System) project! This document serves as an extensive introduction to the entire EMCS project, outlining its components, functionality, and benefits. The EMCS project comprises three main subprojects:
- Sensor Module
- Control Module
- Control Panel

Each subproject plays a crucial role in ensuring accurate data collection, efficient data management, and seamless control of environmental factors.

[(to the top)](#environment-monitoring-and-control-system-emcs)


## Project Objective
The primary objective of the Environment Monitoring and Control System (EMCS) project is to develop a comprehensive, integrated solution that enables its users to precisely monitor and control environmental systems. By leveraging advanced sensor technology, robust data management, and user-friendly remote interfaces, EMCS aims to enhance operational efficiency, optimize resource utilization, and ensure optimal environmental conditions in various settings such as agriculture, industrial facilities, and research laboratories. The system is designed to provide real-time insights, automate control processes, and facilitate remote management.

[(to the top)](#environment-monitoring-and-control-system-emcs)


## Project Scope
The scope of the EMCS project encompasses the design, development, and implementation of three core subprojects: the Sensor Module, Control Module, and Control Panel. These components will enable comprehensive monitoring and control of soil and air parameters, facilitating data collection, analysis, and system management.
The project will focus on delivering a scalable and adaptable solution suitable for diverse organizational environments, with the potential for integration with third-party systems to enhance functionality and interoperability.


### Subprojects Details
#### Sensor Module
The Sensor Module is a product responsible for gathering critical environmental data. It is equipped with various sensors to measure:
- Soil Temperature. Monitors the temperature of the soil to ensure optimal conditions for plant growth.
- Soil Moisture Levels. Measures the moisture content in the soil to prevent overwatering or drought conditions.
- Soil pH Levels. Tracks the acidity or alkalinity of the soil to maintain a balanced environment for vegetation.
- Air Temperature. Records the ambient air temperature to help manage climate conditions.
- Oxygen Levels in the Air. Monitors oxygen levels to ensure adequate ventilation and air quality.
- Carbon Dioxide Levels in the Air. Measures CO2 levels to manage plant respiration and air quality.
- Air Humidity. Tracks humidity levels to maintain an ideal environment for plants and equipment.

The Sensor Module features an e-paper display that shows the collected metrics in real-time and transmits this data via a CAN FD (Controller Area Network Flexible Data-rate) bus to the Control Module.

[(to the top)](#environment-monitoring-and-control-system-emcs)

#### Control Module
The Control Module is the central hub of the EMCS. It collects data from multiple Sensor Modules via the CAN FD communication protocol. Its primary functions include:
- Data Collection. Aggregates metrics from various sensors for comprehensive environmental monitoring.
- Data Storage. Maintains a record of all collected data for historical analysis and reporting.
- Data Analysis. Utilizes advanced algorithms to analyze the collected data and provide actionable insights.
- System Control. Manages and controls the entire system, including the Sensor Modules and potential third-party integrated systems.

For example, the Control Module can integrate with an automated watering system. Using the data collected, it can manage watering schedules and amounts via a separate CAN FD line, ensuring optimal soil moisture levels without manual intervention.

[(to the top)](#environment-monitoring-and-control-system-emcs)

#### Control Panel
The Control Panel is a remote application that serves as an online dashboard for the EMCS. It provides users with an interface to interact with the system's Control Module from anywhere via the internet. Key features of the Control Panel include:
- System Configuration. Allows users to configure settings for both the Control Module and Sensor Modules.
- Remote Management. Enables users to monitor and control the system remotely, ensuring flexibility and convenience.
- Data Visualization. Offers detailed graphs and reports to help users understand environmental conditions and trends.
- Alerts and Notifications. Sends alerts and notifications based on predefined conditions or anomalies detected in the environment.

[(to the top)](#environment-monitoring-and-control-system-emcs)


### Examples of Usage
Agricultural Use<br>
In an agricultural setting, the EMCS can be deployed to ensure optimal growing conditions for crops. The Sensor Modules placed in various parts of the fields or greenhouses collect data on soil moisture, temperature, and pH levels. The Control Module analyzes this data and automatically adjusts the irrigation system to provide precise watering, thus conserving water and enhancing crop yield.

[(to the top)](#environment-monitoring-and-control-system-emcs)


## License
The EMCS project is released under the **emcs clv1** license. Users and contributors are required to review and comply with the license terms specified in the [license.md file](./license.md). The license outlines the permitted usage, distribution, and intellectual property rights associated with this project.

Please refer to the [license.md file](./license.md) for more details. By using, modifying, or distributing this project, you agree to be bound by the terms and conditions of the license.

[(to the top)](#environment-monitoring-and-control-system-emcs)
