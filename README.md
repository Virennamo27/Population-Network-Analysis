# Population-Network-Analysis

A data science project analyzing global population trends using Graph Theory, clustering, and machine learning.

## Overview

- Built demographic networks of countries using centrality measures:
  - Degree Centrality
  - Betweenness Centrality
  - Closeness Centrality
  - Eigenvector Centrality
- Used K-Means clustering for pattern detection across regions.
- Applied predictive models:
  - Random Forest
  - Logistic Regression
  - Support Vector Machine (SVM)
- Derived insights on urbanization, population growth, and policy implications.

## Skills & Tools Used

- Python
- NetworkX
- Pandas & NumPy
- scikit-learn
- Matplotlib & Seaborn

## Output

Visualizations of central countries in the population network, clustered population regions, and predictions of population-related factors.

## Structure
(For looking at the structure, use README.md file.)

Population-Network-Analysis/
│
├── data/                   # Raw and cleaned datasets
│   └── population_data.csv
│
├── notebooks/              # Jupyter notebooks for EDA, modeling, etc.
│   ├── 01_exploratory_analysis.ipynb
│   └── 02_modeling_and_results.ipynb
│
├── src/                    # Python scripts (modular, reusable code)
│   ├── __init__.py
│   ├── data_loader.py          # Load and preprocess data
│   ├── network_analysis.py     # Graph theory & centrality
│   ├── clustering.py           # K-means clustering logic
│   └── prediction_models.py    # ML model training and evaluation
│
├── visualizations/         # Charts, graphs, and plots
│   ├── centrality_plots.png
│   └── cluster_map.png
│
├── README.md               # Project overview and instructions
├── requirements.txt        # List of required Python packages
└── .gitignore              # Ignore unnecessary files (e.g., .ipynb_checkpoints)


