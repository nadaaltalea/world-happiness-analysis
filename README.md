# World Happiness Report 2019 – Data Analysis & Linear Regression Model

## 📌 Project Overview
This project analyzes the **World Happiness Report 2019** dataset to identify the key factors influencing happiness levels across different countries.  
The objective is to determine how economic, social, and health-related variables impact the **Happiness Score**, and to build a **Linear Regression Model** that predicts this score using the available features.

---

## 🎯 Research Question
Can the happiness level of a country be predicted using economic, health, and social indicators such as GDP, social support, life expectancy, freedom, generosity, and corruption?

---

## 🧪 Hypothesis
Countries with:
- Higher **GDP per capita**
- Better **social support**
- Longer **healthy life expectancy**
- Higher **freedom**

tend to have higher happiness levels.  
Corruption is expected to negatively affect the happiness score.

---

## 📁 Dataset
- **Source:** World Happiness Report 2019  
- **Rows:** 156 countries  
- **Columns:** 9 numerical features  
- Dataset includes GDP, social support, healthy life expectancy, freedom, generosity, perceptions of corruption, and happiness score.

---

## 🔍 Steps Performed in the Project
### 1. **Data Loading**
Dataset was imported and stored in a pandas DataFrame.

### 2. **Descriptive Statistics**
- Summary statistics were generated.
- No missing values were found in the dataset.

### 3. **Outlier Detection**
- Boxplots identified natural variations between countries.
- Outliers were **not removed** as they represent real-world differences.

### 4. **Data Visualization**
- Histograms for all features
- Scatter plots between each predictor and happiness score

### 5. **Correlation Analysis**
- Correlation matrix and heatmap generated  
- Strongest correlations found in:
  - GDP per capita
  - Social support
  - Healthy life expectancy

### 6. **Linear Regression Model**
- Trained using 6 predictors  
- Extracted coefficients and evaluated model performance

### 7. **Model Evaluation**
Metrics used:
- **R² Score** ≈ 0.60  
- **MAE**
- **RMSE**

Model shows reasonable predictive power for socio-economic data.

---

## 🧾 Conclusion
The analysis confirms that economic stability, social support, and health conditions are strong predictors of happiness.  
Countries with stronger economies, healthier populations, and lower corruption tend to have the highest happiness scores.  
The linear regression model performed well and supported the hypothesis.

---

## 🛠️ Technologies Used
- Python  
- Google Colab  
- pandas  
- numpy  
- seaborn  
- matplotlib  
- scikit-learn  

---

## 👩‍💻 
Prepared by: Nada Altalea 

Course: Statistical Methods for Data Analysis
Instructor: Ayman Qahmish
University: King Khalid University
Date: 19. Nov.2025


---

## 🔗 Project Files
The repository contains:
- Jupyter Notebook (`.ipynb`)
- Dataset (`2019.csv`)
- Project documentation (Word/PDF)

