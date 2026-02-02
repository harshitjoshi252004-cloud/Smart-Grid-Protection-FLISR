# Integrated Protection, FLISR Automation, & Smart Grid Analytics

![Project Status](https://img.shields.io/badge/Status-Completed-success) ![MATLAB](https://img.shields.io/badge/Tools-MATLAB%20%7C%20Simulink%20%7C%20PowerBI-blue)

## 📌 Project Overview
This project focuses on the modeling, simulation, and analysis of a **Smart Distribution Network**. It integrates advanced protection coordination schemes with **Fault Location, Isolation, and Service Restoration (FLISR)** logic. The system is validated using **MATLAB/Simulink** for electromagnetic transient studies and **Power BI** for post-event asset performance analytics.

The objective is to minimize outage duration and analyze the correlation between distribution transformer loading and thermal efficiency under fault conditions.

## 🚀 Key Features

### 1. Distribution Network Simulation
* Modeled radial distribution feeders to assess technical losses and voltage profiles.
* Simulated varying load conditions to propose optimization strategies under utility operating constraints.

### 2. Protection Coordination Logic
* Implemented **Relay Coordination logic** using symmetrical and asymmetrical fault trajectories (L-G, L-L-G).
* Ensured selectivity between upstream and downstream breakers to minimize the "zone of disconnection" during faults.
* **Tech:** RMS detection, S-R Flip-Flop latching, and threshold-based tripping in Simulink.

### 3. Smart Grid FLISR Automation
* Designed the functional architecture for **SCADA** and **Ring Main Units (RMU)**.
* **Self-Healing Grid:** Implemented logic for automatic **Fault Isolation** and immediate **Service Restoration** via a backup power source integration.

### 4. Asset Performance Analytics (Power BI)
* Developed a dashboard to visualize **Distribution Transformer** health using simulation data.
* Correlated **Load Factors** with **Thermal Efficiency** and **Voltage Stability**.
* **Visuals:** Real-time waveform monitoring, fault current profiles, and revenue impact indicators.

## 📂 Repository Structure & Files

This repository contains the following source files:

| File Name | Description |
| :--- | :--- |
| **`Integrated Protection, FLISR Automation.slx`** | The main **MATLAB/Simulink Model** containing the grid topology, protection logic, and FLISR automation blocks. |
| **`Integrated Protection, FLISR Automation.pbix`** | The **Power BI Dashboard** source file used for visualizing asset health and fault data. |
| **`AdvancedProjectData.xlsx`** | The **Dataset** generated from the simulation, containing timestamped voltage, current, and power logs. |
| **`Dashboard.pdf`** | A static **PDF Report** of the analytics dashboard for quick viewing without Power BI. |

## 📊 Visuals

*(Please refer to the `Dashboard.pdf` file for high-resolution charts and graphs)*

## 🤝 Contact
* **Author:** [Harshit Joshi]
