Fast Food Nutrition Analysis
Author: Yongshi Xu | Course: DATA 6150 | Date: December 2025

Overview
Analysis of nutritional content from six major U.S. fast-food chains (McDonald's, Burger King, Wendy's, KFC, Taco Bell, Pizza Hut) to identify healthier options and predict calorie content using machine learning.

Key Findings

Burger King has highest average calories (359.2), KFC has lowest (215.2)
Strong correlation between calories and sodium (r ≈ 0.60-0.75)
Linear regression predicts calories with 99% accuracy (R² > 0.99, RMSE < 5)
Developed composite health score ranking chains by nutritional quality


Repository Structure
├── codes/                    # Jupyter notebook with all analysis
├── data/                     # fastfood.csv dataset
├── graph/                    # 5 visualization images
├── report/                   # Final report (Word + PDF)
└── README.md

Technologies

Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn


Dataset
Source: Kaggle - Fast Food Nutrition
Size: 1,133 menu items
Variables: Calories, Protein, Fat, Carbs, Sodium, Sugar, etc.

How to Run

Install requirements: pip install pandas numpy matplotlib seaborn scikit-learn
Run: jupyter notebook codes/fastfood_analysis.ipynb
Execute all cells sequentially


Results
MetricValueModel R²0.9998RMSE2-5 caloriesProtein coef.~4.0 cal/gFat coef.~9.0 cal/gCarbs coef.~4.0 cal/g
Calorie Rankings: Burger King (359.2) > Pizza Hut > McDonald's > Taco Bell > Wendy's > KFC (215.2)

Contact
Yongshi Xu | xuy1@wit.edu | Wentworth Institute of Technology
