# Robot Health Monitoring & Fault Diagnostics System

A Python-based simulation of a robot motor health monitoring system designed to identify abnormal operating conditions through sensor data analysis.

## Project Overview

The system simulates three motors operating under normal conditions and introduces faults to demonstrate automated fault detection and monitoring.

## Key Features
- Simulation of motor RPM, temperature and current readings.
- Fault injection for overheating, overcurrent and low-speed conditions.
- Threshold-based fault detection and classification.
- Automated fault event logging.
- Fault distribution visualization and event summaries.
- Interactive motor selection and individual sensor inspection.

## Technologies Used
Python, NumPy, Pandas, Matplotlib, Plotly, ipywidgets.

## Fault Conditions Simulated

| Motor | Fault | Detection Parameter |
|---|---|---|
| Motor 1 | Overheating | Temperature |
| Motor 2 | Overcurrent | Electrical Current |
| Motor 3 | Low Speed | Rotational Speed (RPM) |

## Methodology
1. Generate simulated motor sensor readings.
2. Introduce abnormal operating conditions.
3. Compare readings against predefined thresholds.
4. Classify faults and generate event logs.
5. Visualize motor performance and inspect individual motors.

## Note
This project uses simulated sensor data and rule-based fault detection. It is a software prototype and is not connected to physical robotic hardware.

## Author
Lohitaksha Guha  
B.Tech Mechanical Engineering, IIT Patna
