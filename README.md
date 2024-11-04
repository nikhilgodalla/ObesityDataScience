# Machine Learning Project Repository

This repository contains a series of Jupyter notebooks that explore various machine learning techniques, including data cleaning, feature selection, model interpretability, and automated machine learning (AutoML). Each notebook is self-contained and demonstrates key concepts in machine learning workflows.

## Table of Contents

- [Project Overview](#project-overview)
- [Notebooks Overview](#notebooks-overview)
  - [ML Data Cleaning and Feature Selection](#1-ml-data-cleaning-and-feature-selection)
  - [Model Interpretability](#2-model-interpretability)
  - [AutoML with Nikhil Godalla](#3-automl-with-nikhil-godalla)
  - [Combined Report](#4-combined-report)
- [Installation](#installation)
- [Usage](#usage)
- [License](#MIT-License)

## Project Overview

The goal of this project is to demonstrate essential machine learning techniques, from preparing data for analysis to interpreting model results. Additionally, the project explores the use of automated machine learning (AutoML) tools to simplify the process of building and tuning machine learning models.

## Notebooks Overview

### 1. ML Data Cleaning and Feature Selection
**File:** `ML-Data-Cleaning-and-Feature-Selection.ipynb`

This notebook covers the following topics:
- Handling missing values
- Feature scaling and encoding
- Feature selection techniques such as correlation analysis and recursive feature elimination (RFE)

### 2. Model Interpretability
**File:** `Model_Interpretability.ipynb`

This notebook focuses on interpreting machine learning models:
- Visualizing feature importance
- Using SHAP (SHapley Additive exPlanations) values to explain model predictions
- Exploring partial dependence plots (PDPs) for interpretability

### 3. AutoML with Nikhil Godalla
**File:** `Auto_ML_NikhilGodalla.ipynb`

This notebook introduces automated machine learning (AutoML) techniques:
- Overview of AutoML concepts
- Implementation using AutoML tools like TPOT or Auto-sklearn
- Comparing AutoML-generated models with manually tuned models

### 4. Combined Report
**File:** `Combine_Report.ipynb`

This notebook provides a comprehensive summary of the project:
- Consolidates insights from the other notebooks
- Presents a comparative analysis of different approaches used in the project
- Summarizes key findings and conclusions

## Installation

To run these notebooks locally, follow these steps:

1. Clone this repository:
   ```bash
    git clone https://github.com/nikhilgodalla/ObesityDataScience.git
    cd ObesityDataScience
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

Alternatively, you can run the notebooks in any environment that supports Jupyter, such as Google Colab.

## Usage

Each notebook can be run independently. However, it is recommended to follow this order for a logical flow:

1. Start with **ML Data Cleaning and Feature Selection** to prepare your dataset.
2. Use **Model Interpretability** after training your model to understand its behavior.
3. Explore **AutoML with Nikhil Godalla** for an automated approach to model building.
4. Review the **Combined Report** for a summary of all findings.

## MIT License

Copyright (c) 2024 nikhilgodalla

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
