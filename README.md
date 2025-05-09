👋 Hi, I’m Sam

I am working on projects regarding hardware acceleration, hardware-optimized programming and efficient software.
The main focus is autonomous systems and robotics, where I try to improve the efficiency both on computational and functional side
of scene understanding and motion planning.

# Publications


- **Autonomous Electric Race Car Inverter Development: Revving up the future with resource efficient drive technology**. *IEEE Electrification Magazine, vol. 11, no. 2*, 2023. [Link](https://ieeexplore.ieee.org/abstract/document/10143767)

# Projects
## THAMP: THAccelerated Motion Planner

This project developed as part of the [Driverless Mobility](https://github.com/DriverlessMobility) research group at Technical Univeristy of Applied Sciences Augsburg.

### Results

#### Straight Driving

#### Parking Vehicle

#### Overtaking

#### Avoidance

## Yolov4 Edge Object Detection: Jetson TX2 vs. Utlrascale MPSoC

Metrics are: FPS, W. On Jetson TX2 `jtop` was used to measure power consumption, on Ultrascale MPSoC `sysmon`was used.

### Evaluation Hardware

### Latency

| FPS    | Jetson TX2 | UltraZed
| -------- | ------- | -------
| Min  | 3.1 | 3.091
| Max | 3.4 | 3.202
| Avg    | 3.3 | 3.134

### Inference

| Power consumption [W]    | Jetson TX2 | UltraZed
| -------- | ------- | -------
| Inference Off  | 2.216 | 1.734
| Inference On | 9.955 | 2.641 
| Diff.    | 7.739 | 0.906 


## Formula Student Traction Inverter

### Hardware Interfaces
- [Motor Encoder Interface](https://github.com/samlei-research/endat_interface)
- [External Differntial ADC Interface](https://github.com/samlei-research/inverter_adc_interface)

### Software Interfaces:
- [Emdedded Linux CAN to AXI Interface](https://github.com/samlei-research/automatic_can_axi_mapper)

### Inverter Operating System 
- [Forked Uboot config](https://github.com/samlei-research/xlnx_uboot_custom)
- [Forked Xilinx Linux config](https://github.com/samlei-research/xilinx-linux_custom)

<!---
samlei-research/samlei-research is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
