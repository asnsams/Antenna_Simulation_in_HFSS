# Antenna Simulation in HFSS

## TODO List

| Antenna Type       | To-Do         | File Name             | Configuration                         |
|--------------------|---------------|-----------------------|---------------------------------------|
| Dipole Antenna     | [✔]           | `dipole_simulation.hfss` | Half-Wavelength, Full-Wavelength, 1.5-Wavelength |
| Monopole Antenna   | [ ]           | `monopole_simulation.hfss` | Quarter-Wavelength                    |
| Bowtie Antenna     | [ ]           | `bowtie_simulation.hfss`  | TBD                                   |
| Horn Antenna       | [ ]           | `horn_simulation.hfss`    | TBD                                   |
| Patch Antenna      | [ ]           | `patch_simulation.hfss`   | TBD                                   |
| Vivaldi Antenna    | [ ]           | `vivaldi_simulation.hfss` | TBD                                   |
| Yagi-Uda Antenna   | [ ]           | `yagi_uda_simulation.hfss`| TBD                                   |

---

## Antenna Configurations

### Dipole Antenna
1. **Half-Wavelength Dipole:**  
   - **Length**: <code>l = λ<sub>0</sub> / 2</code>  
   - **Radius**: <code>a = 0.02λ<sub>0</sub></code>  
   - **Center Frequency**: <code>f<sub>0</sub> = 900 MHz</code>  
   - **Characteristic Impedance**: <code>75 Ω</code>  

2. **Full-Wavelength Dipole:**  
   - **Length**: <code>l = λ<sub>0</sub></code>  
   - **Radius**: <code>a = 0.02λ<sub>0</sub></code>  
   - **Center Frequency**: <code>f<sub>0</sub> = 900 MHz</code>  
   - **Characteristic Impedance**: <code>75 Ω</code>  

3. **1.5-Wavelength Dipole:**  
   - **Length**: <code>l = 3λ<sub>0</sub> / 2</code>  
   - **Radius**: <code>a = 0.02λ<sub>0</sub></code>  
   - **Center Frequency**: <code>f<sub>0</sub> = 900 MHz</code>  
   - **Characteristic Impedance**: <code>75 Ω</code>  

---

### Monopole Antenna
1. **Quarter-Wavelength Monopole:**  
   - **Length**: <code>l = λ<sub>0</sub> / 4</code>  
   - **Radius**: <code>a = 0.02λ<sub>0</sub></code>  
   - **Center Frequency**: <code>f<sub>0</sub> = 900 MHz</code>  
   - **Characteristic Impedance**: <code>37.5 Ω</code>  
