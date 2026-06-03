# DC-DC-Zeta-Converter
DC-DC Zeta Converter for buck-boost voltage regulation

This project is part of EE 252 EMPEL Lab under Prof. Vijay A. S. and focuses on the design, simulation, and hardware realization of a **DC–DC Zeta Converter** using TL494 PWM control.

---

##  Objective
To design and implement a non-isolated DC–DC Zeta Converter and analyze its performance in CCM and DCM modes using simulation and hardware testing  

---

## ⚙️ Circuit Implementation
The converter is implemented using:

- TL494 PWM controller IC for pulse generation  
- TC4428A gate driver IC for MOSFET driving  
- IRFZ44N MOSFET as switching device  
- QH08TZ600 fast recovery diode  
- Inductor (1 mH) for energy transfer  
- Capacitor filter network for output smoothing  
- Variable rheostat load for testing  

---

##  Work Done
- Designed and soldered TL494-based PWM driver circuit  
- Verified PWM frequency and duty cycle using oscilloscope  
- Built and tested Zeta converter hardware on PCB/perf board  
- Performed MATLAB/Simulink simulation (if applicable)  
- Tested converter under different load conditions  
- Observed CCM and DCM operation  

---

##  Observations / Results
- Stable PWM pulses generated using TL494  
- Verified switching operation at specified frequency (~5–20 kHz)  
- Observed inductor current and diode conduction behavior  
- Achieved regulated output voltage (buck–boost behavior)  
- Compared simulation results with hardware performance  

---

## Safety Precautions
- Ensured isolation between gate drive and power ground  
- Load connected before powering the circuit  
- Current limited to avoid inductor saturation (<1.5 A)  
- Used proper oscilloscope measurement technique  

---

## Repository Contents
- Circuit diagram images  
- Hardware setup photos  
- Simulation results (MATLAB/Simulink)  
- Waveform screenshots (CCM & DCM)  
- Project report (PDF)  
- README documentation  

---

## Guide
- Project: DC–DC Zeta Converter  
- Instructor: Prof. Vijay A. S.  
- Institute: IIT Indore (EMPEL Lab)

---

## 📌 Note
This project is part of the EMPEL Lab requirement and demonstrates practical implementation of power electronic DC–DC converters using PWM control techniques.
