# Bioinformatics & Computational Biology Notebooks

This directory contains reproducible Jupyter notebooks demonstrating computational workflows developed by **Mohyeddine Taleb**, spanning sequence bioinformatics, molecular dynamics / docking automation, cheminformatics, and deep learning.

---

## 📚 Available Notebooks

### 1. 🧬 [TSPO Conservation & Polymorphism Analysis](TSPO_conservation_analysis.ipynb)
* **Topics:** Sequence Alignment, Biopython, NCBI Entrez, Heatmap Visualization, SNP & Polymorphism Impact.
* **Biological Context:** Cross-species analysis of Translocator Protein (TSPO) across *Homo sapiens*, *Rattus norvegicus*, *Mus musculus*, and *Bacillus cereus*. Evaluates the clinical impact of the **Ala147Thr (rs6971)** polymorphism on 2nd- vs. 3rd-generation PET radioligand binding.
* **NGS Relevance:** Demonstrates core sequence alignment, conservation scoring, and functional variant annotation principles.

### 2. 🧪 [Graph Neural Networks & Machine Learning for Molecular Docking](GNN_Molecular_Docking_ML.ipynb)
* **Topics:** PyTorch Geometric (PyG), RDKit, Graph Convolutional Networks (GCN), AutoDock4.2 / Vina Automation, Web Dashboard Architecture.
* **Computational Context:** Converts small molecule ligands into molecular graphs (atoms as node features, bonds as edges) to train a deep GNN model for binding free energy ($\Delta G$) prediction.
* **Relevance to Structural Dynamics & IDPs:** Integrates ensemble docking across MD conformational clusters with fast GNN surrogate screening — an ideal approach for flexible and intrinsically disordered protein interactions.

---

## 🛠️ Installation & Requirements

To run these notebooks locally, install the necessary dependencies:

```bash
# Core data science & plotting
pip install numpy pandas matplotlib seaborn scikit-learn

# Bioinformatics & Cheminformatics
pip install biopython rdkit

# Deep Learning & PyTorch Geometric
pip install torch torchvision torchaudio
pip install torch_geometric
```

---

## 👤 Author
**Mohyeddine Taleb**  
PhD in Biology, Chemistry, Health  
ICMR – CNRS UMR 7312, University of Reims Champagne-Ardenne  
Website: [mohyeddine-taleb.github.io](https://mohyeddine-taleb.github.io) | [GitHub](https://github.com/mohyeddine-taleb)
