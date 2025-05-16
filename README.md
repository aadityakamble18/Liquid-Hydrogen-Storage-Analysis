# Liquid Hydrogen Storage – FEA-Based Design Analysis

This repository contains all design, simulation, and result files for the course project titled **"Simulation and Analysis of a Liquid Hydrogen Storage Vessel"**, completed as part of the **Mechanics of Solids** course at IIT Jodhpur.

## Project Overview

Hydrogen, the lightest and most abundant element in the universe, plays a vital role in clean energy systems. In its **liquid form (LH₂)**, hydrogen has high energy density and is critical for applications such as **rocket propulsion** and **hydrogen fuel infrastructure**. However, due to its cryogenic nature (boiling point: −252.87°C), the storage of liquid hydrogen demands specialized high-strength containers with excellent thermal insulation and structural integrity.

In this project, we designed a cryogenic hydrogen pressure vessel in CAD software and analyzed its mechanical performance under internal pressure conditions using Finite Element Analysis (FEA) across four different materials. The goal was to evaluate and compare structural performance and identify the most optimal material based on mechanical stress, strain, deformation, and strain energy.

## Team Members

**Team Name:** Team Protium

- Aaditya Kamble – B22MT024  
- Vishvajeethsinh Jadeja – B22MT023  
- Sahil – B22MT038  

**Course Instructor:** Dr. Hirishikesh

## Technical Summary

### Pressure Vessel Specifications

- **Length:** 8270 mm  
- **Outer Diameter:** 2300 mm  
- **Wall Thickness:** 39 mm  
- **Internal Pressure:** 35 MPa  
- **Operating Temperature:** -25°C (ambient)  
- **Boundary Condition:** One fixed support at the vessel's mouth  

The analysis considered both **thin-walled** and **thick-walled** pressure vessel theory using Lamé’s equations to evaluate hoop, longitudinal, and radial stresses.

## Materials Simulated

1. Structural Steel  
2. Magnesium  
3. AL7075-T6 (Aluminium Alloy)  
4. Ti-6Al-4V (Titanium Alloy)

Each material was analyzed under identical loading and boundary conditions using ANSYS Workbench.

## Key Simulation Results

| Property              | AL7075-T6       | Magnesium        | Structural Steel | Ti-6Al-4V        |
|----------------------|-----------------|------------------|------------------|------------------|
| Max Stress (Pa)      | 7.33 × 10⁹      | 7.43 × 10⁹       | 7.19 × 10⁹       | 4.29 × 10⁹       |
| Max Strain           | 0.10477         | 0.17683          | 0.03597          | 0.04014          |
| Max Deformation (m)  | 0.65446         | 1.0749           | 0.23365          | 11.537           |
| Strain Energy (J)    | 22,333          | 36,782           | 7,934.5          | 568,620          |

All values were extracted from simulation results and plotted using Origin. The `Results/` folder contains the Origin files used for graphing and comparison.

## Repository Structure

├── Results/

│ └── Graphs and Origin files for parameter comparisons

├── Structural_Steel/

│ └── ANSYS simulation files and result data

├── Magnesium/

│ └── ANSYS simulation files and result data

├── AL7075-T6/

│ └── ANSYS simulation files and result data

├── Ti-6Al-4V/

│ └── ANSYS simulation files and result data


## Engineering Concepts Applied

- Pressure Vessel Theory (Thin and Thick Wall)
- Hoop Stress, Longitudinal Stress, Radial Stress
- Lamé’s Equations
- Thermo-mechanical Simulation
- Finite Element Analysis (ANSYS)
- Material Behavior under Cryogenic Conditions

## Future Work

- Incorporation of thermal insulation and thermal stress analysis  
- Evaluation under fatigue/cyclic loading conditions  
- Optimization of geometry and material for weight and cost  
- Use of composite or multilayer materials for hybrid design

## Contact

For further information, feel free to contact:

- Aaditya Kamble – [b22mt024@iitj.ac.in](mailto:b22mt024@iitj.ac.in)  
- Vishvajeethsinh Jadeja – [b22mt023@iitj.ac.in](mailto:b22mt023@iitj.ac.in)  
- Sahil – [b22mt038@iitj.ac.in](mailto:b22mt038@iitj.ac.in)
