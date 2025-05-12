# Supercapacitor and Batteries Hybrid Energy Storage System

## Author
Phạm Lê Ngọc Sơn

## Project Description
This project implements a hybrid energy storage system using supercapacitors (SC) and batteries in conjunction with a boost converter. The system is designed to optimize energy efficiency by leveraging the high power density of supercapacitors with the high energy density of batteries.

## Project Contents
The project consists primarily of a MATLAB/Simulink model that simulates the behavior of:
- Parallel connection of batteries and supercapacitors
- Boost converter for voltage regulation
- Control systems for energy management

## Project Structure
- `parallel_battery_SC_boost_converter.slx`: The main Simulink model file
- `parallel_battery_SC_boost_converter.slxc`: Simulink cache file
- `slprj/`: Simulink project folder containing simulation data

## How to Use
1. **Prerequisites**:
   - MATLAB R2020a or newer
   - Simulink
   - Simscape Electrical library

2. **Running the Simulation**:
   - Open the `parallel_battery_SC_boost_converter.slx` file in MATLAB/Simulink
   - Review the model parameters in the initialization scripts if any
   - Run the simulation using the "Run" button in Simulink
   - Analyze the results using the scope blocks integrated in the model

3. **Key Parameters**:
   - Battery parameters (capacity, internal resistance)
   - Supercapacitor parameters (capacitance, ESR)
   - Boost converter settings (switching frequency, duty cycle)

## Technical Background
This model demonstrates the advantage of hybrid energy storage systems where:
- Supercapacitors handle high-power, short-duration loads
- Batteries provide steady energy for long-duration operation
- The boost converter regulates the output voltage to a stable level

The parallel configuration allows for efficient energy management and extended battery life by reducing stress during high-power demands.