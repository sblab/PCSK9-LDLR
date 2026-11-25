README DATA DEPOSITION: MODELED STRUCTURES, MOLECULAR DYNAMICS
SIMULATIONS AND PROTEIN STRUCTURAL NETWORK ANALYSIS

Project Computational characterization of loss-of-function (LOF) and
gain-of-function (GOF) variants and their effects on protein structure,
dynamics, and interaction networks.

This data package contains modeled structures of the selected LOF and
GOF variants, molecular dynamics simulation outputs, representative
conformational structures, analysis files, and protein structural
network (PSN) data.

1.  MODELED STRUCTURES Folder: Modeled_Structures/

Contains the modeled three-dimensional structures of the wild-type 3M0C (WT)
protein and the selected LOF and GOF variants used as starting
structures for molecular dynamics simulations.


The files contain the modeled protein structures prepared for subsequent
simulation.

2.  MOLECULAR DYNAMICS SIMULATION STRUCTURES Folder: MDS 500ns structures/

Contains structural trajectory data generated from the 500 ns molecular
dynamics (MD) simulations of the WT protein and selected LOF and GOF
variants.

3.  MD ANALYSIS OUTPUT FILES Folder: MDS_Analysis_XVG/

Contains numerical output files in GROMACS XVG format generated during
the analysis of the MD trajectories.

Depending on the analyses performed, files may include: -
Root-mean-square deviation (RMSD) - Root-mean-square fluctuation
(RMSF) - Radius of gyration (Rg) - Solvent-accessible surface area
(SASA) - Hydrogen-bond analysis - Other trajectory-derived measurements

XVG files generally contain numerical data together with plot or axis
metadata in comment lines. The axis labels and units are recorded in
each file where available. The specific analysis represented by each
file should be identifiable from its filename.

4.  CLUSTERING LOG FILES Folder: Clustering_Logs/

Contains log and supporting output files generated during conformational
clustering of the MD trajectories.

These files provide information about the clustering procedure and its
output, such as the number of clusters, cluster populations,
representative frames, and associated RMSD values, where reported.

5.  REPRESENTATIVE STRUCTURES Folder: Representative_Structures/

Contains representative protein structures selected from the MD
simulations and/or conformational clusters for the WT, and GOF
variants.

These structures are provided for visualization and comparative
structural interpretation. 

6.  PROTEIN STRUCTURAL NETWORK (PSN) DATA Folder: 06_PSN_Data/

Contains the input structures and output data generated for protein
structural network analysis of the WT, LOF, and GOF variants.

Where available, this folder includes: - PDB structures used as PSN
input - PSN output and log files - Residue interaction or edge lists -
Network files used for visualization or analysis (for example,
Cytoscape-compatible files) - Comparative network data for WT, LOF, and
GOF variants

The PSN data are intended to support comparison of residue-level
connectivity and communication networks among the studied variants. The
software/server, version, analysis settings, and relevant network
definitions should be documented in the associated methods or metadata.


    SOFTWARE AND METHODS The simulations and analyses were performed
    using the software and protocols described in the associated
    manuscript. Record the exact software versions, force field,
    simulation parameters, analysis settings, and PSN tool/version used.
    Do not rely on this README alone as a substitute for the detailed
    methods.


This README describes the organization and general contents of the
deposited data package. The exact contents are determined by the files
included in each folder.
