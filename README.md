# Comparative Binding Analysis by Computational Methods and Quartz Crystal Microbalance: Case of hnRNPA2B1 Protein and Irinotecan Drug

This repository contains input files and results supporting the molecular docking and molecular dynamics (MD) simulation study of the hnRNPA2B1 protein in complex with irinotecan (IRT) and camptothecin (CPT).

## Initial Structures:

hnRNPA2B1_protein.pdb - Purified protein structure.

CPT.sdf, IRT.sdf - Initial ligand structures.

## Docking Preparation:

hnRNPA2B1.pdbqt, CPT.pdbqt, IRT.pdbqt - Prepared protein and ligand structures for molecular docking.

## Docking Results & Configuration:

CPT_docked_min.pdbqt, IRT_docked_min.pdbqt - Final poses of the docked ligands.

cfg.txt - Configuration parameters for the molecular docking simulation.

## Molecular Dynamics (MD) Setup:

input_IRT.gro, input_CPT.gro - Ligand structures for MD.

input_MD_hnRNPA2B1-IRT.gro, input_MD_hnRNPA2B1-CPT.gro - Final solvated systems (protein-ligand in water box with NaCl) for MD production runs.

topol_input_MD_hnRNPA2B1-IRT.top, topol_input_MD_hnRNPA2B1-CPT.top - Molecular topologies for the MD systems.

## Energetics Analysis:

FINAL_RESULTS_MMPBSA_hnRNPA2B1-CPT.dat, FINAL_RESULTS_MMPBSA_hnRNPA2B1-IRT.dat - Final MM/PBSA binding energy results.
