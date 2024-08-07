Lending Club: LoanAnalysis
Overview:
This repository contains a case analysis for Lending Club's personal loan data using R programming. The project involves merging and cleaning data, performing various data analyses, and
creating visualizations to understand different aspects of Lending Club's lending practices from 2012 to 2017.

Project Structure
LendingClub.Rmd: The main R Markdown file containing the analysis, data cleaning, and visualizations.
LendingClub_LoanAnalysis.docx: The business case analysis document that outlines the project objectives, data details, and specific analysis questions.
Data Sources
The analysis is based on the following data files:

Lending Club Data (2012-2017): Data files for personal loans issued by Lending Club, provided in CSV format.
states.csv: Contains demographic information such as population size, median income, and unemployment rate for each state.
states_regions.csv: Contains information about the regions and divisions each state belongs to.
Analysis Sections
1. Merging and Cleaning
- Stacking six years of Lending Club data.
- Merging with states.csv and states_regions.csv to create a comprehensive dataset.
2. Data Analysis
- Distribution of the number of loans by state, regions, and divisions.
- Comparison of average loan amounts by state and division.
- Analysis of interest rates and loan amounts by loan grade.
- Frequency distribution of loans, average loan amounts, and interest rates by state and year.
- Relationship analysis between population size, median income, and loan characteristics.
3. Visualization
- Plot of interest rates and loan grades.
- US map color-coded by average loan amounts.
- Visualization of the relationship between annual income and loan amounts.
- Plot showing the relationship between length of employment and loan amounts.
- Regional map showcasing an interesting relationship derived from the data.

How to Run
1. Clone the repository:
git clone https://github.com/sahanaram29/LendingClub_LoanAnalysis.git
cd LendingClub_LoanAnalysis
2. Open LendingClub.Rmd in RStudio
3. Install required packages (if not already installed):
   install.packages(c("dplyr", "ggplot2", "tidyr", "maps", "ggthemes"))
4. Knit the R Markdown file if you would like to generate the analysis report in pdf/doc/html format: Click on the "Knit" button in RStudio
