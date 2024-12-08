# Antenna Simulation in HFSS
[Repo will be updated on Dec, 2024] 
This repository contains a collection of antenna simulations completed as part of the course **ECE 421: Introduction to Antennas and Wireless Propagation**, as well as some additional personal antenna projects. The final entry in the table corresponds to the course **final project**, which is yet to be completed. Each simulation includes key configurations, results, and analysis for different types of antennas.


<h2>TODO List</h2>

<h3>Mid-Stage Simulations:</h3>
<table>
  <thead>
    <tr>
      <th>Antenna Type</th>
      <th>To-Do</th>
      <th>File Name</th>
      <th>Configuration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dipole Antenna</td>
      <td>[ ]</td>
      <td><code>dipole_halfwave.hfss</code></td>
      <td>Half-Wavelength</td>
    </tr>
    <tr>
      <td>Dipole Antenna</td>
      <td>[ ]</td>
      <td><code>dipole_fullwave.hfss</code></td>
      <td>Full-Wavelength</td>
    </tr>
    <tr>
      <td>Dipole Antenna</td>
      <td>[ ]</td>
      <td><code>dipole_1_5wave.hfss</code></td>
      <td>1.5-Wavelength</td>
    </tr>
    <tr>
      <td>Monopole Antenna</td>
      <td>[ ]</td>
      <td><code>monopole_simulation.hfss</code></td>
      <td>Quarter-Wavelength</td>
    </tr>
    <tr>
      <td>Yagi-Uda Antenna</td>
      <td>[ ]</td>
      <td><code>yagi_uda_simulation.hfss</code></td>
      <td>-</td>
    </tr>
  </tbody>
</table>

<h3>Final Simulations:</h3>
<table>
  <thead>
    <tr>
      <th>Antenna Type</th>
      <th>To-Do</th>
      <th>File Name</th>
      <th>Configuration</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Multi-band Quasi-Yagi Antenna</td>
      <td>[ ]</td>
      <td><code>quasi_yagi_mb_simulation.hfss</code></td>
      <td>-</td>
    </tr>
  </tbody>
</table>

----

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
