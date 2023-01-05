# SHS2021_Statistics-DataAnalysis-Winter2022Co-op

## Description

During the Fall 2021 & Winter 2022 semesters, I worked as an Information Technology Assistant for the Centre for Educational & Information Technology (CEIT) at Douglas College for my Co-op work placement. My official role was that of a CEIT Student Support Assistant/Student Helping Students (SHS). I directly reported to the CEIT Service Desk. My role entailed various tasks and duties, yet the predominant purpose of my role was to provide support to Douglas College students with any issues/challenges related to educational technology through various modes of communication such as in-person interaction, email correspondance, video conferencing (i.e., Zoom & Microsoft Teams Meeting), and phone call. If I was unable to resolve the technological issue due to having lack of information, administrative rights, system clearance, or any other related reason, I would have to escalate the student's issue to the CEIT Service Desk. After any interaction with a student, it was standard procedure to record the date of interaction, time range of interaction, task category, escalation status, and the student name & contact method in a Excel Workbook that was shared with other SHSs and the Service Desk on Microsoft Teams.

During the Winter 2022 term, it was the first time Douglas College opened its doors to having in-person classes. That being said, I was interested to perform an exploratory data analysis of the 2021 SHS statistics data. It should be noted that the act of recording student interactions was introduced prior to the start of my work placement. The process of recording the student interactions was not standardized until the term prior to my hiring. Also, during my work terms, recording student interactions were prone to human errors and descrepencies. Thus, in order to perform the exploratory data analysis, I had to also perform rigorous data cleaning prior to calculating descriptive statistics, performing aggregations and constructing visualizations for the exploratory data analysis.

To perform this project at an optimal level, I utilized the **Python** programming language along with the **_Pandas_**, **_Numpy_**, **_Datetime_**, **_Scipy_**, **_Matplotlib_**, and **_Seaborn_** libraries. As I project completed during the Winter 2022 term, I was working in-person using a work station provided by CEIT Douglas College. Thus, the required tools and softwares to perform the exploratory data analysis were not pre-installed, and I did not have the administrative rights to install the technologies I required. Therefore, I utilized Jupyter Notebooks facilitated by Google Colaboratory (Google Colab) to perform the exploratory data analysis as it was accessible online through my personal Google Email account. Post-completion of the project, I made some minor adjustments to the Jupyter Notebooks using Microsoft Visual Studio Code for the purposing of sharing the codebase, aggregated datasets, and documentation to this GitHub repository. It should also be noted that Excel workbooks were the primary file formats for the raw, cleaned, and aggregated datasets. In addition, a spreadsheet was created with the help of some online tools and the Douglas College academic calenders to accurately find out the work days for the year of 2021. This was helpful during certain points of the project that required analysis of the date of interaction with the students. The final output of the project is the [**SHS Annual Statistics Report 2021**](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/SHS%20Annual%20Statistics%20Report%202021.pdf) document.

## Important Note

The raw and cleaned datasets are not provided to protect the privacy of the students that required technological assistance from Douglas College CEIT Students Helping Students.

## Project Structure

The project files are within the **SHS_2021Stats_DataAnalysis** directory of this repository. Below is a breakdown in table form that names the main project files with descriptions.

|File|Type|Description|
|--|--|--|
|[1_rawData](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/tree/main/SHS_2021Stats_DataAnalysis/1_rawData)|Directory|Contains the raw SHS statistics data for Winter 2021, Summer 2021, and Fall 2021 semesters in the form of Excel Workbooks.|
|[2_data](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/tree/main/SHS_2021Stats_DataAnalysis/2_data)|Directory|Contains the combined & cleaned 2021 SHS Statistics Data Excel Workbook, and another Excel Workbook that contains all Workday, Weekday, and Public Holiday dates for the 2021 calender year.|
|[3_analyzedData](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/tree/main/SHS_2021Stats_DataAnalysis/3_analyzedData)|Directory|Contains Excel Workbooks containing analysis and aggregations for each of the following columns: _Date_, _Time Range_, _Task Category_, and _Escalation Status_.|
|[4_visualizations](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/tree/main/SHS_2021Stats_DataAnalysis/4_visualizations)|Directory|Contains images of all of the data visualizations.|
|[References](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/tree/main/SHS_2021Stats_DataAnalysis/Reference)|Directory|Contains referential files that were helpful but not directly utilized in the codebase of the project.|
|[1_dataCleaning](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/1_dataCleaning.ipynb)|Jupyter Notebook|The Jupyter Notebook that performs all data cleaning and transformation steps to construct a unified-cleeaned SHS 2021 Statistics Dataset.|
|[2_exploratoryDataAnalysis](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/2_exploratoryAnalysis.ipynb)|Jupyter Notebook|Performs descriptive statistics analysis and aggregations of the following columns in the combined SHS 2021 Statistics Dataset: _Date_, _Time Range_, _Task Category_, and _Escalation Status_.|
|[3.1_Date_Visualizations](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/3.1_Date_Visualizations.ipynb)|Jupyter Notebook|The Jupyter Notebook containing the codebase and output to generate all visualizations related to the _Date_ column.|
|[3.2_TimeRange_Visualizations](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/3.2_TimeRange_Visualizations.ipynb)|Jupyter Notebook|The Jupyter Notebook containing the codebase and output to generate all visualizations related to the _Time Range_ column.|
|[3.3_TaskCategory_Visualizations](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/3.3_TaskCategory_Visualizations.ipynb)|Jupyter Notebook|The Jupyter Notebook containing the codebase and output to generate all visualizations related to the _Task Category_ column.|
|[3.4_EscalationStatus_Visualizations](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/3.4_EscalationStatus_Visualizations.ipynb)|Jupyter Notebook|The Jupyter Notebook containing the codebase and output to generate all visualizations related to the _Escalated to SD?_ column.|
|[SHS Annual Statistics Report 2021](https://github.com/kjeshang/SHS2021_Statistics-DataAnalysis-Winter2022Co-op/blob/main/SHS_2021Stats_DataAnalysis/SHS%20Annual%20Statistics%20Report%202021.pdf)|PDF|Combines all data visualizations into a singular & easy-to-navigate annual report.|

## How the Project Works

The project was performed across several stages. Below are the stages the project went through and explanation of the steps taken within those respective stages.

1. Data Cleaning
    * Import the relevant Python packages.
    * Import the raw datasets, containing the SHS statistics data for the Winter 2021, Summer 2021, and Fall 2021 semesters, as dataframes.
    * Update the column headings for all of the dataframes such that they are concise and not too long, which will assist when combining all dataframes together after data cleaning is complete.
    * Create a new column called _Description_ to serve as a column to save initial _Task Category_ column's entries that were made by past SHS during the work terms, but have typographical error, discrepency, or is so unique that it does not align with the current pre-determined task category types used by Service Desk and SHS.
    * Reorder the column labels of the dataframes in the following way: _Date_, _Time Range_, _Task Category_, _Escalated to SD?_, _Student Contact_, _Description_.
    * Clean the _Date_ column such that entries indicate a date that reflects a valid workday, and NOT a weekend day.
    * Clean the _Time Range_ column such that the entries have no typographical error, discrepency. Specifically, all time ranges must be of half-hour durations where the start time is half-hour earlier than the end time, all start/end times must have a "0" before the hour value if the hour value is a single digit number, and the time ranges must reflect a 24-hour clock. The aforementioned cleaning assists when ordering the dataframes in chronological order after data cleaning is complete.
    * Clean the _Task Category_ column such that all entries that have discrepencies, typographical errors, and any other anomaly, are replaced with entries that closely align with one of the following task category types currently used by Service Desk and SHS:
        * Academic Advising
        * Blackboard Issues
        * MyAccount Issues
        * Zoom Help
        * Bookstore
        * CNA/Login Issues
        * Others
        * Enrollment Service
        * Microsoft 365 Issues
        * Library and Learning Centre
        * Citrix
        * Lockdown Browser
        * Kaltura
        * Douglas College International
    * Clean the _Escalated to SD?_ column such that the entries only display "Yes" and "No".
    * After cleaning is completed, combine all dataframes together via concatenation.
    * Order the now combined dataframes's rows in chronological order by the _Date_ and _Time Range_ columns. Drop all duplicate values if necessary.
    * Export the final cleaned dataframe containing the "Cleaned 2021 SHS Statistics Data" as an Excel workbook
2. Exploratory Data Analysis
    * Import the relevant Python packages.
    * Import the "Cleaned 2021 SHS Statistics Data" Excel Workboook as a dataframe.
    * Import the "Days in 2021" Excel Workbook as a dataframe to help assit with constructing accurate aggregations for the _Date_ column.
    * Create variables to serve as parameters to serve as parameters for performing aggregations & analysis. Below are some examples:
        * List of raw semester date ranges
        * List of semester names
        * List of month names
        * List of time of day created from time ranges
        * Time of day list
        * List of task categories
        * etc.
    * Create function that calculates Descriptive Statistics (i.e., measures of dispersion and central tendency) per given time period (e.g., year, semester, month, day of week, etc). This function is applied when performing analysis in this stage of the project. During analysis, the time period, total number of cases per time period, number of work days per time period, and number of work days with no student interactions/cases is also calculated. Below is a full list of statistical measures that are considered for analysis:
        * Mean
        * Median
        * Mode
        * Minimum
        * Maximum
        * Range
        * 1st Quartile
        * 2nd Quartile
        * 3rd Quartile
        * 4th Quartile
        * Interquartile Range
        * Mean Absolute Deviation
        * Variance
        * Standard Deviation
        * Skewness
        * Kurtosis
    * Analyze the descriptive statistics and perform aggregations for all of the columns in the dataframe except for the _Student Contact_ column. The output of analysis would also be that of a dataframe. For each column of the dataframe, an Excel Workbook is created. A sheet is created for each analysis dataframe per column.
    * Below is a breakdown of the various analysis performed for each colulmn.
        * _Date_ column
            * Total Cases per Day
            * Descriptive Statistics of the Year
            * Descriptive Statistics per Semester
            * Descriptive Statistics per Month
            * Descriptive Statistics per Day of Week
            * Descriptive Statistics per Day of Week in a particular Semester
            * Descriptive Statistics per Week
        * _Time Range_ column
            *  Total Cases per Time Range
            *  Total Cases per Time Range by Time of Day
            *  Total Cases per Time Range by Semester
            *  Total Cases per Time Range by Semester & Time of Day
            *  Total Cases per Time Range by Month
            *  Total Cases per Time Range by Month & Time of Day
            *  Total Cases per Time Range by Day of Week
            *  Total Cases per Time Range by Day of Week & Time of Day
            *  Total Cases per Time Range by Day of Week in a particular semester
            *  Total Cases per Time Range by Day of Week & Time of Day in a particular semester
            *  Total Cases per Time Range by Week
            *  Total Cases per Time Range by Week & Time of Day
        *  _Task Category_ column
            * Total Cases per Task Category
            * Total Cases per Task Category by Semester
            * Total Cases per Task Category by Month
            * Total Cases per Task Category by Day of Week
            * Total Cases per Task Category by Day of Week in a particular semester
            * Total Cases per Task Category by Week
            * Total Cases per Task Category by Time Range
            * Total Cases per Task Category by Time of Day
            * Total Cases per Task Category by Time Range in a particular semester
            * Total Cases per Task Category by Time of Day in a particular Semester
        * _Escalated to SD?_ column (i.e., Escalation Status)
            * Total Cases per Escalation Status 
            * Total Cases per Escalation Status by Semester
            * Total Cases per Escalation Status by Month
            * Total Cases per Escalation Status by Day of Week
            * Total Cases per Escalation Status by Day of Week in a particular semester
            * Total Cases per Escalation Status by Week
            * Total Cases per Escalation Status by Time Range
            * Total Cases per Escalation Status by Time of Day
            * Total Cases per Escalation Status by Time Range in a particular semester
            * Total Cases per Escalation Status by Time of Day in a particular semester
            * Total Cases per Escalation Status by Task Category
            * Total Cases per Escalation Status by Task Category in a particular semester
3. Data Visualization
    > Note that this stage splits up the steps to perform Data Visualization by each analyzed column (i.e., Date, Time Range, Task Category, Escalated to SD?), of which each has its own Excel workbook with several sheets of descriptive statistics and aggregations.
    
    * Import the relevant Python packages.
    * For all of the analysis and aggregations performed in the prior stage, create visualizations ot graphically communicate the trends and observations for basic reporting purposes.














