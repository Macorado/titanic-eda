# Titanic Dataset – Exploratory Data Analysis (EDA)

This is an EDA project focused on the Titanic dataset. It uses Python-based data analysis libraries to explore trends in passenger survival outcomes.

---

## Tools & Libraries Used
- **Pandas** – data manipulation  
- **NumPy** – numerical operations  
- **Seaborn** – visualization  
- **Matplotlib** – plotting  

---

## Key Findings from the Analysis
- **Gender played a significant role in survival**: approximately **74% of women survived**, compared to just **18% of men**.
- **Passenger class was inversely correlated with survival**: first-class passengers had much higher survival rates than those in second or third class.
- **Age showed little to no correlation** with survival, despite the common belief that younger passengers were prioritized.
- These findings align with historical accounts: women and children were prioritized, and many lower-class passengers were trapped below deck.
- **Next Steps**: `Pclass` and `Sex` appear to be strong predictors and are good candidates for a future classification model. `Fare` may also be relevant.

---

## How to Use
- Open the notebook in **Jupyter** or **Google Colab**
- Run all cells in order to reproduce the analysis
