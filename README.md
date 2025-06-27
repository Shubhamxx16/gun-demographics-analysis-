# gun-demographics-analysis-
Gun Background Check and Demographic Correlation Analysis Conducted exploratory data analysis on FBI NICS background checks and U.S. Census data to identify how demographic variables such as population, income, education, and veteran presence correlate with gun activity across states. Using Pandas, Matplotlib, and Seaborn.


# Gun Background Checks vs. U.S. Demographics

## 📌 Objective
Explore how demographic features such as population, income, education level, and veteran presence relate to gun background check activity across U.S. states.

## 📊 Data Sources
- FBI NICS Gun Background Checks: `gun_data.xlsx`
- U.S. Census Demographic Data: `U.S. Census Data.csv`

## 🛠 Tools Used
- Python
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Key Findings
- **Population size** strongly correlates with gun background check volume.
- Weak **negative correlation** between education level and gun activity.
- **Veteran presence** showed a mild positive correlation.
- Income and poverty rates had **no strong relationship** to gun checks.

## 📁 Files
- `gun_demographics_analysis.ipynb` – full analysis
- `gun_data.xlsx` – FBI NICS data
- `U.S. Census Data.csv` – U.S. state demographics

## ✅ Future Improvements
- Normalize gun checks per capita
- Add gun legislation strength index
- Build a predictive regression model
