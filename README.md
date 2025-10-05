# High Fat Diet Induces Sex-Specific Differential Gene Expression

**Authors:** Júlia Jiménez, Ainhoa López, Alba Peña

---

## 📖 Overview

This project investigates how a **high-fat diet (HFD)** influences gene expression in a **sex-specific** manner using transcriptomic data.  
The analysis includes PCA, t-SNE, and UMAP visualizations to explore patterns and variance in gene expression.

**Analysis Steps:**

1. Introduction to the dataset  
2. PCA (Principal Component Analysis)  
3. t-SNE (t-distributed Stochastic Neighbor Embedding)  
4. UMAP (Uniform Manifold Approximation and Projection)  
5. Conclusions

---

## 🧬 Introduction to the Data

**Dataset Structure:**  
- **Sample Metadata:** Biological and experimental design information.  
- **Gene Expression Matrix:** Contains samples and genes for analysis.

**Key Points:**  
- Metadata includes sex and body part.  
- Gene expression matrix used for dimensionality reduction and clustering.

---

## 📊 PCA (Principal Component Analysis)

- PCA reveals **significant factors** affecting gene expression.  
- ANOVA tests performed to identify significant vs. non-significant factors.  

**Findings:**  
- Sex and body part are **strong determinants** of gene expression variance.  
- Clear separation along PC1 and PC2 indicates strong interactions between sex and tissue type.  
- Non-significant factors show no clear clustering in PCA plots.

---

## 🔹 t-SNE (t-distributed Stochastic Neighbor Embedding)

- Explored **batch effects** in the dataset.  
- t-SNE confirms **consistent clustering by sex and tissue** with no major batch biases.

---

## 🔹 UMAP (Uniform Manifold Approximation and Projection)

- UMAP visualization highlights **distinct clustering by sex**.  
- No clear clustering by diet type (HFD vs. regular), suggesting diet is a minor source of variance.

---

## ✅ Conclusions

- **Sex and body part** drive the majority of gene expression variation.  
- Interaction between sex and body part explains PC1 variance.  
- **High-fat diet** has minimal impact on global gene expression patterns.  
- Normalization successfully removes biases and highlights biological patterns.  
- Data shows no outliers or batch effects; results are reproducible.  
- **Dimensionality reduction methods (PCA, t-SNE, UMAP)** consistently show clustering by sex and body part.  
- Drosophila remains a valuable model organism for studying obesity and metabolic diseases.

---

## 📂 Analysis Pipeline

1. Load sample metadata and gene expression matrix  
2. Perform PCA to identify significant factors  
3. Conduct t-SNE for batch effect exploration  
4. Apply UMAP for clustering by sex and diet  
5. Compare results and draw biological conclusions

---

