# 📘 ML Models from Scratch & Notebooks

This repository contains my personal notes, Jupyter notebooks, and resources for learning **Machine Learning (ML)** step by step.  
I’m documenting models, metrics, and concepts as I learn and experiment.

---

## 📂 Repository Structure
```
.
├── data/                                    # datasets
│   └── placement.csv
├── requirements.txt                         # python libraries needed
├── multiple_linear_regression/              # for multi-variable regression
│   ├── multiple_linear_sklearn.ipynb        # implementation with sklearn
│   └── multiple_linear_scratch.ipynb        # built from scratch
│   └── Multiple_linear_regression_notes.pdf # theory
│
├── gradient-descent/                        # GD stuff
│   ├── gradient_descent.ipynb               # basic concept
│   ├── gd_regressor.ipynb                   # full model using GD
│   ├── Batch_learning.ipynb
│   └── Gradient_descent_notes.pdf           # notes
│
├── simple_linear_regression/                # simple regression (1 variable)
│   ├── simle_linear_regression.ipynb        # from scratch version
│   ├── simple_linear_regreesion_sklearn.ipynb # sklearn version
│   └── Simple_linear_regression.pdf         # notes for simple linear reg
│
├── regression_metrics                       # for model evaluation
│   ├── regression_metrics_rmse.ipynb        # notebook for calculating scores like R2, MAE, etc.
│   └── Regression_metrics.pdf
│
├── README.md                                # project overview
└── ml-env/                                  # python virtual env
```
---

## 🚀 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd ml-models-scratch-notebooks
   ```
2.	Create a virtual environment
  ```bash
   python3 -m venv ml-env
  source ml-env/bin/activate   # For macOS/Linux
  ml-env\Scripts\activate      # For Windows
```
3.	Install dependencies
   ```bash
      pip install -r requirements.txt
   ```
4. Run Jupyter Notebook

## 📒 Contents
- **Simple Linear Regression**
  - Implementation from scratch
  - Using scikit-learn
  - PDF notes
- **Multiple Linear Regression**
  - scikit-learn implementation
- **Regression Metrics**
  - RMSE explained with notebook + notes
- **Data**
  - Placement dataset for experiments

---

## 📌 Notes
- The folder `ml-env/` is just my local virtual environment. You don’t need it if you recreate your own environment.
- PDFs are scans of my handwritten notes for quick reference.

---

## 🎯 Goal
To build a structured, easy-to-follow learning path of ML concepts with both **code implementations** and **notes** for revision.

