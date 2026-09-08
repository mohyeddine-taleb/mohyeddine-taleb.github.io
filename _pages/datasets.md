---
layout: archive
title: "Datasets, Notebooks & Workflows"
permalink: /datasets/
author_profile: true
---

Below is a collection of computational workflows, interactive Jupyter notebooks, analysis pipelines, and structural datasets developed during my research. To maintain data integrity prior to publication, some raw trajectories and datasets are available upon request, while open-source notebooks and scripts can be explored directly on GitHub.

---

## 🧬 Interactive Jupyter Notebooks & AI Pipelines

### 1. TSPO Cross-Species Conservation & Polymorphism Analysis
**Description:** Automated sequence analysis pipeline using **Biopython** and NCBI Entrez to fetch cross-species TSPO sequences (*Homo sapiens*, *Rattus norvegicus*, *Mus musculus*, *Bacillus cereus*), compute pairwise global alignments, generate percent identity heatmaps, and map residue conservation across the 5 transmembrane domains. Specifically highlights the **Ala147Thr polymorphism (rs6971)** in human TSPO and its impact on PET radioligand binding.  
🔗 **Explore Notebook on GitHub:** [`TSPO_conservation_analysis.ipynb`](https://github.com/mohyeddine-taleb/mohyeddine-taleb.github.io/blob/main/notebooks/TSPO_conservation_analysis.ipynb)

### 2. Graph Neural Networks (GNN) & Deep Learning for Molecular Docking
**Description:** End-to-end deep learning pipeline combining **RDKit** and **PyTorch Geometric (PyG)** to predict protein-ligand binding free energies directly from molecular graph topologies. Trained and evaluated on systematic docking data generated during my PhD research across all available TSPO structural states (**BcTSPO**, **mTSPO**, **RsTSPO**, and **MD conformational clusters C0–C6**). Bridges high-throughput ensemble docking with deep learning surrogate screening.  
🔗 **Explore Notebook on GitHub:** [`GNN_Molecular_Docking_ML.ipynb`](https://github.com/mohyeddine-taleb/mohyeddine-taleb.github.io/blob/main/notebooks/GNN_Molecular_Docking_ML.ipynb)

---

## 💻 Molecular Modeling & Automation Pipelines

### Automated High-Throughput Molecular Docking
**Description:** Automated Python workflows for batch AutoGrid map calculation and AutoDock 4.2 / AutoDock Vina genetic algorithm runs across multi-replicate and multi-target conformational libraries.

### Molecular Docking Web Dashboard Architecture
**Description:** Web application framework integrating 3D molecular visualization (NGL/3Dmol.js), receptor/ligand preparation routines, interactive grid box parameterization, and automated backend docking execution with real-time scoring.

### GROMACS Umbrella Sampling Automation
**Description:** Developed computational pipeline (`setup_automation_aroma_gmx`) designed to automate input file generation (umbrella sampling, bilayer equilibration), topology setup, energy minimization, and equilibration for lipid/aroma bilayers in GROMACS.

### High-Throughput MD Trajectory Analysis
**Description:** Custom analysis pipelines utilizing Python (MDAnalysis) and GROMACS tools to automate the extraction of key structural metrics:
* Root-Mean-Square Deviation (RMSD) & Fluctuation (RMSF)
* Radius of Gyration ($R_g$)
* Principal Component Analysis (PCA) for protein conformational dynamics
* Conformational clustering using CONAN tools

### Dynamic IGMPlot Non-Covalent Interaction Analysis
**Description:** Adaptation of the Independent Gradient Model (IGM) approach to analyze non-covalent interactions (van der Waals, hydrogen bonds, and steric repulsion) across MD simulation trajectories rather than static structures.

---

## 📦 Structural Biology Datasets

### BcTSPO Docking Poses & MD Trajectories
**Description:** A curated dataset containing high-confidence docking poses, scoring metrics, and explicit-solvent molecular dynamics trajectories evaluating the interaction between TSPO and novel small-molecule ligands.

---

## 📬 Contact for Sharing & Collaboration
If you are interested in using these workflows, reproducing notebooks, or discussing collaborative projects:  
📧 [mohyeddinetb@gmail.com](mailto:mohyeddinetb@gmail.com) \| [mohyeddine.taleb@univ-reims.fr](mailto:mohyeddine.taleb@univ-reims.fr)
