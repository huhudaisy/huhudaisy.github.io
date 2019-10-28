---
layout:     post
title:      "An IC Design of Traffic Light Controller"
date:       2019.09.02
author:     "Qianting"
header-img: "img/in-post/tag-bg.jpg"
catalog: True
tags:
    - Postgraduate
---

## An IC Design of Traffic Light Controller. 2017

This project was the term project for the course <<CMOS VLSI design>>, Prof.Yue-Kai Lo was our advising professor. This chip design project was based on SMIC 0.18um CMOS process design flow and EDA tools. And its main function was to control the display of traffic signal LED lights and the LED digital display.

This embedded Flash RAM Controller within FPGA  was controlled by a PC-Based system to download the digital function (HDL Verilog codes stored in FLASH RAM Memory) through an UART interface module, to modify its timing settings upon power-on-reset and downloading modes.

On our VLSI design project, we have covered all the phases of the Controller Chip Design, which included Specification Definition, Algorithm and Architural HDL Design, Verilog function Design with FPGA Verification and Validation Flows in the VLSI front-end design and physical layout backend design. These design procedures of the VLSI controller chip were including system design using C-Language; RTL-HDL programs using Verilog; Test-Vector generation of the testbench; Simulation using ModelSim; Emulation on an Altera FPGA function boards; Netlist was synthesized using Synopsys DC Compiler and SMIC PDK and Stand-Cell, Mixed-Signal IP Libraries; Logic gate and transistor levels of veriifcation with DFT, Automatic Pacement and Routing (APR) using Synopsys APR EDA Tools/Flows to generate the physical layout of the netlist with 0.18 uM Standard-Cell Library and IP Modules, till the final GDS2 of the XY-Mask Data for generating the photo mask levels to fabricate the VLSI chip.

* IC design process
![](/img/in-post/Traffic-light/ic-design.jpg)
* Realization by FPGA
![](/img/in-post/Traffic-light/fgpa.gif)
* The layout of traffic lights
![](/img/in-post/Traffic-light/layout.jpg)
