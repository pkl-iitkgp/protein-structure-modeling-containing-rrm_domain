# 🧬 Model Validation and Structural Quality Assessment

This section presents the structural validation of predicted protein models generated using **MODELLER** and **I-TASSER**. The goal is to evaluate and compare the quality of predicted structures using standard validation metrics.

---

## 📊 Validation Metrics Used

### 1. Ramachandran Plot Analysis (PROCHECK)

The Ramachandran plot evaluates backbone dihedral angles (ϕ and ψ) of amino acid residues in protein structures.
* It indicates whether the protein adopts **sterically allowed conformations**
* A high percentage of residues in the **most favored regions** reflects good structural quality
* Presence of residues in **disallowed regions** suggests structural errors or instability

**Interpretation:**

* ✅ >90% in most favored → Excellent model
* ✅ 80–90% → Acceptable model
* ⚠️ <80% → Needs improvement

---

### 2. ProSA Z-score

The ProSA Z-score evaluates overall model quality by comparing it to experimentally determined structures.

**Why it matters:**

* Indicates whether the predicted structure falls within the range of native proteins
* Helps detect **incorrect folds or unrealistic models**

**Interpretation:**

* More **negative Z-score** → Better structural quality
* Z-score should fall within the range of known protein structures of similar size

---

## 📁 Files Included

* `modeller_validation_results.csv` → Validation results for MODELLER models
* `itasser_validation_results.csv` → Validation results for I-TASSER models

---

## 📈 Comparative Analysis

To systematically compare both modelling approaches, the following parameters were analyzed:

### ✔️ 1. Most Favored Regions (%)

* Represents structural reliability
* Higher values indicate better folding accuracy

### ✔️ 2. Disallowed Regions (%)

* Indicates structural inconsistencies
* Lower values are desirable

### ✔️ 3. ProSA Z-score Distribution

* Evaluates overall structural realism
* More negative values indicate better models

## 🧑‍💻 Author Note

This analysis is part of an M.Tech project focused on structural modelling of human RNA-binding proteins containing RRM domains. The goal is to combine computational modelling with rigorous validation to ensure biologically meaningful predictions.

---

