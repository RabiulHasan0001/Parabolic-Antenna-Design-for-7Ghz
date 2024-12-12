# Parabolic Antenna Design at 7 GHz

### **Project Overview**
This project focuses on the design and simulation of a parabolic reflector antenna operating at a frequency of **7 GHz**. Using **CST Studio Suite**, a transient time-domain solver is employed to analyze the antenna's performance, ensuring optimal directivity and gain. The design integrates a **horn antenna** as the feed, illuminating the parabolic reflector to convert spherical waves into plane waves.

---

### **Introduction to Parabolic Reflector Antennas**
A **parabolic reflector antenna** utilizes a paraboloid-shaped reflecting surface to collect and re-radiate electromagnetic waves. It is widely regarded as the simplest and most efficient reflector antenna. The primary function is to transform spherical waves emitted by the feed antenna (typically a horn antenna) into plane waves, achieving a high degree of directivity. 

---

### **Design and Simulation**
- **Software**: CST Studio Suite
  - Utilized the **transient solver** for time-domain analysis.
  - Based on **Finite Domain Time Difference (FDTD)** methodology.
  - Simulation runtime: Approximately **8 hours**.

- **Antenna Specifications**:
  - Operating frequency: **7 GHz**
  - Feed antenna: **Circular horn waveguide** with a rectangular waveguide input.

---

### **Key Results**
1. **S-Parameter Analysis**:
   - S11 parameter is optimized at **6.876 GHz**, close to the operating frequency.
   - Achieved reflection coefficient value less than **-10 dB**, indicating minimal power reflection and efficient power transfer.

2. **Far-Field Radiation Pattern**:
   - Polar plot analysis shows a dominant **main lobe** with significantly smaller side lobes, indicating excellent directivity.

3. **VSWR (Voltage Standing Wave Ratio)**:
   - VSWR value: **1.001947**, confirming efficient antenna operation within the desired frequency range.

4. **Energy and Power Analysis**:
   - Plots confirm efficient radiation of power at the desired frequency with minimal losses.

5. **Field Analysis**:
   - **E-field**, **H-field**, and **surface current** distributions highlight proper antenna operation and propagation behavior.


Below are the key design parameters for the antenna:

| Name | Value (mm) |
|------|------------|
| A    | 0.005      |
| R    | 110        |
| Rt   | 8          |
| F    | 160        |
| Lf   | 42         |
| Lg   | 19         |
| Wg   | 16         |
| Hg   | 11         |
| Wa   | 27         |
| Ha   | 21         |
| Mt   | 0.9        |
| Rs   | 0.5        |
---

### **Figures and Visualizations**
- **Figure 1**: Parabolic Reflector Configuration
![Parabolic Antenna](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/1.PNG)
- **Figure 2**: S-Parameter Plot
![S-Parameter Plot](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/s%20paramete.PNG)
- **Figure 3**: Port Signal Analysis
![Port Signal Analysis](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/port%20signal.PNG)
- **Figure 4**: Energy Plot
![Energy Plot](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/energy.PNG)
- **Figure 5**: Far Field Radiation Pattern
![Far Field Radiation Pattern](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/far%20field.PNG)
- **Figure 6**: Power Acceptance and Outgoing Analysis
![Power Acceptance and Outgoing Analysis](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/power.PNG)
- **Figure 7**: VSWR Curve
![VSWR Curve](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/VSWR.png)
- **Figure 8**: Electric Field (E-field) Distribution
![Electric Field (E-field) Distribution](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/e%20field.PNG)
- **Figure 9**: Magnetic Field (H-field) Distribution
![Magnetic Field (H-field) Distribution](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/h%20field.PNG)
- **Figure 10**: Surface Current Visualization
![Surface Current Visualization](https://github.com/RabiulHasan0001/Parabolic-Antenna-Design-for-7Ghz/blob/main/Images/Surface%20Current.png)

---

### **Conclusion**
The simulation and design of the parabolic antenna at **7 GHz** using CST Studio Suite demonstrate the following:
- **High directivity and gain** due to the narrow beamwidth and minimal side lobes.
- Efficient power transfer with minimal reflection, as indicated by S-parameters and VSWR.
- Consistent performance in terms of electromagnetic field distribution and power radiation.

This project underscores the practicality of designing high-performance parabolic reflector antennas using advanced simulation tools. The results align with the desired performance benchmarks, making this design suitable for applications requiring precise and efficient wave propagation.

---

### **Team Members**
- **Avizit Nandi Avin** - ID: 1709018  
- **Nawaz Talukdar Sanglap** - ID: 1709016  
- **Md Rabiul Hasan** - ID: 1709017  


