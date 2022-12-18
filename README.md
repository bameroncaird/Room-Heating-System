# Room-Heating-System
This repository contains my Fall 2022 final project for CS6376: Foundations of Hybrid and Embedded Systems at Vanderbilt University. In this project, I built a multi-room heating system using MATLAB and Simulink. Below is the interface (inputs and outputs) for the system.

![Interface (inputs & outputs) for the system.](https://github.com/bameroncaird/Room-Heating-System/blob/main/paper_interface.png?raw=true)

## Report and Specifications

- Final_Project_Report.pdf contains the LaTeX document describing the project. This is a paper-style report using IEEE double column formatting.
- Original_Specifications.pdf contains the baseline specifications provided for this final project. All credit goes to Dr. Abhishek Dubey, the CS6376 instructor, for these specifications.

## Running the project on your machine

The Simulink model is self-contained in the heating_system_model.slx file. As described in the report, I developed and ran all the code and simulations using the latest version of MATLAB (R2022b) on the Windows 11 Pro operating system. If you need to install the latest version of MATLAB, you can see more about that process [here](https://www.mathworks.com/downloads). To run simulations locally (assuming you have MATLAB installed), follow these steps:

1. Get access to the heating_system_model.slx file, either by cloning this repo or downloading it directly.

2. Open the file in Simulink.

3. Click the big green "Run" button at the top of Simulink's "Simulation" window to simulate the heating system.

4. Use the different Simulink Scope blocks to visualize the output. There are comments in the heating_system_model.slx file detailing which scope block corresponds to which output.

## Project Demo

Below is a demonstration of me simulating this system on my machine. This is mainly so Dr. Dubey can see that this code was in fact working at one point.

![Project demo.](https://github.com/bameroncaird/Room-Heating-System/blob/main/demo.mp4?raw=true)
