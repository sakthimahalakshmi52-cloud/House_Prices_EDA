House Prices EDA

Exploratory Data Analysis on House Prices Dataset

This project focuses on analyzing a House Prices dataset to uncover patterns, trends, relationships, and key factors influencing house sale prices.

Dataset

- 1,460 rows
- 81 columns
- Target variable: "SalePrice"
- Contains numerical and categorical features

Analysis Performed

- Dataset exploration and statistical summary
- Missing value analysis
- Duplicate value checking
- Sale price distribution and outlier analysis
- Correlation analysis
- Feature-wise analysis
- Data visualization

Key Insights

- "OverallQual" has the strongest correlation with "SalePrice" (0.79).
- "GrLivArea" has a strong positive relationship with "SalePrice" (0.71).
- Neighborhood, house quality, garage capacity, and living area are important factors associated with house prices.
- "SalePrice" is right-skewed, with a skewness of approximately 1.88.
- 61 potential "SalePrice" outliers were identified using the IQR method.

Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

Project File

"House_Prices_EDA.ipynb"
