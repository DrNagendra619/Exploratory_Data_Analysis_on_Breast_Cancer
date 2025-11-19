# Exploratory_Data_Analysis_on_Breast_Cancer
Exploratory_Data_Analysis_on_Breast_Cancer
# 🔬 Exploratory Data Analysis (EDA) on Breast Cancer Diagnostics

This repository contains a **Jupyter Notebook** pipeline dedicated to performing a thorough **Exploratory Data Analysis (EDA)** on the **Wisconsin Breast Cancer Diagnostic Dataset**.

The primary goal is to understand the underlying structure, distributions, and relationships within the dataset's features, providing a foundational understanding necessary for subsequent machine learning model development.

---

## 🚀 Key Features

* **Data Loading & Inspection:** Loads the built-in dataset from `scikit-learn` and performs initial checks on structure, data types, and missing values.
* **Univariate Analysis:** Visualizes the distribution of individual features (e.g., radius, texture, perimeter) using histograms and density plots.
* **Bivariate Analysis:** Analyzes the relationship between pairs of features, particularly focusing on correlation.
* **Target Variable Analysis:** Visualizes the distribution of the target variable (Malignant vs. Benign) to check for class balance.
* **Correlation Analysis:** Generates a comprehensive **Correlation Heatmap** to visualize the linear relationships among all features, aiding in feature selection and redundancy identification.
* **Diagnostic Visualization:** Creates plots (likely Scatter Plots or Box Plots) that show how individual features separate the two diagnostic classes (Malignant/Benign).

---

## 🔬 Analysis Overview

| Component | Method / Tool | Purpose |
| :--- | :--- | :--- |
| **Dataset** | Wisconsin Breast Cancer Diagnostic Dataset | Features computed from digitized images of fine needle aspirates (FNAs) of breast masses. |
| **Analysis Focus** | Data Distribution, Correlation, Class Separation | Gaining insight into the data properties before modeling. |
| **Visualization** | Histograms, Scatter Plots, Heatmaps | Graphical representation of data statistics and feature relationships. |

---

## 🛠️ Prerequisites and Setup

### 📦 Data Requirement

The notebook uses the **built-in** Wisconsin Breast Cancer dataset available directly via the `scikit-learn` library, meaning no external file download is required.

### 🖥️ Requirements

This pipeline requires a Python environment with the following libraries installed:

* `pandas`
* `numpy`
* `matplotlib.pyplot`
* `seaborn`
* `scikit-learn` (sklearn.datasets)

### ⚙️ Execution

1.  **Download** the `Exploratory_Data_Analysis_on_Breast_Cancer.ipynb` file.
2.  Open and run the notebook in a Jupyter environment (e.g., JupyterLab or Google Colab) by executing all cells sequentially.

---

## 📊 Expected Output

The notebook's output is focused on visual and statistical summaries:

* **Console Output:** Descriptive statistics (`.describe()`), data structure (`.info()`), and correlation values.
* **Visualizations:** A series of informative plots, primarily including the **Correlation Heatmap** and plots showing feature distributions split by the `diagnosis` column.
