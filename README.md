## Article Title: Cholesterol derivatives regulate Adenylyl cyclase 7 activity by binding CARC and CRAC motifs in the cytosolic parts

### Authors: [Radim Jaroušek], [423168@muni.cz]

### Corresponding Author:[Lukas Kubala] [kubalal@ibp.cz]

### This repository contains supplementary data, analysis scripts, and supporting files associated with the article "Cholesterol derivatives regulate Adenylyl cyclase 7 activity by binding CARC and CRAC motifs in the cytosolic parts" Here, we explore how cholesterol and its derivatives modulate Adenylyl Cyclase 7 (AC7) structure and function through computational predictions, docking studies, and sequence alignments.

Repository Structure
DeepSite -binding site prediction/
Contains input files and results from DeepSite, a binding site prediction tool. These predictions helped identify potential cholesterol and derivative binding pockets on the AC7 structure.

DiffDock - diffdock docking of cholesterol derivatives/
Results obtained from DiffDock, a diffusion-based docking method. It includes configuration files, run scripts, and output data showing how cholesterol derivatives interact with the predicted AC7 binding sites.

DockThor_Cholesterol/
Docking results using the DockThor platform. This directory holds input files, run parameters, and docking outputs to visualize and assess how cholesterol interacts with AC7 binding motifs.

Molecules - optimized structures for ligands/
A collection of optimized 3D structures of cholesterol derivatives used as ligands. These have been geometry-optimized prior to docking experiments, ensuring more accurate predictions of ligand orientation and interaction.

MSA - Multiple sequence alignment of tmAC1-AC9 R script/
Contains a script (Rmakrdown) and related files for generating and analyzing a multiple sequence alignment (MSA) of transmembrane Adenylyl Cyclases AC1 through AC9. This alignment provides comparative insights into CARC and CRAC motif conservation and variation across isoforms.

Optimized_AC7_AlphaFold/
Files generated by refining the AlphaFold-predicted structure of AC7. These optimized models served as a starting point for identifying binding sites and conducting docking simulations.

Pymol_session - pymol object with cholesterol ligands and AC7 predicted structure/
A PyMOL session file (.pse) that can be opened to visualize the AC7 structure, its cholesterol-binding sites, and docked ligand conformations. This provides an interactive 3D representation of the results.
