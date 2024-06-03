# TaON_100_Water

## Description
This repository contains input files and the coordinate file (in XYZ format) for simulating the β-TaON (100)/Water system, as studied in the paper "Molecular Insights into the Water Dissociation and Proton Dynamics at the β-TaON (100)/Water Interface."

## Files

### Input Files
- **input_QBO.in**: CPMD input file for the Quench Born-Oppenheimer (BO) step. This file sets up the initial conditions and parameters for the quenching BO procedure.
- **input_prod_run_0.in**: CPMD input file for the initial production run. This file contains the settings and parameters for starting the molecular dynamics simulation.
- **input_prod_run_1.in**: CPMD input file for continuing the production run. This file is used to extend the molecular dynamics simulation from where the initial production run ended.

### Coordinate File
- **TaON-Water.xyz**: A few representative snapshots throughout the whole trajectory of the simulation. This file provides the atomic coordinates at different MD steps.

### Pseudopotential Files
- **Ta_VDB_PBE1.USPP**: Pseudopotential file for Tantalum (Ta). 
- **o.pbe.vb.txt**: Pseudopotential file for Oxygen (O).
- **n.pbe.vb.txt**: Pseudopotential file for Nitrogen (N). 
- **h.pbe.vb.txt**: Pseudopotential file for Hydrogen (H). 

## Usage
To use these files for your own simulations, ensure that you have CPMD installed and configured on your system. Place the input files and pseudopotential files in the appropriate directories and modify the input files as needed for your specific simulation requirements.

## References
For more details on the methods and results, please refer to the paper: "Molecular Insights into the Water Dissociation and Proton Dynamics at the β-TaON (100)/Water Interface."
