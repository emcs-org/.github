
[![Proprietary License](https://img.shields.io/badge/license-emcs_clv1-brightgreen.svg?style=for-the-badge)](./license.md)


# emcs
**Environmental Monitoring and Control System**


## Table of Contents
- [Terms and Abbreviations](#terms-and-abbreviations)
- [Overview](#overview)
- [Project Objective](#project-objective)
- [Project Scope](#project-scope)
	- [System Components](#system-components)
	- [System Interactions](#system-interactions)
	- [Project Constraints](#project-constraints)
	- [Project Risks](#project-risks)
	- [Project Deliverables](#project-deliverables)
	- [System Prototype Example](#system-prototype-example)
- [Getting Started](#getting-started)
- [Licenses](#licenses)


## Terms and Abbreviations
- **GEMS**: The abbreviation for the project name - Greenhouse Environment Monitoring System.
- **IP**: Internet Protocol in regard to communication.

[(to the top)](#gems)


## Overview
Welcome to the GEMS project. This project aims to create a comprehensive system for monitoring and automating greenhouse conditions to enhance plant growth and sustainability.

[(to the top)](#gems)


## Project Objective
The objective of this project is to design, develop, and implement a Greenhouse Environmental Monitoring System (GEMS). This system aims to provide real-time monitoring, automation, and control of greenhouse conditions, enhancing plant growth and sustainability.

[(to the top)](#gems)

## Project Scope
As this project consists of many components, here is the scope of the project:

[(to the top)](#gems)

### System Components
The Greenhouse Environmental Monitoring System will consist of several components:
- **Sensor(s)**: The system will integrate industry-standard sensors supporting the CAN protocol for monitoring various environmental metrics, including air temperature, humidity, oxygen, carbon dioxide levels, soil humidity, and soil pH levels.
- **Control Unit(s)**: The control unit will be responsible for collecting data from the sensors, forwarding it to the remote monitoring system, and managing the local greenhouse network. Equipped with 2 CAN and an Ethernet adapters, it will bridge the sensors with the remote management system.
- **Remote User Interface**: A remote management system, similar to Home Assistant, accessible via a web-based dashboard or a standalone application that connects to the control unit through an IP connection. It enables users to manage the entire system remotely.
- **Maintenance Interface**: A display and control unit that can be dynamically connected to the Control Unit via the second CAN port to review, configure, and fix the system on the spot.

[(to the top)](#gems)

### System Interactions
The components of the system interact as follows:
- **Sensor(s)**: Exclusively communicate via the CAN bus with the Control Unit.
- **Control Unit(s)**: Communicate with sensors via CAN bus and interface with the remote user interface via IP connection.
- **Remote User Interface**: Interfaces with the Control Unit through the IP protocol.
- **Maintenance Interface**: Interfaces with the Control Unit via CAN.

[(to the top)](#gems)

### Project Constraints
- Hardware component selection and compatibility.
- Third-party sensor availability.
- Development and integration of firmware and software.
- User interface design and implementation.
- Network and communication protocols.
- Environmental impact, including waste management and energy consumption, in accordance with local legal policies.

[(to the top)](#gems)

### Project Risks
- Sensor compatibility and availability.
- Development and integration challenges.
- Technical issues with communication protocols.
- User interface design and usability.
- Project timeline and resource constraints.

[(to the top)](#gems)

### Project Deliverables
- Functional and fully tested Greenhouse Environmental Monitoring System.
- User Manual and System Documentation.

[(to the top)](#gems)

### System Prototype Example
<img src="./example.svg" alt="Example" width="800">

[(to the top)](#gems)


## Getting Started
todo!

[(to the top)](#gems)


## Licenses
todo!

[(to the top)](#gems)
