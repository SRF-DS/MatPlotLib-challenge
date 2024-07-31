# MatPlotLib-challenge
 Module 5 Challenge due 8/1 at 11:59pm

 ### Overview

The dataset comprises information on the efficacy of four drug regimens—Capomulin, Ramicane, Infubinol, and Ceftamin—on tumor volume in mice. The analysis includes calculating the final tumor volume for each mouse, identifying potential outliers, and visualizing the data through box plots, line plots, and scatter plots. Additionally, the correlation between mouse weight and average tumor volume under the Capomulin regimen was examined using linear regression.

1.  Final Tumor Volume Across Treatment Regimens
    The final tumor volume was calculated for each mouse across the four treatment regimens.
    The data was grouped by Timepoint to obtain the last recorded tumor volume, which was then merged with the original dataset to retain the drug regimen information.

 2.  Interquartile Range (IQR) and Outliers
    For each treatment group, the quartiles (25th, 50th, and 75th percentiles) and the IQR were calculated.
    The IQR was used to determine the lower and upper bounds for potential outliers.The only outlier identified was for Infubinol at 36.32mm³ indicating variability in response to the treatments.

3.  Box Plot Analysis
    A box plot was generated to visualize the distribution of final tumor volumes for each treatment group.
    Observation: Capomulin and Ramicane showed lower median tumor volumes compared to Infubinol and Ceftamin, suggesting higher efficacy in reducing tumor size.


4.  Line Plot for Capomulin Treatment
    A line plot was created to show the tumor volume over time for a single mouse treated with Capomulin.
    Observation: The tumor volume decreased consistently over time, demonstrating the effectiveness of Capomulin in reducing tumor size.

5.  Scatter Plot of Mouse Weight vs. Average Tumor Volume for Capomulin
    A scatter plot was generated to examine the relationship between mouse weight and average tumor volume for the Capomulin regimen.
    Observation: There was a positive correlation between mouse weight and average tumor volume, indicating that heavier mice tend to have larger tumors.

6.  Correlation and Linear Regression Analysis
    The correlation coefficient between mouse weight and average tumor volume was calculated.
    A linear regression model was fitted to the data, and the regression line was plotted.
    Result: The correlation coefficient was 0.84, indicating a strong positive correlation. The linear regression model further supported this relationship, with an R-squared value of 0.71.





### Analysis

- Effectiveness of Drug Regimens:
    - Capomulin and Ramicane appear more effective in reducing tumor size compared to Infubinol and Ceftamin, as indicated by their lower median tumor volumes.  The included box plot below shows lower median values for Capomulin and Ramicane, and lower overall variance compared to Infubinol and Ceftamin. From our calculations Capomulin and Ramicane have an IQR of 7 and 9 respectively indicating a tighter range of values. Based on the data we can see that there is less variance which we can infer means that these drugs efficacy yeild more consistent outcomes in function rather than Infubinol and Ceftamin.

- Correlation Between Weight and Tumor Volume:
    - Inference: There is a positive correlation between mouse weight and average tumor volume in the Capomulin regimen, suggesting that heavier mice tend to have larger tumors.
    - Supporting Data: The scatter plot shows a positive trend, and the correlation coefficient is positive. The linear regression line further supports this relationship.

