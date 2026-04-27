# Computational modeling and validation of human RNA-binding proteins containing RRM domains using homology and threading approaches

## 📌 Overview
RNA-binding proteins (RBPs) play critical roles in post-transcriptional gene regulation. Among them, the RNA Recognition Motif (RRM) is one of the most abundant and functionally important domains.

In this project, I performed computational structural modeling of human RRM-containing proteins using sequence similarity-based approaches and validated the predicted structures.

---

## 🎯 Objectives
- Curate human RNA-binding proteins containing RRM domains
- Perform sequence similarity analysis using BLAST
- Predict protein structures using:
  - Homology modeling (MODELLER)
  - Threading (I-TASSER)
- Validate predicted structures using structural quality metrics

---

## ⚙️ Workflow

Dataset Collection → Sequence Analysis (BLAST+) → Model Selection  
→ Structure Prediction (MODELLER / I-TASSER Suite)  
→ Validation (PROCHECK, ProSA)

---

## 🧪 Methods

### 1. Dataset Preparation
- Retrieved RNA-binding proteins from UniProt
- Filtered proteins containing RRM domains
- Final dataset categorized into:
  - Single RRM
  - Multiple RRM
  - Combined domains

### 2. Sequence Analysis
- Tool: BLAST+
- Criteria:
  - >35% similarity → Homology modeling
  - <35% similarity → Threading

### 3. Structure Prediction

#### Homology Modeling
- Tool: MODELLER
- Used high-similarity templates

#### Threading
- Tool: I-TASSER Suite
- Used for low similarity sequences

### 4. Structure Validation
- Ramachandran Plot (PROCHECK)
- Z-score evaluation (ProSA)
- DOPE score (MODELLER)

---

## 📊 Results

- Successfully modeled structures for selected RRM-containing proteins
- Observed variation in structure quality based on sequence similarity
- Validated models showed acceptable stereochemical quality

---

## 📁 Project Structure

protein-structure-modeling-containing-rrm_domain/
│── data/
│── scripts/
│── results/
│── figures/
│── docs/
│── README.md

---

## 📷 Figures
- RRM domain structure
- Workflow diagram
- Sample modeled structures

---

## 🚀 Future Work
- Compare predicted structures with AlphaFold models
- Perform RNA-protein docking
- Identify key RNA-binding residues
- Integrate machine learning for structure quality prediction

---

## 🧑‍💻 Author
Pradeep Kumar Lohra  
M.Tech Biotechnology & Biochemical Engineering  
