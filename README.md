# 3D Printed Valve
A 3D printed valve is a device that has a membrane that opens or closes tubing depending on the way the membrane is flipped; acting analogously to a CMOS transistor in an electrical circuit. The soft fluidic valve can be configured as either an OR-gate, an AND-gate, or a NOT-gate. 

This repo will serve as an user guide for the 3D printable valve. Topics coverred includes: (1) Fabrication and Assembily Guide, (2) Characterization of the device, (3) Demostrations, (4) Tube extruding nozzle design, (5) Feedback from using the device as education tool. Since the design is based on the valve design introduced in the "Digital logic for soft devices" paper $^{[2]}$, we sometimes refer to our designs as soft bi-stable / mono-stable valve as well.


## Fabrication, Assembily and Configureation Guide

The fabricaiton of the devices are done on the [Prusa MK3S+ desktop 3D printer](https://www.prusa3d.com/product/original-prusa-i3-mk3s-3d-printer-3/). Filament used are [NinjaFlex 85A](https://ninjatek.com/shop/ninjaflex/) and [FilaFlex 60A](https://recreus.com/gb/filaments/1-filaflex-60a.html).

Details on how to fabricate, assemble and configure the soft valves are detailed in [this document](https://github.com/roboticmaterialsgroup/3D-printed-valve/blob/master/fabrication/Bi-stable_Valve_Fabrication_Instructions.pdf). 
The CAD file, stl file, gcode, printer configurations are also provided in the same folder.


## Characterization of the Device



## Demos


<!--
<div style="display: flex; flex-direction: row;">
    <img src="pic/nozzle_design.png" width="50%" />
    <p>
    hello
    </p>
    <img src="pic/nozzle_design.png" width="50%" />
</div>
-->

<div style="display: flex; align-items: center;">
    <div style="flex: 1;">
        <img src="pic/XOR_demo.png" style="max-width: 100%; height: auto;" />
    </div>
    <div style="flex: 1; padding: 0 20px;">
        <p>
        Optimised XOR gate. (A) An INHIBIT gate along with the truth table and schematic representation. (B) The circuit diagram of XOR gate with five logic gates. When we optimise the XOR gate using an INHIBIT gate, we only require three logic gates. (C) The assembly of a XOR gate from our 3D printed valves. (D) Implementation of an optimized XOR gate with the output directly connected to a soft display. When both inputs of the XOR gate are HIGH ($A=1$ and $B=1$), the output is LOW ($Q=0$).
        <!-- This demo shows how making the XOR gate from the mono-stable valves. It also showcases how the INHIBIT gate configuration can dramastically simplify the number of gates and connections in a circuit. This design trick is also evident in subsequent demos. -->
        </p>
    </div>

</div>

<br>
<div style="display: flex; align-items: center;">
    <div style="flex: 1;">
        <img src="pic/Dlatch_demo.png" style="max-width: 100%; height: auto;" />
    </div>
    <div style="flex: 1; padding: 0 20px;">
        <p>
        Optimized D-latch circuit. (A) The diagram of a conventional D-latch circuit from six logic gates and the optimized circuit from three logic gates using an INHIBIT gate with a set-reset latch. (B) We modified the 3D printed valve design to create a bistable device; bistable devices act as non-volatile SR latches. (C) Implementation of a D-latch using our 3D printed valves and a soft display. When both the data and clock inputs are HIGH ($D = 1$ and $CLK = 1$), the output turns HIGH ($Q=1$).
        </p>
    </div>
</div>




## Tube Extruding Nozzle Design

![](pic/nozzle_design.png)

This figure shows 3D model of the tube-extruding printing nozzle including a schematic and a cross-sectional view. 

[Here]() is a video showing the tube-extruding in progress.






## Link to supplemental resources
This file contains links to the supplemental information on how to construct the soft fluidic valve. It also includes important physical considerations for the operation of the valve. 


[1] A soft, bistable valve for autonomous control of soft actuators  
P. Rothemund, A. Ainla, L. Belding, D.J. Preston, S. Kurihara, Z. Suo, G.M. Whitesides  
[Science Robotics, 3(16), 2018](https://gmwgroup.harvard.edu/files/gmwgroup/files/1301.pdf)\
\
[2] Digital Logic for Soft Devices  
D.J. Preston, P. Rothemund, H.J. Jiang, M.P. Nemitz, J. Rawson, Z. Suo, G.M. Whitesides  
[Proceedings of the National Academy of Sciences (PNAS), 1820672116, 2019](https://gmwgroup.harvard.edu/files/gmwgroup/files/1318.pdf) \
\
[3] A Soft Ring Oscillator  
D.J. Preston, H.J. Jiang, V. Sanchez, P. Rothemund, J. Rawson, M.P. Nemitz, W.-K. Lee, Z. Suo, C.J. Walsh, G.M. Whitesides  
[Science Robotics, 4(31), 2019](https://gmwgroup.harvard.edu/files/gmwgroup/files/1323.pdf) \
\
[4] Soft Non-Volatile Memory for Non-Electronic Information Storage in Soft Robots  
M.P. Nemitz, C.K. Abrahamsson, L. Wille, D.J. Preston, A.A. Stokes, G.M. Whitesides  
[IEEE Soft Robotics Conference, New Haven, 2020](https://cpb-us-w2.wpmucdn.com/wp.wpi.edu/dist/e/484/files/2021/09/Soft_Non-Volatile_Memory_for_Non-Electronic_Information_Storage_in_Soft_Robots.pdf)  




## Fabrication of a 3D printed valve
Please read all instruction before you begin the process. 

<img width="1183" alt="Screen Shot 2022-03-08 at 7 34 11 AM" src="https://user-images.githubusercontent.com/68814774/157252858-aac9fc8c-4152-4e48-b00f-7ba56cdcffba.png">


### Materials 
* Ninjaflex 85A filament


### Setting up







## References
```
[1]:
@article{
doi:10.1073/pnas.1820672116,
author = {Daniel J. Preston  and Philipp Rothemund  and Haihui Joy Jiang  and Markus P. Nemitz  and Jeff Rawson  and Zhigang Suo  and George M. Whitesides },
title = {Digital logic for soft devices},
journal = {Proceedings of the National Academy of Sciences},
volume = {116},
number = {16},
pages = {7750-7759},
year = {2019},
doi = {10.1073/pnas.1820672116},
URL = {https://www.pnas.org/doi/abs/10.1073/pnas.1820672116}
}


```

