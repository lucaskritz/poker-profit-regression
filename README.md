# poker-profit-regression

### 🚀 TL;DR  
This project implements a quadratic regression model to predict net profit in poker tournaments using factors like game type, Buy-In, total entries, and rebuys. Despite using Ridge regression and multiple predictors, the model showed poor performance, suggesting the predictors may not strongly influence profitability.

---

### 📊 Project Overview  
This project implements a **quadratic regression model** using the **scikit-learn** package to predict net profit in poker tournaments. The model is based on several predictors, including:
- Game type
- Buy-In
- Total entries
- Entries per individual
- Buy-In with rebuys

Despite adding multiple predictors and tuning the model with **Ridge regression**, the results showed poor performance:
- Both training and testing **RMSEs** remained high
- **R²** values were close to zero

These results suggest that the relationship between the predictors and net profit may not be easily captured by linear models. Additionally, non-linear interactions between the variables did not provide significant improvements.

---

### 🔍 Key Findings  
- **Buy-In** and **rebuys** were identified as the most influential factors on profitability.
  - **Rebuys** positively impacted profit.
  - **Higher Buy-In** generally led to lower net earnings.
- Despite these insights, the model showed no substantial improvement, indicating that the chosen predictors may not have a meaningful or strong influence on profitability in this dataset.

---

### 📁 Repository Contents  
This repository includes:
- The formal **writeup** of my findings
- The **complete code** used for the analysis
- The relevant **CSV data file**

---

Feel free to explore the code and data to see the analysis in more detail.
