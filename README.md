# Electric Vehicle Data Analysis Project

##  Overview
This project analyzes electric vehicles (EVs) dataset using Python and statistical methods.  
The goal is to help customers and stakeholders make informed decisions by exploring price, range, energy consumption, and performance factors.

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Dataset: EV specifications (Excel file)

## Project Structure
├── data/ # EV dataset (Excel/CSV)
├── notebooks/ # Jupyter notebook with full code
├── reports/ # Project PDF report
├── README.md # Documentation

##  Tasks & Insights

### ✅ Task 1: EVs under budget with required range
- Customer budget: 350,000 PLN  
- Minimum range: 400 km  
- Result: Multiple models (Tesla, Audi, Hyundai, Kia, etc.) fit these criteria.  

### ✅ Task 2: Outlier Detection in Energy Consumption
- Methods: IQR & Z-score  
- Result: No significant outliers → dataset is clean and consistent.  

### ✅ Task 3: Relationship between Battery Capacity & Range
- Strong positive correlation: larger batteries → higher range.  
- But efficiency matters too (same battery size can give different ranges).  

### ✅ Task 4: EV Recommendation System
- Built a Python class `EVRecommender`  
- User inputs: Budget, desired range, minimum battery capacity  
- Output: Top 3 EVs matching requirements  

### ✅ Task 5: Hypothesis Testing (Tesla vs Audi Engine Power)
- Two-sample t-test  
- Result: No statistically significant difference in engine power between Tesla & Audi.  

---

## Key Findings
1. Several EVs available under 350,000 PLN with 400+ km range.  
2. Battery capacity strongly drives range, but efficiency differs across brands.  
3. Energy consumption data is consistent (no outliers).  
4. Simple recommender system helps filter cars by budget and needs.  
5. Tesla ≈ Audi in engine power (no significant statistical difference).  

---

##  How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/Electric-Vehicle-Data-Analysis.git
   cd Electric-Vehicle-Data-Analysis

