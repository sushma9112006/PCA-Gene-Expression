# PCA Gene Expression Analysis

## Project Overview
This project applies Principal Component Analysis (PCA) to gene expression data to study patterns between ER+ and ER− breast cancer samples.

The analysis includes:
- Loading and preprocessing high-dimensional gene expression data
- Standardizing the dataset
- Reducing dimensions using PCA
- Visualizing sample distribution and clustering
- Analyzing variance explained by principal components

---

## Objectives
- Understand differences between ER+ and ER− samples
- Reduce dimensionality of large-scale gene expression data
- Visualize biological patterns using PCA
- Identify how much variance is captured by principal components

---

## Features
- Gene expression data preprocessing
- Dataset standardization using `StandardScaler`
- PCA dimensionality reduction
- Scatter plot visualization
- Scree plot analysis
- Projection onto principal component 1 (PC1)
- Variance explained calculation

---

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset Information
The dataset contains:
- 105 samples
- 16,174 gene expression features

The analysis focuses on gene expression patterns associated with ER+ and ER− classes.

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/sushma9112006/PCA-Gene-Expression.git
```

### Open the project folder

```bash
cd PCA-Gene-Expression
```

### Start Jupyter Notebook

```bash
jupyter notebook
```

### Open the notebook

```text
PCA.ipynb
```

Run all cells sequentially.

---

## Visualizations Included

The notebook generates:
- Gene expression scatter plot
- PCA plot
- Scree plot
- PC1 projection plot

---

### PCA Plot

![PCA Plot](<img width="490" height="346" alt="image" src="https://github.com/user-attachments/assets/eb4d473d-daff-436d-8315-09024b3954c9" />
)

---

### Scree Plot

![Scree Plot](<img width="502" height="276" alt="image" src="https://github.com/user-attachments/assets/ac61f8b3-6423-4a8b-a904-847c654b59e4" />
)

---

## Results
- PCA successfully reduced the dimensionality of the dataset while preserving important biological variation.
- The PCA visualization showed visible separation patterns between ER+ and ER− samples.
- The scree plot demonstrated how variance is distributed across principal components.
---

## Conclusion
Principal Component Analysis helped simplify high-dimensional gene expression data into lower dimensions for easier visualization and interpretation. The project demonstrates how PCA can reveal meaningful biological patterns in complex datasets.

---
- Name: Jakkula Charita Sai Sushma
- Enrollment: 24114044

---
