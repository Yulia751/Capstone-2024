# Capstone-2024
**Title: Design & Optimization of Motor & Fan Assembly for an eVTOL Aircraft**

**_Disclaimer: Metrics are redacted due to NDA_**

_Supervisor: Dr. Sayyed Ali Hosseini (BSc, MSc, PhD, P.Eng)_

_Team Members :Yulia Isaeva (me), Afraz Malik, Andy Zhou, Rabih Alameddine, Shil Patel, Ubaid Ubaid_

# Project Overview
This capstone project, completed in partnership with Horizon Aircraft, focused on the design and optimization of an eVTOL propulsion system. The project centered around the Cavorite X7 propulsion system, a key component of Horizon Aircraft’s eVTOL development. My work primarily involved conducting CFD simulations, with a strong emphasis on boundary layer configurations and simulation results. Additionally, we developed MATLAB code to support these simulations and analyze the data. The project was a success, culminating in the optimization of the rotor efficiency, contributing valuable insights into the design and performance of eVTOL propulsion systems.

![1  Rotor CAD Model](https://github.com/user-attachments/assets/838250c0-aeff-43ec-a9b4-8c100b551b4f)
![x7](https://github.com/user-attachments/assets/0391e5ff-6fed-406a-bf66-e23c24b6ed00)

# Literature Reveiw
For the design and optimization of the Cavorite X7 propulsion system, we conducted extensive research and analysis:

**Airfoil Selection:** Evaluated 80+ airfoil candidates using performance indexes based on:


- Lift-to-drag ratio


- Industry Application


- Drag coefficient


**CFD Simulations:** Ran numerous 2D simulations in ANSYS Fluent, focusing on:


- Boundary layer behavior


- Pressure distribution


- Vortex formation


**Outcome:** Optimized airfoil choices to enhance rotor efficiency and reduce power consumption.


# 3D CFD Simulations with ANSYS Fluent

![4  Setup CFD Example](https://github.com/user-attachments/assets/37fd84f5-ba80-4336-9a05-3fc1d3cce3b3)

For the 3D simulation of the Cavorite X7 propulsion system, we focused on optimizing rotor performance with ANSYS Fluent:

**Meshing:** Applied structured meshing for accuracy. The mesh settings were calculated using a custom MATLAB Script.


**Boundary Layer:** Prioritized boundary layer configuration to improve airflow prediction. Did this by determining the Y+ factor and applying in the simulation settings. 

![2  Boundary Layer Example - ANSYS Fluent](https://github.com/user-attachments/assets/961135e5-0946-491e-90fb-8138e7fedde7)

**Turbulence Modeling:** Modeled turbulence effects over rotor blades to determine stall areas and vertices.


**RPM Simulation:** Ran simulations at 7800 RPM to capture operating conditions.


**Convergence:** Set convergence conditions to minimize processing time while maintaining result accuracy.
![5  CFD Pathline](https://github.com/user-attachments/assets/8cc08573-a429-4946-b376-016d72ab88b5)


# Final Results
The simulation results compared rotor lift, overall lift, and rotor torque, with rotor torque maintained near 3.8 lb.ft for accurate simulation. The rotors were additive manufactured using ABS material, and the testing rig and system model were scaled to 40% of the actual design. During the testing process, rotors were mounted onto the test rig and tested at various RPM values (4250, 6025, and 7800). Key findings included the SG6043-rev5 achieving the highest overall lift, and the DAE21-rev6 having the highest average figure of merit (F.O.M.). Further modifications in segment analysis could further increase the lift.

# Acknowledgements 
For their invaluable support, guidance and expertise throughout this project, we extend our gratitude to the Horizon Aircraft team. We also thank Tim Clarke and Mehrdad Sadeghieh from the Machining Research Lab (MRL) for extending their equipment and services.
