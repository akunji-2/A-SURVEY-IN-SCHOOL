# A-SURVEY-IN-SCHOOL
School Survey Analysis
This repository contains the dataset and analysis scripts for a school survey conducted to understand various parameters such as school location, gender distribution, and reasons affecting education trends. The analysis leverages Excel for data storage and R for comprehensive data cleaning, analysis, and visualization.

Repository Contents
Files
ASURVEY IN A SCHOOL Data cleaning.xlsx

The raw dataset collected from the school survey.
Contains structured responses categorized across various survey questions.
analysis_script.R

R script for performing the data cleaning, analysis, and visualization.
Includes detailed comments for understanding the workflow.
Output Files (generated after running the R script):

cleaned_data.csv: Cleaned and processed version of the dataset.
summary_statistics.csv: Summary statistics of numeric data.
Visualization outputs:
location_distribution.png: Bar plot of school locations.
gender_pie_chart.png: Pie chart of gender distribution.
Requirements
Tools
Excel: To view and modify the original dataset.
R: For data analysis and visualization.
R Libraries
The following R libraries are required to run the analysis_script.R:

readxl: For reading Excel files.
dplyr: For data manipulation.
ggplot2: For creating visualizations.
Install these libraries using the command:

R
Copy code
install.packages(c("readxl", "dplyr", "ggplot2"))
Usage
Step 1: View the Dataset
Open the ASURVEY IN A SCHOOL Data cleaning.xlsx file in Excel to review the survey responses.

Step 2: Run the R Script
Open analysis_script.R in your R IDE (e.g., RStudio).
Ensure the Excel file is in your working directory.
Run the script to:
Clean the data.
Generate summary statistics.
Create visualizations.
Save processed outputs.
Step 3: Review Outputs
Visualizations: Check the .png files for graphical insights.
Cleaned Data: Use cleaned_data.csv for further analysis.
Statistics: Refer to summary_statistics.csv for descriptive statistics.
Analysis Overview
Key Insights
School Location: Majority of respondents are from Kakuma 1 (62.7%), followed by Kakuma 2 (37.3%).
Gender Distribution: Visualized in the gender_pie_chart.png.
Additional analyses include age distribution, reasons for reduced numbers of girls, and others.
Visualizations
Bar Chart: Represents the distribution of school locations.
Pie Chart: Visualizes gender proportions.
Contribution
If you'd like to contribute or provide feedback, please open an issue or submit a pull request. Contributions are welcome to extend the analysis or refine the script.

License
This project is licensed under the MIT License. See the LICENSE file for details.

