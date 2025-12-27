# solar_wind_induction
Exploration of Electricity by Solar-Wind Tower on Expressway from Motion of Vehicles and Solar Irradiance and Its Utilization in EV Charging.

** just to small note for informational purpose**
I will be including 3 different project in this together and they will be in branches
just so you guys can look at it clearly without any mess 
my files will required password
so if you want to have access to it you have to ask me for password
just to keep the track of it
its a hard work of mine and mits a hard work of mine and my college mate afterall
for next I will work tomorrow.... 
#  Solar PV System with MPPT (P&O) Controlled DC–DC Converter

##  Project Overview
This project demonstrates the **modeling and simulation of a Solar Photovoltaic (PV) system** integrated with a **Maximum Power Point Tracking (MPPT)** controller using the **Perturb and Observe (P&O) algorithm**.  
The MPPT algorithm controls a **DC–DC converter** to extract **maximum available power** from the PV array under varying **irradiance and temperature** conditions.

The system is developed using **MATLAB/Simulink** in **discrete-time mode**, making it suitable for power electronics and renewable energy studies.

---

##  System Components

###  PV Array
- Generates DC power based on:
  - Solar irradiance
  - Temperature
- Outputs:
  - PV Voltage (Vpv)
  - PV Current (Ipv)

###  MPPT Controller (Perturb & Observe)
- Calculates PV power using Vpv and Ipv
- Continuously perturbs operating voltage
- Adjusts duty cycle to track the **Maximum Power Point (MPP)**

###  PWM Generator
- Converts MPPT duty cycle into PWM pulses
- Drives the DC–DC converter switch

###  DC–DC Converter
- Consists of:
  - Switch (MOSFET/IGBT)
  - Inductor
  - Diode
  - Capacitor
- Transfers maximum power from PV array to the load

###  Load
- Resistive DC load
- Output voltage and current are monitored

---

##  Simulation Details
- Platform: **MATLAB/Simulink**
- Simulation type: **Discrete**
- Sample time: **1e-6 seconds**
- Power electronics modeled using Simulink blocks

---

##  Results & Observations
- MPPT successfully tracks the maximum power point
- Output power improves compared to non-MPPT operation
- System adapts to changes in irradiance
- Stable output voltage at the load

---

##  Applications
- Solar energy systems
- EV charging stations
- DC microgrids
- Renewable energy research

---

##  Learning Outcomes
- Understanding PV characteristics
- MPPT algorithm implementation
- DC–DC converter operation
- Power electronics simulation in MATLAB

---

##  How to Run the Model
1. Open MATLAB
2. Navigate to the project folder
3. Open the `.slx` file
4. Run the simulation
5. Observe waveforms for Vpv, Ipv, and output voltage

---

##  Author
**Swati Sharma**  
Electrical Engineer | EV & Renewable Energy Enthusiast  

---

⭐ *If you find this project useful, feel free to star the repository!*
