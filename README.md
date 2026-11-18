# Seaborn for Data Science

A structured, practice-driven curriculum for statistical visualization in Python with Seaborn. It covers the plots used in **exploratory data analysis (EDA)** before modeling: distributions, category comparisons, correlations and multi-variable relationships.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-statistical%20plots-4c72b0)
![Jupyter](https://img.shields.io/badge/Jupyter-notebooks-F37626)

## Overview

Each module has an **introduction notebook** (concepts, syntax, parameters) and a **practice notebook** (hands-on tasks and conceptual questions). Later modules include a mini-EDA task on a student performance dataset.

Companion repo: [matplotlib-for-datascience](https://github.com/ibrahimkhanmohammad/matplotlib-for-datascience)

## Curriculum

| Module | Topic | Key concepts |
|---|---|---|
| 01 | Introduction & Fundamentals | Seaborn vs Matplotlib, themes, built-in datasets, first plot |
| 02 | Scatter Plots | `scatterplot`, relationships between numeric variables, style and size |
| 03 | Line Plots | `lineplot`, trends, parameters |
| 04 | Histograms | `histplot`, bins, `kde=True` |
| 05 | KDE Plots | `kdeplot`, histogram vs KDE |
| 06 | Box Plots | Five-number summary, outliers, parameters |
| 07 | Bar Plots | Aggregation, `estimator`, `errorbar`, bar plot vs count plot |
| 08 | Count Plots | Category frequencies, `hue`, `order`, percentages |
| 09 | Correlation & Heatmaps | Pearson correlation, correlation matrix, `heatmap`, `vmin/vmax`, `cbar`, `square`, annotations |
| 10 | Pair Plots | `pairplot`, `hue`, `kind`, KDE diagonal, corner plots |

## Why this matters for ML

| Plot | Use in the ML workflow |
|---|---|
| Histogram / KDE | Check feature distributions and skew before scaling or transforming |
| Box plot | Detect outliers |
| Count plot | Check class balance in classification targets |
| Correlation heatmap | Spot multicollinearity and feature-target relationships |
| Pair plot | Scan all feature relationships at once |

## Repository structure

```
seaborn-for-datascience/
├── 01_introduction_fundamentals/
├── 02_scatterplots/
├── ...
├── 10_pairplots/
│   ├── 01_introduction.ipynb    # concepts + examples
│   └── 02_practise.ipynb        # tasks + conceptual questions
├── requirements.txt
└── README.md
```

## Setup

```bash
git clone https://github.com/ibrahimkhanmohammad/seaborn-for-datascience.git
cd seaborn-for-datascience
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

**Dependencies:** NumPy, Pandas, Matplotlib, Seaborn, Jupyter, ipykernel

## Author

**Ibrahim Khan Mohammad**, Computer Science student specializing in Data Science and AI/ML.

[GitHub](https://github.com/ibrahimkhanmohammad) · [LinkedIn](https://www.linkedin.com/in/ibrahimkhanmohammad/)
