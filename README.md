# Economic Regression Analysis (Iran) 📊📉

## 📌 Introduction
This project implements a comprehensive **regression analysis** using **R** to explore the relationships between economic indicators in **Iran**, including **Overall Index, Interest Rate, Inflation Rate, Exchange Rate, and Oil Price**. The analysis includes **normality tests, homogeneity tests, transformation of variables, multicollinearity checks, and advanced regression techniques**.

## 🚀 Features
- **Data Processing & Exploration**:
  - Importing data from an Excel file using `readxl`.
  - Summary statistics and visualization of economic indicators.
- **Normality Tests**:
  - **Anderson-Darling, Kolmogorov-Smirnov, and Shapiro-Wilk tests** to check normality.
- **Data Transformation**:
  - **Box-Cox, Log, and Inverse transformations** to improve normality and linearity.
- **Homogeneity of Variance Tests**:
  - **Bartlett, Levene, and Fligner-Killeen tests** to check variance stability.
- **Multicollinearity Check**:
  - **Variance Inflation Factor (VIF)** to detect collinearity among predictors.
- **Linear Regression Modeling**:
  - **Ordinary Least Squares (OLS) Regression** to examine economic trends.
  - **Weighted Least Squares (WLS) Regression** for heteroscedasticity correction.
  - **Robust Regression (Huber’s Method)** to handle outliers.
- **Model Evaluation**:
  - **Residual Analysis** including QQ plots, histograms, and residual-vs-fitted plots.
  - **Breusch-Pagan and Goldfeld-Quandt tests** for heteroscedasticity detection.
  - **Cook’s Distance** to identify influential points.
  - **ANOVA Analysis** to determine significance of predictors.

## 📂 Project Structure
```
📦 Economic-Regression-Analysis
├── 📜 regression.Rmd             # R Markdown file with full implementation
├── 📜 Final_Data_Translated.xlsx # Dataset file
├── 📜 README.md                  # Project documentation
```

## 🛠️ Installation
Ensure you have **R** installed, then install the required packages using:
```r
install.packages(c("readxl", "nortest", "car", "lmtest", "MASS", "sandwich"))
```

## 📌 How to Run
1. Open **RStudio** or **R Notebook**.
2. Load the dataset (`Final_Data_Translated.xlsx`).
3. Run the `regression.Rmd` file to execute the full analysis.

## 📊 Results Analysis
- **Visualizations**: Histograms, QQ Plots, and residual scatterplots.
- **Model Performance**: R-squared, p-values, and coefficient significance.
- **Diagnostic Tests**: Multicollinearity (VIF), heteroscedasticity (BP Test), and normality of residuals.

## 📧 Contact
For any inquiries or collaboration opportunities, reach out to:
📩 Email: emad.k50000@gmail.com

## ⭐ Contribute
Feel free to fork this repository, report issues, or submit pull requests to improve the project.

🔹 **Developed by Emad K | Open Source & Research-Oriented**

