🚧 PROJECT PAGE UNDER CONSTRUCTION 🚧  
# File Title: NYC Transportation Analysis

### Description of Project Scope, Roles, & Responsibilities
This project analyzes NYC transportation data to provide insights into delays and breakdowns within the bus system. The analysis identifies common reasons for these issues, variations in delay times across bus companies and boroughs, and weekly trends. The goal is to provide actionable recommendations for improving efficiency and reducing disruptions.

[<img src="https://github.com/Tiffany-Bergett/Data_Projects_Personal_Projects/blob/main/Images/NYCTransCP.png" alt="First Analytical Sheet of Project**">](https://docs.google.com/spreadsheets/d/11g0H_hpKuW9gY2ppFh8apFvPY88fVrzq/edit?usp=sharing&ouid=101031187502320177888&rtpof=true&sd=true)

Video Overview can be found [HERE]()
Project can be found [HERE](https://docs.google.com/spreadsheets/d/11g0H_hpKuW9gY2ppFh8apFvPY88fVrzq/edit?usp=sharing&ouid=101031187502320177888&rtpof=true&sd=true)

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | :-----------: | :-----------: |
| 1 | [NYC Transportation Project.pdf](https://github.com/Tiffany-Bergett/Data_Projects_Personal_Projects/blob/main/NYC%20Transportation/NYC%20Transportation%20Project.pdf) | PDF file containing the cleaned and analyzed NYC transportation data, including pivot tables and charts. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_Projects_Personal_Projects/blob/main/NYC%20Transportation/Requirements.txt) | A simple .txt file with the provided project requirements as provided by "Alex the Analyst". |

### Table of Contents for README
| Section Title | Description |
| :-----------: | :-----------: |
| [Description](LINK) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](LINK) | Describes the process, including tools or tech used. |
| [Data](LINK) | Describes the data source, including files, tables, and fields. |
| [Assumptions](LINK) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](LINK) | Insights learned from the data analysis. |
| [Recommendations](LINK) | Recommended direction for the stakeholders based on the final analysis. |
| [Notes](LINK) | Lists any special requests from the reviews or stakeholders unique to this project. |

#### Description:  
* Software: Excel, 7 sheets
* The Excel workbook includes cleaned data, pivot tables, and charts visualizing trends in delays and breakdowns, analysis of delay times by company and borough, and identification of top 10 companies with highest delay times. 

#### Process:  
* The project started by setting up workbook structure and cleaning raw data.
* Then creating new columns for analysis.
* After, for each question, I created pivot tables and charts to analyze and visualize the data.
* Finally I summarized the analysis and proposed next steps in an executive summary.

#### Data Description:  
* 'Raw Data': This sheet contains the original, uncleaned NYC transportation data. 
    * 'Occurred_On': Date and time of the incident. 
    * 'Company_Clean': Bus company name (potentially requiring normalization).
    * 'How_Long_Delayed': Delay time information. 
    * 'Reason': Reason for delay or breakdown. 
    * 'Breakdown_or_Running_Late': Indicates if the incident was a breakdown or a delay. 
    * 'Boro': Borough where the incident occurred.
* 'Clean Data': This sheet contains the raw and clean/transformed data used for analysis.
    * 'Weekday_Occured': Day of the week the incident occurred. 
    * 'Bus_Company_Name': Normalized bus company names.
    * 'Short_Delay_Est': Short delay time estimate. 
    * 'Long_Delay_Est': Long delay time estimate. 

#### Assumptions:  
* Similar-sounding bus company names can be aggregated as the same company. 
* One event marked "running late" with no delay time was assumed to have a 0-minute delay. 
* Null boroughs were excluded from borough delay analysis. 
* Blanks and outliers were removed from weekday analysis.

#### Findings:  
* The majority of breakdowns are due to mechanical problems, including "Won't Start". 
* The main cause of delays is heavy traffic. 
* Delay times vary greatly between bus companies, with Selby Transportation, Little Linda Bus Co., and Pride Transportation experiencing some of the highest delays. 
* Boroughs with the highest delay times are the main areas of NYC. 
* There is a gradual decrease in breakdowns throughout the week.
* There is a spike in delays on Monday and lower delays on Fridays.

#### Recommendations:  
* Implement more precautionary maintenance to prevent mechanical problems.
* Schedule maintenance over weekends to limit breakdowns at the beginning of the week. 
* Have buses pick up the majority of students at non-high traffic times. 
* Use the Delay Time Table and Chart to compare the number of delays, boroughs, and the total number of trips. 
* Delays could be due to mechanical issues that can be fixed with regular maintenance, high-density boroughs where routes need to be reworked, or inefficient handling of companies, and their contracts should be re-evaluated. 
* Since the majority of delays are caused by traffic, the decrease in delays on Friday is likely caused by fewer people going to work or driving. 
