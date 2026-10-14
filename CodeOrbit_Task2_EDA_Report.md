
# Task 2: Exploratory Data Analysis (EDA)

**Dataset:** Titanic Passenger Dataset
**Tools:** Python, Pandas, Matplotlib, Seaborn

## 1. Objective
The objective was to explore passenger data through visualizations
and identify patterns, trends, and potential outliers.

## 2. Key Findings

- Overall survival rate: 38.38%.
- Female survival rate: 74.20%.
- Male survival rate: 18.89%.
- First-class survival rate: 62.96%.
- Second-class survival rate: 47.28%.
- Third-class survival rate: 24.24%.
- Median passenger age: 28.00 years.
- Mean passenger age: 29.36 years.
- Potential high-fare outliers: 116.
- IQR upper fare threshold: 65.63.

## 3. Interpretation
Female passengers had a higher observed survival rate than male
passengers in this dataset. First-class passengers had the highest
survival rate, while third-class passengers had the lowest.

The fare distribution contains high values flagged by the IQR rule.
These observations require investigation and should not be removed
without a clear reason.

## 4. Limitations
The Age column contains median-imputed values, which affect the age
distribution. The analysis shows associations and does not establish
causation.

## 5. Conclusion
EDA revealed differences in survival rates by gender and passenger
class, along with potential high-fare outliers. The visualizations
and summary statistics help describe the dataset and support
further investigation.

**Deliverable:** Task2_Exploratory_Data_Analysis.ipynb
