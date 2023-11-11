# insurance_premium
 **Insurance Premium Dataset**

This repository contains a dataset and analysis related to insurance premiums. The dataset includes information about individuals, their characteristics, and corresponding insurance charges.

**Dataset Information**

Columns:
- **age:** Age of the individual
- **sex:** Gender of the individual (0: male, 1: female)
- **bmi:** Body Mass Index (BMI) of the individual
- **children:** Number of children/dependents covered by insurance
- **smoker:** Smoking status (0: non-smoker, 1: smoker)
- **region:** Geographic region of the individual (encoded as 0, 1, 2, 3)
- **charges:** Insurance charges for the individual
- **Age_groups:** Categorization of age into groups (Young_adults, Middle_adults, Senior_adults, Old_adults)
- **bmi_levels:** Categorization of BMI into levels (low, medium, moderate, high)
- **smoker_status:** Smoker status (Smoker, Non-Smoker)

**Exploratory Data Analysis (EDA)**

The analysis includes:
- Data loading and basic information
- Checking for duplicates and handling them
- Handling null values
- Exploring relationships between different variables
- Visualizations (heatmap, bar graphs, scatter plots, histograms) for better understanding

**Data Preprocessing**

- Mapping categorical values for better interpretation (e.g., encoding gender, smoking status, region)
- Grouping ages into meaningful categories (Age_groups)
- Investigating the relationship between BMI and charges

**Linear Regression Model**

- Utilizing the scikit-learn library to create a linear regression model
- Assessing the model's performance using training and test sets
- Evaluating the model's predictive capabilities

**Conclusion**

The analysis provides insights into the factors influencing insurance charges. The linear regression model, while simple, indicates limitations in predicting charges based solely on age.

**Instructions**

1. **Dataset:** The dataset (insurance.csv) is available in the repository.
2. **Notebooks:** Explore the analysis and model in the Jupyter Notebook (insurance_premium_analysis.ipynb).
3. **Reproduce Analysis:** You can reproduce the analysis by running the notebook in a Jupyter environment.

Feel free to contribute, provide feedback, or use the findings for your own analysis!
