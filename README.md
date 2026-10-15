# Capstone-Project[GROUP-14]
# FAULT DETECTION IN A TRANSMISSION LINE

## Project Overview

This capstone project focuses on detecting and locating faults in a transmission line using Time-Domain Reflectometry (TDR) and mathematical modelling techniques.

The transmission line is modelled using electromagnetic principles and telegrapher equations. The equations are transformed into the Laplace domain and solved numerically using the Finite Difference Method (FDM). A Linear Programming (LP) approach is then used to reconstruct changes in the resistance and capacitance profiles to identify possible faults.

The project uses synthetic TDR data to demonstrate the fault reconstruction process.

## Objectives

- Develop a mathematical model of a transmission line.
- Formulate the governing Partial Differential Equations (PDEs).
- Apply the Laplace transform to analyse signal propagation.
- Use FDM to discretize the transmission-line model.
- Apply the CFL condition to check numerical stability.
- Use Linear Programming to reconstruct resistance and capacitance variations.
- Analyse TDR signals and reconstructed parameter profiles to identify faults.

## Methodology

The project follows a six-stage mathematical pipeline:

1. Field Model: Apply electromagnetic field principles.
2. PDE Formulation: Develop the telegrapher equations.
3. Laplace Transform: Express the equations in the transform domain.
4. Discretization: Apply FDM and check CFL stability.
5. Linear Programming: Reconstruct transmission-line parameter variations.
6. Verification: Analyse TDR and reconstruction plots.

## Tools and Technologies

- Python
- Google Colab
- NumPy
- SciPy
- Matplotlib
- LaTeX Overleaf 
- GitHub

## Simulation Parameters

Parameter| Value
Transmission-line length| 1.0 m
Number of spatial intervals| 49
Nominal resistance| 0.1 Ω/m
Nominal inductance| 250 nH/m
Nominal capacitance| 100 pF/m
Nominal conductance| 0 S/m
Fault resistance parameter| 0.4 Ω/m
Fault capacitance parameter| 60 pF/m

These parameters are used in the numerical simulation to demonstrate fault reconstruction.

## Results

The simulation generates synthetic TDR data and reconstructs resistance and capacitance profiles along the transmission line. The reconstructed profiles are compared with the nominal parameters to identify deviations associated with the simulated fault.

The residual error is also evaluated to assess the agreement between the simulated and reconstructed TDR responses.

## Limitations

- The study uses synthetic rather than experimentally measured TDR data.
- Reconstruction accuracy depends on noise levels and spatial discretization.
- The results depend on the assumptions used in the mathematical model.
- Experimental validation on a physical transmission line is not included.

## Conclusion

This project demonstrates how electromagnetic modelling, numerical methods, and optimization can be combined to study transmission-line signal integrity and reconstruct possible fault locations using synthetic TDR data.



**Branch:** Electronics and Communication Engineering (ECE)    
**Academic Year:** 2026

