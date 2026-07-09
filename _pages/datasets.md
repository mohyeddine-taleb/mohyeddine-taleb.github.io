---
layout: archive
title: "Datasets & Scripts"
permalink: /datasets/
author_profile: true
---

{% include base_path %}

Below is a collection of computational workflows, analysis scripts, and datasets developed during my PhD research. Due to the nature of the research, some full datasets and scripts are available upon request rather than direct public download.

## Scripts & Automation

### GROMACS Membrane Bilayer & Umbrella Sampling Automation
An automated computational workflow (`setup_automation_aroma_gmx`) designed to rapidly generate and equilibrate Aroma/lipid bilayers and automatically prepare systems for Umbrella Sampling in GROMACS. This script handles topology generation, energy minimization, equilibration, and production run setup in a single automated pipeline.

**Availability:** Available upon request.  
📧 [mohyeddinetb@gmail.com](mailto:mohyeddinetb@gmail.com) | [mohyeddine.taleb@univ-reims.fr](mailto:mohyeddine.taleb@univ-reims.fr)

---

## Data Analysis Workflows

### IGMPlot Non-Covalent Interaction Analysis
Workflows for batch processing Independent Gradient Model (IGM) calculations to map and quantify non-covalent interactions (steric repulsion, van der Waals, and hydrogen bonds) between target proteins (e.g., TSPO) and various ligands.

### MD Trajectory Analysis Pipelines
Custom scripts utilizing Python (MDAnalysis) and GROMACS tools for high-throughput analysis of large-scale molecular dynamics trajectories. Automates extraction of:
- **RMSD** — Root Mean Square Deviation
- **RMSF** — Root Mean Square Fluctuation
- **Radius of Gyration**
- **PCA** — Principal Component Analysis

---

## Structural Datasets

### BcDocking Trajectories & Poses
High-confidence docking poses, scoring metrics, and molecular dynamics trajectories evaluating the interactions between BcTSPO and novel small-molecule ligands.

⚠️ *Currently under embargo pending publication.*
