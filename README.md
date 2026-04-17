# 🏠 Housing Price Analysis in Reading, UK

<p align="center">
  <b>Data-Driven Insights into Property Prices Using Regression & Machine Learning</b>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python"></a>
  <a href="#"><img src="https://img.shields.io/badge/Pandas-Data%20Wrangling-yellow?style=for-the-badge&logo=pandas"></a>
  <a href="#"><img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn"></a>
  <a href="#"><img src="https://img.shields.io/badge/Statsmodels-Regression-green?style=for-the-badge"></a>
  <a href="#"><img src="https://img.shields.io/badge/Seaborn-Visualization-purple?style=for-the-badge"></a>
</p>

---

##  Overview

This project explores how **building characteristics and energy efficiency** impact housing prices in Reading, UK.

Using **statistical modelling and machine learning**, the analysis identifies key drivers of property value and evaluates model performance.

📊 Dataset:  **69,656 property records from Land Registry and EPC data**
📍 Location: Reading, United Kingdom  

---

##  Objectives

- Analyse housing price trends over time  
- Identify key factors influencing property prices  
- Build and evaluate regression models  
- Compare statistical vs machine learning approaches  
- Generate actionable insights for stakeholders  

---

##  Key Insights

✔️ **Property size is the strongest predictor of price**  
✔️ **More rooms → higher property value**  
✔️ **Potential energy efficiency impacts price (not current rating)**  
✔️ **Leasehold properties tend to be cheaper**  
✔️ **Energy efficiency alone has limited direct influence**

 Model explains **~24% of price variation after transformation**  

---

##  Dataset Features

| Feature | Description |
|--------|------------|
| `price` | Property sale price |
| `tfarea` | Total floor area |
| `numberrooms` | Number of rooms |
| `CEE` | Current energy efficiency |
| `PEE` | Potential energy efficiency |
| `duration` | Leasehold / Freehold |

---

##  Tech Stack

| Category | Tools |
|---------|------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Statistics | Statsmodels |
| Machine Learning | Scikit-learn |
| Notebook | Jupyter |

---

## Methodology

### 1. Data Preparation
- Cleaned missing values & outliers  
- Encoded categorical variables  
- Removed unrealistic price values  

### 2. Exploratory Data Analysis
- Scatter plots & histograms  
- Trend analysis over time  
- Correlation matrix  

### 3. Statistical Modelling
- Multiple Linear Regression (OLS)  
- Multicollinearity check using VIF  
- Log transformation for stability  

### 4. Machine Learning
- Random Forest Regressor  
- Feature importance analysis  

---

##  Model Performance

| Model | R² | RMSE | Verdict |
|------|----|------|--------|
| OLS Regression | ~0.24 | Lower |  Best |
| Random Forest | ~0.15 | Higher |  Weaker |

Thus, OLS outperformed Random Forest, showing **linear relationships dominate the data** 

---

##  Visual Findings

- Strong **positive relationship** between:
  - Floor area and price  
  - Number of rooms and price  

- Weak relationship:
  - Energy efficiency vs price  

---

##  Limitations

- Model explains only a part of price variation  
- Missing key variables:
  - Location quality  
  - Economic conditions  
  - Neighbourhood features  

- Residual analysis shows:
  - Non-normal distribution  
  - Heteroscedasticity  

---

## 3. Project Structure

    housing-price-analysis-reading/
    │
    ├── notebooks/
    │   └── DSSS_CourseWork.ipynb
    │
    ├── report/
    │   └── DSSS_CourseWork.pdf
    │
    ├── data/
    │   └── (external dataset)
    │
    └── README.md

---

##  How to Run
1. Clone the repository.  
2. Open the notebook `notebooks/DSSS_CourseWork.ipynb` in Jupyter.  
3. Run all cells from top to bottom.  
4. Review the visualisations and model outputs.  
5. Refer to the project report `(CourseWork.pdf)` for detailed insights.
