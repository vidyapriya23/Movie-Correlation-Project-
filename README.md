# Movie-Correlation-Project-
This project explores the relationships between various movie attributes and their potential impact on gross earnings using Python's data analysis libraries.
# Data Acquisition and Cleaning 
Movie data is imported using libraries like pandas.
Used Data cleaning techniques to address potential issues like missing values, duplicates, or inconsistent formats.
# Visualization and Correlation analysis 
Created scatter plots to visually examine associations between specific features, such as budget vs. gross revenue.
Choose Pearson method correlation coefficient and calculated to quantify the strength and direction of linear relationships between variables. A heatmap (using seaborn) is used to visualize the correlation matrix for all numerical features.
# Categorical Data Handling 
Wrote a condition to check if the data type of the current column is 'object' 
If the condition is true it converts the columns to category type 
Used cat.codes to assign the categorial codes back to the same column 
# Insights 
Analyzed the correlation values and identified variables with high positive correlations to gross earnings, suggesting potential factors influencing revenue.
# Outcome
Identified features with strong positive correlations to gross earnings.
Gain insights into potential factors affecting movie revenue.
Understood the limitations of correlation analysis (e.g., doesn't necessarily imply causation).
