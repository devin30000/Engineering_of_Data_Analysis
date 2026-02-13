# Engineering of Data Analysis

This repository contains two notebooks that focus on practical aspects of data analysis and data engineering:  
Performance benchmarking of data processing tools (such as Pandas, pyspark and cuDF), and the application and impact of data anonymization on  machine learning models.

---

## Contents

- `data_processing_performance_comparison.ipynb` — Performance comparison of different data processing backends
- `computation_and_anonymity.ipynb` — Data anonymization techniques and their impact on model performance

---

## Notebook 1: Data Processing Performance Comparison
**File:** `data_processing_performance_comparison.ipynb`

**Goal:** Analyze how the performance of data analysis pipelines changes depending on the underlying data processing tools.

**Focus:**
- Comparing execution performance across different backends:
  - pandas
  - pandas SQL-style APIs
  - cuDF (GPU-accelerated DataFrames)

**What’s inside:**
- Equivalent data transformations implemented with different APIs
- Runtime measurements and performance comparisons
- Discussion of trade-offs between readability, flexibility, parallelization and performance
- Considerations for CPU vs GPU-based data processing

**Skills demonstrated:**
- Performance-oriented data engineering
- Writing backend-agnostic data transformations
- Benchmarking and interpreting runtime results
- Practical experience with modern Python data tooling

---

## Notebook 2: Computation and Anonymity
**File:** `computation_and_anonymity.ipynb`

**Goal:** Demonstrate how different data anonymization strategies affect downstream machine learning performance.

**Focus:**
- Applying multiple anonymization techniques to the same dataset
- Measuring the utility loss introduced by anonymization

**Models used for evaluation:**
- Linear Regression (baseline, interpretable model)
- Random Forest Regression (non-linear, more robust model)

**What’s inside:**
- Anonymized vs original data comparisons
- Model performance evaluation using R², MSE, and RMSE
- Analysis of privacy–utility trade-offs
- Discussion of when anonymization significantly impacts predictive quality

**Skills demonstrated:**
- Privacy-aware data analysis
- Experimental ML evaluation and model comparison
- Interpreting the impact of data transformations on model performance

---

## Tech Stack

- Python
- NumPy
- pandas
- scikit-learn
- matplotlib
- seaborn
- sklearn 
- spark-SQL
- anonymity-api
- cuDF (for GPU-based data processing)

---

## How to Run

1. Create a Python environment and install required dependencies.
2. Open the notebooks in Jupyter or VS Code.
3. Run notebooks top-down.

Note: GPU-based examples require a CUDA-capable environment to run cuDF.

---

## What this repository demonstrates

- Performance trade-offs between different data processing backends
- Practical benchmarking and engineering-focused analysis
- The impact of data anonymization on machine learning model quality
- Clean, reproducible analytical workflows


## Authors

- Devin Mavric
- Moritz Müller