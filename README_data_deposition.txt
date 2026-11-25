README: DATA DEPOSITION
This repository contains the structural and computational data generated during the investigation of wild-type (WT), loss-of-function (LOF), and gain-of-function (GOF) variants of the PCSK9–LDLR complex.

The deposited dataset includes modeled three-dimensional protein structures, 500 ns molecular dynamics (MD) simulation trajectories, trajectory analysis outputs, conformational clustering results, representative structures, and protein structural network (PSN) analysis data.

The repository is organized into the following folders:

1. Modeled Structures
Folder: Modeled structures/

Contains two subfolders:

Gain of Function/ – Contains the modeled three-dimensional structures of the selected GOF variants.
Loss of Function/ – Contains the modeled three-dimensional structures of the selected LOF variants.
Both subfolders also include the wild-type (WT) PCSK9–LDLR complex structure (PDB ID: 3M0C), which, along with the modeled variant structures, was used as the initial input for molecular dynamics simulations.

2. Molecular Dynamics Simulation Structures
Folder: MDS 500ns structures/

Contains the structural trajectory data generated from 500 ns molecular dynamics simulations of the WT PCSK9–LDLR complex and selected LOF and GOF variants.

The data are organized into two subfolders:

Gain of Function/ – Contains MD simulation structures of the WT and selected GOF variants.
Loss of Function/ – Contains MD simulation structures of the WT and selected LOF variants.
These structures represent the conformational evolution of the protein complex during the 500 ns simulation period.

3. Molecular Dynamics (MD) Analysis Outputs
The MD trajectory analysis outputs are provided in separate folders for LOF and GOF variants. Each folder contains the corresponding numerical data and supporting outputs generated from the analysis of 500 ns MD trajectories.

A. Loss-of-Function (LOF) Variant Analysis

Folder	Description
LOF RMSD/	Root Mean Square Deviation (RMSD) analysis.
LOF RMSF/	Root Mean Square Fluctuation (RMSF) analysis.
LOF SASA/	Solvent Accessible Surface Area (SASA) analysis.
LOF Rg/	Radius of Gyration (Rg) analysis.
LOF PCA/	Principal Component Analysis (PCA) outputs.
LOF PSN Analysis/	Protein Structural Network (PSN) analysis outputs.
B. Gain-of-Function (GOF) Variant Analysis

Folder	Description
GOF RMSD/	Root Mean Square Deviation (RMSD) analysis.
GOF RMSF/	Root Mean Square Fluctuation (RMSF) analysis.
GOF SASA/	Solvent Accessible Surface Area (SASA) analysis.
GOF Rg/	Radius of Gyration (Rg) analysis.
GOF PCA/	Principal Component Analysis (PCA) outputs.
GOF Clustering Analysis/	Conformational clustering log files and representative structures.
GOF PSN Analysis/	Protein Structural Network (PSN) analysis outputs.
The numerical MD analysis outputs are primarily provided in GROMACS XVG format, along with relevant supporting files.

4. GROMACS Analysis Commands section
contains GROMACS Analysis_Commands.pdf GROMACS refernce link: https://manual.gromacs.org/documentation/2021.1/manual-2021.1.pdf
