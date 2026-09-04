# Smart EV BMS AI

Physics-Informed Interactive Battery Management and Energy Management
Framework for Electric Vehicles

## Overview

This repository contains the implementation of an interactive EV
Battery Management System and vehicle energy-management simulation.

The framework integrates:

- Battery State of Charge (SOC)
- Battery State of Health (SOH)
- Battery temperature
- Outdoor temperature
- HVAC temperature
- Vehicle speed
- Vehicle payload
- Individual tire pressures
- Drive mode
- Battery power estimation
- Energy consumption
- Remaining driving range
- Battery stress estimation
- Sensor fault detection
- Warning and alert generation
- Interactive real-time visualization

## Research Objectives

To develop an interactive EV Battery Management and Energy Management simulation that evaluates
the combined influence of battery, vehicle, environmental and sensor parameters on battery power demand,
energy consumption, battery stress and estimated driving range,
while providing real-time warnings and sensor-failure diagnostics

## Implementation

The project is implemented in Python using Google Colab.

## Main Notebook

`notebooks/BMS_with_live_chart.ipynb`

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells.
3. Adjust the interactive parameters.
4. Observe the calculated battery power, range, stress index,
   warnings, and live plots.

## Input Parameters

- SOC
- SOH
- Battery temperature
- Outdoor temperature
- AC temperature
- Vehicle speed
- Payload
- Front-left tire pressure
- Front-right tire pressure
- Rear-left tire pressure
- Rear-right tire pressure
- Drive mode

## License

See LICENSE.

## Citation

If you use this software in academic research, please cite the
associated research publication.
