Linear Regression Analysis

This project contains a Jupyter Notebook that applies **linear regression** analysis to the **CASIA-M3 dataset**

## 📊 Project Goals
- Perform regression analysis on CASIA-M3 expression data
- Identify correlations between expressions and quantified labels
- Visualize prediction performance and model diagnostics

## 📁 Dataset Description

The **CASIA-M3 dataset** includes facial expression recordings from multiple subjects, typically categorized by emotional class or response. For this analysis, expression features are either extracted beforehand or numerically encoded from the dataset.

## 🔍 Notebook Highlights

- **Data Preparation**: Load and clean CSV or structured data files
- **Feature Selection**: Choose expression-based features for regression
- **Model Training**: Use `scikit-learn`'s `LinearRegression` model
- **Evaluation Metrics**: MSE, MAE, R² Score
- **Visualization**: Scatter plots, residuals, and actual vs. predicted graphs

## 📈 Tools Used

- Python 3
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 🚀 How to Use

1. Ensure the CASIA-M3 data is available in `.csv` or compatible format
2. Open `casia_fernandez_m3_linear_regression.ipynb`
3. Run all cells to load data, train the model, and visualize results

## 📌 Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🧠 Insights
This notebook provides insight into the linear relationships between facial expression features and assigned scores. Useful for:
- Building baselines for regression-based emotion recognition
- Verifying feature relevance before deep model development

## 📄 License
This notebook is for educational and research use. Use of the CASIA-M3 dataset must comply with its respective license.

---

**Author:** Axle Casia, Joseph Fernandez
**Last Updated:** 2025
