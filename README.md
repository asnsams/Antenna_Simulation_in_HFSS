# Antenna Simulation in HFSS

## TODO List

| Antenna Type       | To-Do         | Remarks                                                              |
|--------------------|---------------|----------------------------------------------------------------------|
| Dipole Antenna     | [✔]           | Configurations: [dipole[1]], [dipole[2]], [dipole[3]]                |
| Monopole Antenna   | [ ]           | Configuration: [monopole[1]]                                         |
| Bowtie Antenna     | [ ]           |                                                                      |
| Horn Antenna       | [ ]           |                                                                      |
| Patch Antenna      | [ ]           |                                                                      |
| Vivaldi Antenna    | [ ]           |                                                                      |
| Yagi-Uda Antenna   | [ ]           |                                                                      |

---

## Antenna Configurations

### **Dipole Antenna**
1. **dipole[1]:**  
   A lossless, center-fed dipole antenna with:
   - **Length**: \( l = \lambda_0 / 2 \)  
   - **Radius**: \( a = 0.02 \lambda_0 \)  
   - **Center Frequency**: \( f_0 = 900 \, \text{MHz} \)  
   - **Characteristic Impedance**: \( 75 \, \Omega \)  

2. **dipole[2]:**  
   A lossless dipole antenna with:
   - **Length**: \( l = \lambda_0 \)  
   - **Radius**: \( a = 0.02 \lambda_0 \)  
   - **Center Frequency**: \( f_0 = 900 \, \text{MHz} \)  
   - **Characteristic Impedance**: \( 75 \, \Omega \)  

3. **dipole[3]:**  
   A lossless, center-fed dipole antenna with:
   - **Length**: \( l = 3\lambda_0 / 2 \)  
   - **Radius**: \( a = 0.02 \lambda_0 \)  
   - **Center Frequency**: \( f_0 = 900 \, \text{MHz} \)  
   - **Characteristic Impedance**: \( 75 \, \Omega \)  

### **Monopole Antenna**
1. **monopole[1]:**  
   A lossless monopole antenna with:
   - **Length**: \( l = \lambda_0 / 4 \)  
   - **Radius**: \( a = 0.02 \lambda_0 \)  
   - **Center Frequency**: \( f_0 = 900 \, \text{MHz} \)  
   - **Characteristic Impedance**: \( 37.5 \, \Omega \)  

---

This repository organizes simulations and configurations for various antenna types. As tasks are completed, update the table by ticking the respective antennas.
