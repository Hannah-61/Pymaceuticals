
## The Power of Plots

## Background
Data visualization can bring data to life, revealing patterns and insights that numbers alone cannot. In this project, you are a senior data analyst at Pymaceuticals Inc., a pharmaceutical company based in San Diego, specializing in anti-cancer treatments. Recently, Pymaceuticals conducted a study to evaluate the effectiveness of various drug regimens on squamous cell carcinoma (SCC) in mice.

The study involved 249 mice treated with multiple drugs over a 45-day period. Tumor growth was measured regularly to determine the effectiveness of each treatment. The primary objective was to evaluate the effectiveness of Capomulin, Pymaceuticals’ drug of interest, compared to other treatments. The executive team has requested visualizations and statistical summaries for a report on the study’s findings.

## Objectives
Data Cleaning:

Identify any duplicate time points for each mouse and remove associated records to ensure data integrity.

## Summary Statistics:

Generate a table showing the mean, median, variance, standard deviation, and SEM (standard error of the mean) of the tumor volume for each drug regimen.

Data Visualizations:

Bar Plots:
Create bar plots (using both Pandas and Matplotlib) to display the number of mice in each treatment regimen.
Pie Plots:
Generate pie charts (using both Pandas and Matplotlib) to show the gender distribution of the mice in the study.
Tumor Volume Analysis:

For key treatments (Capomulin, Ramicane, Infubinol, and Ceftamin), calculate the final tumor volume for each mouse.
Calculate quartiles and IQR (interquartile range) to detect any potential outliers.
Use a box plot to visualize the final tumor volumes for these treatments, marking outliers in a distinct color.
Capomulin Treatment Analysis:

Select a mouse treated with Capomulin and create a line plot of tumor volume over time.
Generate a scatter plot of mouse weight versus average tumor volume for all mice treated with Capomulin.
Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume, and overlay the regression line on the scatter plot.

## Summary of Findings:

Write a brief summary of at least three observations based on the visualizations and analyses.
Place these observations at the beginning of the notebook for quick reference.

## Key Findings
Capomulin and Ramicane Show Promising Results:

Capomulin and Ramicane had the lowest average tumor volumes (around 40 mm³), suggesting they may be more effective than other treatments in reducing tumor size.
Positive Correlation Between Mouse Weight and Tumor Volume for Capomulin:

For mice treated with Capomulin, there is a positive correlation (correlation coefficient ~0.84) between mouse weight and average tumor volume. This suggests that heavier mice tend to have larger tumors, which may be relevant for dosing and treatment efficacy.
Consistency in Results for Capomulin and Ramicane:

Both Capomulin and Ramicane treatments showed lower variability in tumor volumes, indicating consistent performance across mice. This predictability supports their potential effectiveness as anti-tumor drugs.

## Requirements
Python Libraries: Pandas, Matplotlib, Scipy
Data: Ensure the dataset (clean_df) is loaded and cleaned of duplicate time points.
Usage
Run the Notebook:
Execute each cell in the notebook to generate tables, summary statistics, and visualizations.
Inspect Outputs:
Review the plots and figures to understand the effectiveness of each drug regimen.

## Review Summary:
Check the top of the notebook for a summary of key observations and findings from the analysis.

## Conclusion
This analysis provides insights into the potential of Capomulin and Ramicane as treatments for squamous cell carcinoma. These two drugs demonstrated lower and more consistent tumor volumes, making them promising candidates for further study. Additionally, the positive correlation between mouse weight and tumor volume within the Capomulin regimen highlights areas for potential dosing adjustments.
