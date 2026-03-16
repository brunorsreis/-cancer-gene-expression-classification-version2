# -cancer-gene-expression-classification-version2

# Cancer Gene Expression Analytics – Version 2

Cancer Gene Expression Analytics is an Oracle APEX application designed to explore, analyze, and visualize gene expression data related to cancer research. The platform provides interactive dashboards and visualization tools that allow users to examine patterns in tumor datasets and perform exploratory data analysis on genomic data.

This application is built using **Oracle APEX 24.2** and is connected to the **AI_HEALTHCARE schema**, enabling efficient management and visualization of biological datasets. 

---

# Version 2 Highlights

Version 2 expands the analytical capabilities of the application by adding advanced data visualizations and improved navigation for exploring cancer gene expression patterns.

New and improved features include:

* Interactive reports for exploring gene expression datasets
* Chart-based visualizations for quick analysis of biological data
* Tumor distribution insights across cancer types
* Scatter plot analysis for gene relationship exploration
* PCA (Principal Component Analysis) visualization for dimensionality reduction
* t-SNE clustering visualization to identify biological groupings in gene expression data

These features allow researchers and analysts to better understand complex genomic datasets and detect patterns across cancer types.

---

# Application Architecture

**Platform**

* Oracle APEX 24.2

**Database Schema**

* AI_HEALTHCARE

**Application ID**

* 100



The application currently includes the following major analytical views:

1. **Home**

   * Overview of the analytics platform

2. **Gene Expression Report**

   * Tabular view of gene expression data

3. **Chart Visualization**

   * Graphical analysis of gene expression patterns

4. **Tumor per Cancer Type**

   * Distribution of tumor samples across cancer categories

5. **Scatter Plot**

   * Gene correlation and pattern analysis

6. **PCA Visualization**

   * Dimensionality reduction visualization

7. **t-SNE Cluster Visualization**

   * Cluster discovery in gene expression datasets

---

# Technologies Used

* Oracle APEX
* Oracle Database
* SQL / PL-SQL
* Interactive Reports
* APEX Chart Components
* PCA and t-SNE data visualization methods

---

# Project Goals

The objective of this project is to provide a **visual analytics platform for cancer gene expression data**, enabling:

* Exploration of genomic datasets
* Identification of patterns in cancer types
* Dimensionality reduction visualization
* Data-driven insights for biomedical research

---

# Installation

1. Open **Oracle APEX App Builder**
2. Import the file:

```
f100.sql
```

3. Install into workspace connected to schema:

```
AI_HEALTHCARE
```

4. Run the application.

---

# Future Improvements

Planned enhancements include:

* Machine learning–based gene classification
* AI-assisted genomic pattern detection
* Dataset upload and preprocessing tools
* Integration with biomedical datasets such as TCGA

