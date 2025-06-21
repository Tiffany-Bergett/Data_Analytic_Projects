# US Debt Tracker

This project focuses on analyzing historical trends in US public and intragovernmental debt.
Including data cleaning, analysis, visualization, and report generation.
<!--
🎥 **The Loom Video Overview** can be found [HERE]()
-->

## Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :---------: | ----- | ----------- |
| 1 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/blob/main/US%20Debt%20Tracker/Requirements.txt) | A simple .txt file with the suggested assignment task requirements provided by "Alex the Analyst". |
| 1 | [US Debt Tracker Project.xlsx](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/blob/main/US%20Debt%20Tracker/US%20Debt%20Tracker%20Project.xlsx) | Microsoft Excel File of finished project. |
| 2 | [USDT PDF.pdf](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/blob/main/US%20Debt%20Tracker/USDT%20PDF.pdf) | PDF version of the project; includes all sheets, Pivot tables, and formula examples. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |

---

## Table of Contents for README
| Section Title | Description |
| ------------- | ----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#process) | Describes the process, including the tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#data-description) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#assumptions) | Describes assumptions to include those given by Alex the Analyst and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#recommendations) | Recommended direction for the stakeholders based on the final analysis. |
| [Notes](https://github.com/Tiffany-Bergett/Data_Analytic_Projects/tree/main/US%20Debt%20Tracker#notes) | List any special requests from the reviews or stakeholders unique to this project. |

### Description:
- Microsoft Excel, 6 Sheets
- Includes Conclusions, change-log, assumptions, 2 user-created tables, 2 Pivot Tables, 3 Charts, and formulas including functions AVERAGE and FORECAST.ETS

### Process:
1) Clean data
        -Switch Rows/Columns
        -Change the data format to a number
        -Replace "null" with blanks
2) Create a Manual pivot  table  "Yearly Debt"
        -Add calculated fields for yearly increases.
        -Create Chart
3) Create a Pivot Table for monthly averages
        -Create Chart
4) Create a Pivot Table for max debt
        -Edit for forecasting
        -Create Chart
5) Create Executive Summary

### Data
US Public Debt and Intragovernmental Holdings from 1993 to 2023:
- `'Record Date'`: The date the debt was posted.
- `'Debt Held by the Public'`: Cumulative Yearly debt held by all US citizens combined.
- `'Intragovernmental Holdings'`: Cumulative Yearly debt held by the US government on behalf of its citizens.
- `'Total Public Debt Outstanding'`: Combined debt of the public and the government.

### Assumptions:
1) 2023 is excluded due to unfinished data entries.
2) When looking for a yearly change, only the last day of each year is needed due to its cumulative nature.

### Findings:
- The average debt increase between 2001-2022 to the public is 10% and intragovernmental is 5%, making the total increase 8%.						
- The average debt increase from the last 10 years 2013-2022 to the public is 8%, and intragovernmental is 4%, making the total increase 7%.						
- Peak years for debt increase were 2008 and 2020; These years correspond to a US recession and a pandemic response in the US, respectively.											
- The highest debt increases historically occur during the months of January, December, and November; These months are common for holiday debt.						
- The lowest debt increases historically occur during the months of April, May, and June; These months have no major holidays.											
- From 1997 to 2007, we saw an increase of about 1 trillion in publicly held debt.					
- From 2008 to 2018, we saw an increase of 9 trillion in publicly held debt.						
- From 2019 to 2022, we saw an increase of 7 trillion in publicly held debt.						
- From 2023 to 2027, it is projected to increase by 7 trillion in publicly held debt.					

### Recommendations/Results:
- Publicly held debt is projected to increase at a steady rate over the next 5 years.					
- Research the stock market, housing market, credit card purchase trends, and unemployment rate to determine the cause of the increase.						

### Notes:
Raw Data, theoretical scenarios, and Questions were provided by the source, Alex the Analyst.
