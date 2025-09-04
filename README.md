# VASP6.5-Thermoelectric-Properties
VASP 6.5.0 Tutorial, Seebeck, Conductivity, Power Factor, ZT, Carrier Mobility, Thermoelectrics

VASP 6.5.0 Thermoelectric Properties Tutorial:

This repository contains VASP 6.5.0 input and output files for calculating thermoelectric properties, including temperature-dependent carrier mobility. It accompanies the tutorial video: https://youtu.be/dfV7KeBYceo?si=BWWxJ5ckmQVSdxVE
.

Features

Using VASP 6.5, you can directly calculate key thermoelectric properties without any supporting software:

Seebeck Coefficient (S)

Electronic Conductivity (σ)

Electronic Thermal Conductivity (κₑ)

Power Factor (PF)

Figure of Merit (ZT)

Carrier Mobility (temperature-dependent)

Files in this Repository

INCAR – VASP input configuration for thermoelectric calculations

KPOINTS – K-point mesh file

POSCAR – Structure file

OUTCAR – Output file with calculated TE properties

.dat files – Generated property data for plotting

plot_scripts/ – Optional scripts to plot Seebeck, Power Factor, and other properties

Tutorial Steps

Prepare input files (INCAR, KPOINTS, POSCAR) for your material.

Run VASP 6.5 calculations.

Extract properties from OUTCAR.

Generate .dat files for Seebeck, Conductivity, Power Factor, and Carrier Mobility.

Plot graphs (e.g., Power Factor vs Temperature) using XMgrace or your preferred software.

Reference Video

Full step-by-step tutorial on calculating thermoelectric properties in VASP 6.5:
Watch on YouTube: https://youtu.be/dfV7KeBYceo?si=BWWxJ5ckmQVSdxVE 
