---
layout: archive
title: "Datasets & Scripts"
permalink: /datasets/
author_profile: true
---

Below is a collection of computational workflows, analysis pipelines, and structural datasets developed or adapted during my research. To maintain data integrity prior to publication, some datasets and scripts are available upon request rather than direct download.

## Automation Scripts & Pipelines

### GROMACS Umbrella Sampling Workflow
**Description:** Developed computational pipeline (`setup_automation_aroma_gmx`) designed to automate input file generation (umbrella sampling, bilayer equilibration ...), topology setup, energy minimization, and equilibration for lipid/aroma bilayers. It streamlines the preparation of system windows for high-throughput MD simulation using GROMACS.

### High-Throughput MD Trajectory Analysis
**Description:** Custom analysis pipelines utilizing Python (MDAnalysis) and GROMACS tools to automate the extraction of key structural metrics from large-scale molecular dynamics trajectories.

**Key Metrics Covered:**
* Root-Mean-Square Deviation (RMSD) & Fluctuation (RMSF)
* Radius of Gyration (R_g)
* Principal Component Analysis (PCA) for protein conformational dynamics
* Clustering using CONAN tools

## Advanced Trajectory Analysis Workflows

### Dynamic IGMPlot Interaction Analysis
**Description:** Adaptation of the Independent Gradient Model (IGM) approach to analyze non-covalent interactions (van der Waals, hydrogen bonds, and steric repulsion) across MD simulation trajectories rather than just static structures. This workflow allows for the tracking of interaction density variations and stability over simulation time.

### MMPBSA analysis
**Description:** Approach to analyze non-covalent interactions using GROMACS output to analyze interaction between protein and ligand over time.

## Structural Biology Datasets

### BcTSPO Docking Poses & MD Trajectories
**Description:** A curated dataset containing high-confidence docking poses, scoring metrics, and explicit-solvent molecular dynamics trajectories evaluating the interaction between protein and novel small-molecule ligands.

---

## Contact for Sharing & Collaboration
If you are interested in using these workflows or discussing the datasets, feel free to reach out:  
📧 [mohyeddinetb@gmail.com](mailto:mohyeddinetb@gmail.com) \| [mohyeddine.taleb@univ-reims.fr](mailto:mohyeddine.taleb@univ-reims.fr)
