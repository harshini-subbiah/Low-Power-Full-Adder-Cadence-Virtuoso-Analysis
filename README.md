Low-Power Full Adder Design & Technology Node Analysis
Cadence Virtuoso | CMOS VLSI | GPDK180 / GPDK090 / GPDK045
Overview

This project investigates the design and optimization of low-power CMOS Full Adders at the transistor level using Cadence Virtuoso. Multiple Full Adder implementations were analyzed across different CMOS technology nodes (180 nm, 90 nm, and 45 nm) to study the impact of technology scaling on:

Power Consumption
Propagation Delay
Area Efficiency
Overall Design Performance

The work demonstrates how transistor-level design choices influence the Power-Delay trade-off in arithmetic circuits used in modern ASICs and SoCs. The report compares conventional CMOS and pass-transistor-based implementations and examines their behavior under different technology nodes.

Objectives
Design transistor-level CMOS Full Adders
Simulate multiple Full Adder configurations
Compare CMOS technology nodes
Measure propagation delay
Measure dynamic power consumption
Analyze technology scaling effects
Identify the most efficient Full Adder architecture
Technologies Used
Tool	Purpose
Cadence Virtuoso	Schematic Design
Spectre Simulator	Circuit Simulation
GPDK180	180 nm CMOS
GPDK090	90 nm CMOS
GPDK045	45 nm CMOS
CMOS Logic	Digital Circuit Design
Full Adder Configurations

The project compares four transistor-level implementations of a Full Adder including conventional CMOS and CPL/pass-transistor based designs. Each configuration was implemented and evaluated under three CMOS technology nodes to compare power and timing characteristics.

Technology Nodes Evaluated
180 nm
90 nm
45 nm
Performance Metrics

The following metrics were analyzed:

Average Power Consumption
Propagation Delay
Power-Delay Trade-off
Technology Scaling Behaviour
Key Results

✔ Successfully implemented Full Adder circuits in Cadence Virtuoso.

✔ Compared four transistor-level architectures.

✔ Evaluated performance across three CMOS technology nodes.

✔ Observed significant reductions in power consumption and propagation delay as technology scaled from 180 nm to 45 nm.

✔ Demonstrated the trade-offs between different logic styles and transistor-level implementations.
