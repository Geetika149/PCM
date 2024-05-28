This repository contains an ANSYS Workbench file for simulating Phase Change Material (PCM) behavior using ANSYS Fluent.

PCM (Phase Change Material) analysis in ANSYS Fluent involves simulating the thermal behavior of materials that change phases (solid to liquid and vice versa) to absorb or release heat. This analysis is crucial for optimizing thermal management systems in various applications, such as electronics cooling, building insulation, and energy storage.

Getting Started
Follow these instructions to set up and run the PCM analysis.

Prerequisites
Ensure you have ANSYS Workbench and Fluent installed on your system.

Steps to Run the Simulation
Open ANSYS Workbench:

Launch ANSYS Workbench.
Load the Project:

Navigate to File > Open.
Select the Workbench file (*.wbpj) from this repository.
Review the Project Schematic:

Inspect the schematic for components: Geometry, Mesh, Setup, Solution, and Results.
Geometry and Mesh:

Geometry: Double-click the Geometry cell to review.
Mesh: Double-click the Mesh cell to verify mesh quality.
Setup:

Double-click the Setup cell to open ANSYS Fluent.
Material Properties: Define PCM properties (density, specific heat, thermal conductivity, melting point, latent heat).
Models: Enable the energy model and phase change model (enthalpy-porosity method).
Boundary Conditions: Set heat sources, sinks, and convective or radiative conditions.
Solution:

Configure solution settings: convergence criteria, solver parameters, and time-stepping method.
Click Run to start the simulation. Monitor convergence and adjust settings if necessary.
Post-Processing:

Double-click the Results cell to open the post-processing environment.
Analyze temperature distribution, phase change progression, and heat fluxes.
Generate plots and reports.
