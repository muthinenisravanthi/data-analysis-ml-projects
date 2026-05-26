# 📊 Data Analysis & ML Projects

> A collection of data analysis and machine learning projects using Python — covering exploratory data analysis (EDA), data visualization, and predictive modelling.

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&logo=python)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-1.5-150458?style=flat-square&logo=pandas)](https://pandas.pydata.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2-F7931E?style=flat-square&logo=scikit-learn)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter)](https://jupyter.org)

---

## 📁 Projects

### 1. 🎬 Netflix Content Analysis (`netflix_analysis.ipynb`)

**Goal:** Explore Netflix's content library to uncover trends in content type, release patterns, top genres, and country distributions.

**Key Findings:**
- Movies make up ~70% of Netflix content vs. TV Shows (~30%)
- Content additions peaked significantly post-2016 with rapid global expansion
- USA, India, and UK are the top content-producing countries
- Dramas and International Movies dominate genre distribution

**Techniques Used:**
- Data cleaning: handling nulls, parsing date strings, splitting multi-value columns
- Groupby aggregations for trend analysis
- Visualizations: bar charts, pie charts, heatmaps, time series

**Libraries:** `pandas`, `matplotlib`, `seaborn`, `numpy`

---

### 2. 🏠 House Price Prediction (`House_Price_Prediction.ipynb`)

**Goal:** Build a machine learning model to predict house prices based on features like area, number of rooms, location, and amenities.

**Approach:**
1. EDA — distribution of prices, correlation heatmap, outlier detection
2. Feature engineering — encoding categorical variables, handling skewed features
3. Model training — Linear Regression, Ridge, and Random Forest
4. Evaluation — RMSE, R² score, cross-validation

**Results:**
- Random Forest achieved the best performance with R² ≈ 0.87
- Top predictors: GrLivArea, OverallQual, GarageCars, TotalBsmtSF

**Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🛠️ Setup

```bash
# Clone the repo
git clone https://github.com/muthinenisravanthi/data-analysis-ml-projects.git
cd data-analysis-ml-projects

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

---

## 📚 Skills Demonstrated

| Skill | Where Used |
|---|---|
| Data Cleaning & Wrangling | Both notebooks |
| Exploratory Data Analysis | Netflix Analysis |
| Feature Engineering | House Price Prediction |
| Machine Learning (Regression) | House Price Prediction |
| Data Visualization | Both notebooks |
| Statistical Analysis | House Price Prediction |

---

## 🗂️ Tech Stack

- **Language:** Python 3.10
- **Data:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **ML:** Scikit-learn
- **Environment:** Jupyter Notebook

---

## 👩‍💻 Author

**Sravanthi Muthineni** — MSc Data Science @ TU Wien, Vienna
- 💼 [LinkedIn](https://linkedin.com/in/sravanthi-muthineni)
- 🐙 [GitHub](https://github.com/muthinenisravanthi)
