# Data Professional Survey Breakdown - Power BI Report

This repository contains the Power BI report "Data Professional Survey Breakdown," which provides insights into data professionals' demographics, salaries, programming language preferences, and job satisfaction.

## Table of Contents

1.  **Overview**
2.  **Key Features**
3.  **Data Sources**
4.  **How to Use**
5.  **Snapshots**
6.  **Technical Details**
7.  **Contributing**
8.  **License**

## 1. Overview

This report analyzes data from a survey of data professionals, offering a comprehensive view of their demographics, salary distribution by job title and sex, favorite programming languages, and overall happiness with salary and work-life balance. It is designed to be interactive, allowing users to filter and explore the data based on various criteria.

## 2. Key Features

* **Interactive Slicers:** Filter data by "Country of Survey Taker," "Favorite Programming Language," and "Job title."
* **Salary Analysis:** Visualize average salaries by job title and sex.
* **Programming Language Preferences:** Explore the distribution of favorite programming languages among data professionals.
* **Happiness Metrics:** Track average age, total survey count, happiness with salary, and happiness with work-life balance.
* **Visualizations:** Use treemaps, bar charts, column charts, donut charts, and gauge charts for data representation.

## 3. Data Sources

* [Specify the data source(s) used. For example, "A CSV file containing survey responses from data professionals."]

## 4. How to Use

1.  **Download the .pbix file:** Download the `Data Professional Survey Breakdown.pbix` file from this repository.
2.  **Open in Power BI Desktop:** Open the file using Power BI Desktop.
3.  **Interact with the report:** Use the slicers to filter the data, hover over visualizations for tooltips, and explore the different dashboards.
4.  **Refresh Data (if needed):** If the data source is updated, refresh the report to reflect the latest data.

## 5. Snapshots

**Snapshot 1: Main Dashboard Overview**

![Main Dashboard](snapshot1.png)

This snapshot shows the main dashboard, displaying key metrics like average age, total survey count, salary distribution by job title and sex, programming language preferences, and happiness metrics.

**Snapshot 2: Salary by Job Title**

![Salary by Job Title](snapshot2.png)

This snapshot highlights the average salary distribution across different job titles in the data professional field.

**Snapshot 3: Programming Language Preferences**

![Programming Languages](snapshot3.png)

This snapshot shows the distribution of favorite programming languages among survey respondents.

**(Replace `snapshot1.png`, `snapshot2.png`, `snapshot3.png` with the actual paths to your snapshot images.)**

## 6. Technical Details

* **Power BI Version:** [Specify the Power BI Desktop version used to create the report].
* **Data Model:** [Briefly describe the data model and any relevant relationships].
* **DAX Measures:**
    * `Average Age = AVERAGE('Table'[Age])`
    * `Total Count of Survey = COUNTROWS('Table')`
    * `Average Salary by Job Title = AVERAGE('Table'[Salary])` (Used in the bar chart)
    * `Average Salary by Sex = AVERAGE('Table'[Salary])` (Used in the donut chart)
    * `Happiness with Salary = AVERAGE('Table'[Salary Happiness])`
    * `Happiness with Work Life Balance = AVERAGE('Table'[Work Life Balance Happiness])`
    * `Count of Voters = COUNTROWS('Table')` (Used in the programming language column chart)
* **[Add any other relevant technical information]**

## 7. Contributing

[If you are open to contributions, add guidelines on how to contribute.]

## 8. License

[Specify the license under which the report is distributed. For example, MIT License.]

---

**Important Notes:**

* Replace the bracketed placeholders with your specific information.
* Ensure the snapshot image paths are correct.
* If you have a separate data dictionary or DAX documentation, link to it in the "Technical Details" section.
* Update the README as you make changes to the report.
