# CFD Analysis of a Venturi Tube using ANSYS Fluent

## Project Overview
This project presents a numerical simulation of incompressible flow through a Venturi tube using ANSYS Fluent.  
The objective was to analyze velocity distribution, pressure drop, and validate the numerical results using analytical predictions based on Bernoulli equation.

## Model Description
- Flow type: Laminar
- Maximum Reynolds number: 4.2
- Inlet velocity: 0.01 m/s
- Fluid: Glycerin
- Mesh type: Structured
- Number of elements: 20,634

## Mesh Independence Study
A mesh independence study was performed to ensure the accuracy of numerical results and eliminate grid-related errors.

## Results

### Velocity Contour
![Velocity](images/velocity_contour.png)

The velocity increases significantly at the throat section due to the reduction in cross-sectional area, consistent with the continuity equation.

### Pressure Contour
![Pressure](images/pressure_contour.png)

A noticeable pressure drop is observed at the throat region, which aligns with Bernoulli’s principle for incompressible steady flow.

### Reynolds Number Contour
![Reynolds](images/reynolds_number_contour.png)

The Reynolds number distribution confirms laminar flow behavior throughout the domain.

## Validation
Simulation results were compared with analytical predictions derived from Bernoulli equation.  
The numerical results showed good agreement with theoretical expectations.

## Conclusion
The CFD simulation successfully captured the velocity acceleration and pressure drop within the Venturi tube.  
Results demonstrated strong consistency with analytical solutions and validated the numerical modeling approach.

## Future Work
Future extensions of this project may include:
- Coupling CFD simulations with machine learning models for surrogate modeling
- Fast prediction of pressure drop using data-driven approaches
- Extension to turbulent flow regimes
