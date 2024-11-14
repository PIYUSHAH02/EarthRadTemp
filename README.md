# EarthRadTemp
Planet Radius and Core Temperature Calculator
This project calculates the estimated radius and core temperature of a planet based on various planetary characteristics and environmental factors. It’s designed for educational purposes, especially in the field of mineralogy and planetary science.

Features
Input fields for parameters such as heat radiation rate, surface temperature, solar constant, albedo, formation time, and core/mantle density.
Functions to calculate:
Planet Radius based on radiative heat loss and other inputs.
Core Temperature considering formation time, density, and initial core temperature.
Quick access to preset values for Earth to simplify calculations.
Instructions for Use
Enter the relevant parameters for the planet in the provided input fields.
Click "Calculate Radius" or "Calculate Core Temperature" as needed to view results.
Note: Due to complexity, these calculations may not apply accurately to all planets.
Formulae Used
Planet Radius Calculation:
radius = sqrt((heatRadiationRate * solarConstant) / (4 * π * surfaceTemperature⁴ * (1 - albedo)))
Core Temperature Calculation:
coreTemperature = initialCoreTemperature - (heatRadiationRate * formationTime) / (coreMass * 800)
