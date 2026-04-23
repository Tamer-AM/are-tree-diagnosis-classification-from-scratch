# Tree Diagnosis Classification

University machine learning competition project.

## Result
🏆 Tied for #1 on leaderboard

---

## Overview

The objective was to classify each tree into its diagnostic category using a real-world dataset containing mixed categorical and numerical variables.

Instead of relying on machine learning libraries such as scikit-learn, this project was intentionally built **from scratch** using NumPy and pandas to deeply understand the mechanics behind the algorithms.

---
## Built From Scratch
- KNN
- Decision Tree
- Random Forest
- Cross Validation
- Weighted Ensemble Voting

## Stack
Python, NumPy, pandas

---
## Models Implemented

### K-Nearest Neighbors (KNN)

Implemented manually including:

- Euclidean distance optimization
- Neighbor search
- Majority voting
- Cross-validation for best `k`

### Decision Tree

Implemented manually including:

- Gini impurity
- Best split search
- Recursive tree growth
- Prediction traversal

### Random Forest

Built from the custom Decision Tree implementation:

- Bootstrap-style tree ensemble
- Random feature selection
- Majority vote prediction

### Ensemble Model

Final model combined:

- KNN
- Random Forest

Using weighted voting for stronger final predictions.

---

## Repository Structure

```txt
.
├── notebook.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/tree-diagnosis-ml-from-scratch.git
cd tree-diagnosis-ml-from-scratch
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch notebook:

```bash
jupyter notebook
```

---

## Authors

Tamer Al Masri 

Alex ARGELES 

### Sorbonne Université 

---

## Note

This project was developed in a group academic competition setting and is presented here as a demonstration of practical machine learning foundations and from-scratch implementation skills.