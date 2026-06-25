# Cancer-Gene-Expression-Classifier
# Colon Cancer Gene Expression Classification Using Machine Learning

## Overview

This project uses gene expression data from the GEO dataset GSE44076 to classify colon tissue samples as either cancerous or normal.

Machine learning models were trained on gene expression profiles from healthy colon mucosa, adjacent normal tissue, and colon tumor samples.

---

## Dataset

Dataset: GSE44076

Source: Gene Expression Omnibus (GEO)

Samples:
- 98 Tumor samples
- 98 Adjacent Normal samples
- 50 Healthy Mucosa samples

Total samples: 246

Gene probes: 49,386

For binary classification:

- Normal Class = Healthy Mucosa + Adjacent Normal
- Cancer Class = Tumor

---

## Workflow

1. Load GEO gene expression dataset
2. Parse sample annotations
3. Create binary labels
4. Feature selection using variance
5. Standardization
6. PCA visualization
7. Model training
   - Logistic Regression
   - Random Forest
   - Support Vector Machine
8. Model evaluation
9. Feature importance analysis

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Results

### PCA Visualization

Cancer and normal samples formed distinct clusters, demonstrating strong biological separation based on gene expression profiles.

### Models

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 100% |
| Random Forest | 98% |
| SVM | 100% |

---

## Key Findings

- Gene expression profiles strongly distinguish colon cancer from normal tissue.
- PCA demonstrated clear class separation.
- Machine learning models achieved high classification performance.
- Several highly variable genes contributed substantially to cancer prediction.

---

## Future Work

- Differential gene expression analysis
- Deep learning approaches
- Multi-class classification
- Biological pathway enrichment analysis

---

## Author

Moazma Salahuddin
