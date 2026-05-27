# SCADA Substation Monitoring Platform

## Project Overview

This project provides a professional-grade, web-based SCADA (Supervisory Control and Data Acquisition) operator interface. It is designed to monitor electrical substation data, such as voltage and current, and manage switchgear states through an simulated industrial environment.

The system utilizes a client-server architecture, where a background Modbus TCP server (RTU) generates real-time telemetry, and an interactive Dash-based dashboard provides a graphical human-machine interface (HMI).

---

## Technical Highlights

* **Industrial Communication:** Implements Modbus TCP protocol to facilitate data exchange between the simulated RTU and the monitoring dashboard.
* **Real-Time Data Processing:** Employs multi-threaded background processes to simulate continuous electrical load and switchgear activity.
* **Interactive Visualization:** Utilizes Plotly and Dash to render dynamic gauges and status indicators, mirroring the functionality of industrial control room consoles.
* **Modular Design:** Clearly separates the data simulation backend from the visualization layer, allowing for easy integration with actual PLC hardware in future iterations.

---

## Dashboard Preview

The following dashboard provides a real-time visualization of substation metrics, including voltage levels and current flow, with an integrated switchgear state indicator.

![SCADA Substation Monitoring Dashboard](assets/scada_dashboard_preview.png)
*Real-time operator dashboard displaying live voltage telemetry and switchgear status indicators*
---

## Repository Structure

The project is organized to maintain a clear separation between source code, documentation, and assets.

```text
scada-substation-monitor/
│
├── SCADA_Substation_Monitor_Main.ipynb  # Core implementation notebook
├── README.md                            # Project documentation
├── requirements.txt                     # Project dependencies
├── assets/                              # UI documentation and images
│   └── scada-dashboard-preview.png      # Dashboard interface screenshot
└── LICENSE                              # Project license

```
