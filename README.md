#  Apoptosis Network Analysis using Petri Nets and Machine Learning

## Project Overview
This project models and analyzes the **apoptosis (programmed cell death) network** using a **Petri Net-based approach**, combined with **machine learning techniques**.

The dataset is taken from **TCGA (The Cancer Genome Atlas)** for **Lung Adenocarcinoma (LUAD)**, including both tumor and normal samples (>500 samples).

---

##  Objectives
- Model apoptosis pathways using **Petri Nets**
- Identify **key genes and drug targets**
- Perform network analysis:
  - Minimal Cut Sets  
  - Knockout Analysis  
  - Subnet Analysis  
- Validate results using **machine learning**

---

##  Dataset
- Source: TCGA LUAD  
- Samples: >500  
- Type: Gene expression (TPM values)

### Preprocessing
1. Extract TPM values  
2. Clean and normalize data  
3. Convert continuous values into **discrete tokens** (for Petri Nets)

---

##  Project Structure
```
MAJOR PROJECT/
│
├── data_processed_data/
├── Notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_project_code.ipynb
│   ├── 03_classification_model.ipynb
│   └── 04_regression_model.ipynb
│
├── petri_net/
├── results/
├── requirements.txt
└── README.md
```

---

##  Methodology

### 1. Petri Net Modeling
- Built apoptosis network using Petri Nets  
- Converted gene expression into **tokens**  
- Simulated biological processes  

---

### 2. Network Analysis
- **Minimal Cut Sets** → critical points  
- **Knockout Analysis** → essential genes  
- **Subnet Analysis** → functional modules  

---

### 3. Machine Learning

#### Regression
- Predict **Apoptosis Index**

#### Classification
- Predict **Cancer vs Normal**

---

##  Results
- Identified important apoptosis-related genes  
- Found potential drug targets  
- Successfully performed:
  - Cancer classification  
  - Apoptosis prediction  

---

##  Setup

### Clone Repository
```bash
git clone <your-repo-link>
cd MAJOR_PROJECT
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run
```bash
jupyter notebook
```

---

##  Requirements
- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- jupyter  

---
## 🧪 Petri Net Simulation Tool

This project uses the **HOLMES Petri Net Tool** for modeling and analysis.

It is required for:
- Petri Net simulation  
- Minimal Cut Set analysis  
- Knockout analysis  
- Subnet analysis  

Download here: https://holmes-pn.pl/

---

##  Future Work
- Use deep learning  
- Extend to other cancers  
- Improve validation  

---

##  Author
Atif Khan  
Master’s in Bioinformatics