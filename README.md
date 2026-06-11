# AC-to-DC-Power-Supply-Design-and-PCB-Implementation
Overview

This project was developed as part of the Electronics I course and focuses on the design, simulation, PCB implementation, and experimental validation of AC-to-DC power supply circuits.

The objective was to convert an 8 V, 500 Hz sinusoidal AC input into regulated DC outputs while satisfying strict ripple and component constraints.

Design Specifications
Input
Sinusoidal AC source
Amplitude: 8 V
Frequency: 500 Hz
Constraints
Maximum output ripple: 0.05 V
Maximum capacitor value: 500 μF
Load resistance: 100 Ω
PCB size constraint: 5 cm × 5 cm
Zener diode regulation using approximately:
5.1 V Zener diode
12 V Zener diode
Part I – 5 V Regulated Power Supply
Objective

Design an AC-to-DC converter capable of producing a regulated 5 V DC output from the specified AC source.

Tasks Performed
Circuit analysis and component selection
Ripple calculation
Schematic design in ADS
Simulation and performance verification
PCB design using Altium Designer
PCB fabrication and hardware testing
Results

The implemented circuit successfully generated a regulated 5 V output while maintaining the ripple within the specified limit.

Part II – 12 V Regulated Power Supply
Objective

Design an AC-to-DC converter capable of producing a regulated 12 V DC output from the specified AC source.

Tasks Performed
Circuit analysis and component selection
Ripple calculation
Schematic design in ADS
Simulation and performance verification
PCB design using Altium Designer
PCB fabrication and hardware testing
Results

The implemented circuit successfully generated a regulated 12 V output while satisfying the ripple constraint requirements.

Design Workflow
Theoretical analysis and component sizing
Ripple and regulation calculations
ADS schematic design and simulation
PCB layout design in Altium Designer
PCB fabrication
Hardware assembly
Experimental validation
Repository Structure
schematic/ : ADS schematics
pcb/ : PCB layouts and design files
simulation/ : Simulation results and waveform analysis
photos/ : Fabricated PCB and hardware images
report/ : Final project report
Tools
ADS (Advanced Design System)
Altium Designer
Achievement

The project received the highest score in the class and was successfully validated through both simulation and hardware implementation.

## Key Results

### 5V Regulated Output

The designed circuit successfully achieved a regulated 5V DC output while maintaining the output ripple below the specified 0.05V limit.

### 12V Regulated Output

The second design provided a stable 12V DC output and satisfied the required ripple constraint under the specified load conditions.

### PCB Implementation

The PCB was designed in Altium Designer under a 5 cm × 5 cm size constraint, fabricated, assembled, and experimentally validated.
