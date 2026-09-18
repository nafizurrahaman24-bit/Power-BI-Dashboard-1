# Power BI Dashboard 1
**# 📊 Data Jobs Market Analysis — Power BI Dashboard**

An interactive **\*\*Power BI dashboard for analyzing the data jobs market\*\***, focusing on job demand, salaries, job titles, geographic distribution, work-from-home opportunities, degree requirements, employment schedules, and job-posting trends.

The project was developed as a practical **\*\*data analytics and business intelligence project\*\*** to demonstrate data visualization, exploratory analysis, dashboard development, and interactive reporting using Microsoft Power BI.



**## 🖥️ Dashboard Preview**

**### Main Dashboard**

![Data Jobs Market Analysis Dashboard] ![alt text]\(Dashboard-1.png)

\> **\*\*Preview:\*\*** The image above shows a snapshot of the interactive Power BI dashboard.

\> The complete interactive Power BI report is included in this repository as a .pbix file.

**## 📌 Project Overview**

The dashboard transforms job-posting data into an interactive analytical report that helps users explore the data-job market from multiple perspectives.

The analysis focuses on questions such as:

\* Which data-related job titles have the highest salaries?

\* Which job roles have the greatest number of postings?

\* How do salaries vary across countries?

\* How has job-posting volume changed over time?

\* What proportion of jobs allow work from home?

\* How frequently do job postings mention a degree requirement?

\* Which employment/schedule types are most common?

\* How do annual and hourly salaries compare across job titles?

\* How do job opportunities differ geographically?

**## 🎯 Objectives**

The main objectives of this project are to:

1\. Analyze demand for different data-related job roles.

2\. Compare annual and hourly salary levels.

3\. Examine job opportunities across countries.

4\. Analyze job-posting trends over time.

5\. Investigate remote/work-from-home opportunities.

6\. Examine degree requirements in job postings.

7\. Compare different job schedule types.

8\. Build an interactive dashboard for exploratory analysis.

9\. Demonstrate practical Power BI and business intelligence skills.

**## 🛠️ Tools & Technologies**

\| Tool                   | Purpose                                                             |

\| ---------------------- | ------------------------------------------------------------------- |

\| **\*\*Microsoft Power BI\*\*** | Data visualization, dashboard development, and interactive analysis |

\| **\*\*Power Query\*\***        | Data preparation and transformation                                 |

\| **\*\*DAX\*\***                | Measures and analytical calculations                                |

\| **\*\*Data Visualization\*\*** | Charts, maps, cards, tables, and KPIs                               |

\| **\*\*GitHub\*\***             | Project documentation and portfolio presentation                    |

**## 📂 Dataset**

The dashboard is built around a job-postings dataset containing information related to data and technology positions.

The primary table used in the Power BI model is:

\`job\_postings\_flat\`

Important fields used throughout the dashboard include:

\* \`job\_title\_short\`

\* \`job\_title\`

\* \`company\_name\`

\* \`job\_country\`

\* \`job\_posted\_date\`

\* \`job\_schedule\_type\`

\* \`job\_work\_from\_home\`

\* \`job\_no\_degree\_mention\`

\* \`job\_via\`

\* \`salary\_year\_avg\`

\* \`salary\_hour\_avg\`

The dataset allows job-market characteristics to be analyzed across **\*\*job role, salary, geography, time, employment structure, and job requirements\*\***.



**# 📊 Dashboard Structure**

The Power BI report contains several analytical pages, each designed for a specific type of analysis.

**## 1. 🏠 Home**

The **\*\*Home\*\*** page serves as the navigation interface for the report.

It provides access to the different analytical sections of the dashboard through interactive navigation elements.



**## 2. 📊 Data Jobs Dashboard**

The main dashboard provides a high-level overview of the data-job market.

**### Key metrics include:**

\* Job Count

\* Median Yearly Salary

\* Median Hourly Salary

\* Salary Star Rating

\* Job-posting trends

**### Visualizations include:**

\* Job title slicer

\* Job-posting trend line chart

\* Job count by job title

\* Salary comparison by job title

\* Job-market summary table

\* Yearly and hourly salary comparison

\* Job trend sparklines

This page is designed to provide a quick overview before users move into more detailed analysis.



**## 3. 📈 Column & Bar Charts**

This page focuses on comparing job roles and their characteristics using bar and column charts.

**### Visualizations include:**

\* Job title vs. median yearly salary

\* Country vs. job title vs. median yearly salary

\* Job title vs. degree requirement

\* Percentage of jobs without a degree mention

These visualizations make it easier to compare salary levels and job requirements across different roles and countries.

**## 4. 📉 Line & Area Charts**

This section analyzes the **\*\*temporal dimension of the job market\*\***.

**### Visualizations include:**

\* Job count over time

\* Job-posting trends by job title

\* Percentage distribution of job postings over time

\* Annual and hourly salary comparison by job title

The area and line charts allow users to identify changes in job-posting activity and examine how demand evolves over time.

**## 5. 🥧 Pie & Other Charts**

This page provides additional categorical analysis.

**### Visualizations include:**

\* Work-from-home availability

\* Job schedule type

\* Degree requirements

\* Annual salary vs. hourly salary

\* Job-title salary relationships

Visualizations such as donut charts, pie charts, treemaps, and scatter plots provide alternative perspectives on the dataset.

**## 6. 🌍 Map Charts**

The **\*\*Map Charts\*\*** page focuses on the geographical distribution of data-related employment opportunities.

**### Visualizations include:**

\* Job count by country

\* Annual median salary by country

\* Geographic salary distribution

The geographic analysis helps identify differences in job-market activity and salary levels across countries.

**### ⚠️ Map Availability**

The map visuals are available and visible in the Power BI environment used to develop this project through a **\*\*university-provided Power BI account\*\***.

However, **\*\*map visualization availability can depend on the user's Power BI account, licensing, organization settings, and Microsoft service availability\*\***. Some users may therefore be unable to view or interact with the map visuals, particularly when using an account without the required Power BI capabilities.

If the maps are unavailable in the interactive report, the remaining dashboard pages and analytical visuals can still be explored.

**## 7. 📋 Table**

The table page provides a more detailed view of individual job records.

The report includes information such as:

\* Job title

\* Full job title

\* Company

\* Annual salary

\* Job type

\* Ratings

A pivot-style table also allows job titles to be compared using:

\* Job count

\* Yearly salary

\* Hourly salary

\* Job trends

This page is useful when users want to move from high-level visual analysis to more detailed job-level information.

**## 8. 💳 Cards & KPI Analysis**

The Cards page presents key metrics in a compact format.

It includes:

\* Annual salary

\* Hourly salary

\* Median salary

\* Salary comparisons

\* KPI indicators

\* Gauge visualizations

\* Job-title-level salary metrics

These components are designed to make important metrics immediately visible.

**## 9. 🎛️ Slicers**

The report includes interactive slicers that allow users to filter the dashboard.

Examples include:

\* **\*\*Job Title\*\***

\* **\*\*Job Posted Date\*\***

These filters dynamically update the relevant visualizations throughout the report.

**## 10. 🔎 Job Title Drill Through**

The project also includes a dedicated **\*\*Job Title Drill Through\*\*** page.

Users can select a job title and examine additional information for that specific role.

The drill-through analysis includes:

\* Salary metrics

\* Hourly salary

\* Work-from-home availability

\* Geographic distribution

\* Schedule type

\* Job source

\* Job count

This functionality allows the dashboard to move from **\*\*market-level analysis to role-specific analysis\*\***.

**# 📌 Key Analytical Dimensions**

The dashboard analyzes the job market across several dimensions:

**### Job Demand**

\* Number of job postings

\* Job title distribution

\* Job-posting trends

**### Compensation**

\* Annual salary

\* Hourly salary

\* Median salary

\* Salary comparison across roles

\* Salary comparison across countries

**### Geography**

\* Country-level job counts

\* Country-level salary analysis

**### Work Arrangement**

\* Work-from-home availability

**### Education**

\* Whether a degree is mentioned in the job posting

**### Employment Structure**

\* Job schedule type

**### Time**

\* Year

\* Quarter

\* Month

\* Day

**# 🔄 Interactive Features**

The dashboard was designed as an interactive analytical tool rather than a static report.

Key interactive features include:

\* **\*\*Slicers\*\***

\* **\*\*Drill-through\*\***

\* **\*\*Cross-filtering\*\***

\* **\*\*Interactive charts\*\***

\* **\*\*Map-based exploration\*\***

\* **\*\*Dynamic KPI cards\*\***

\* **\*\*Trend analysis\*\***

\* **\*\*Pivot-style tables\*\***

\* **\*\*Page navigation\*\***

Users can therefore move from a broad market overview to a specific job title and explore the associated salary, location, work arrangement, and employment characteristics.

**# 📈 Example Business Questions**

The dashboard can be used to explore questions such as:

**### Salary**

\> Which job titles have the highest median yearly salaries?

**### Demand**

\> Which data-related roles appear most frequently in the job-posting dataset?

**### Geography**

\> Which countries have the largest concentration of data-job postings?

**### Remote Work**

\> What proportion of job postings offer work-from-home opportunities?

**### Education**

\> Which job titles have a greater proportion of postings without an explicit degree mention?

**### Trends**

\> How has the volume of job postings changed over time?

**### Employment Type**

\> Which job schedule types are most common in the dataset?

**# 🧠 Analytical Approach**

The project follows a typical business intelligence workflow:

\`\`\`text

Raw Job-Posting Data

        ↓

Data Preparation

        ↓

Data Transformation

        ↓

Power BI Data Model

        ↓

Measures & Aggregations

        ↓

Exploratory Analysis

        ↓

Interactive Visualizations

        ↓

Dashboard

        ↓

Business Insights

\`\`\`

The report uses aggregation and comparison techniques such as:

\* Count of job postings

\* Median salary

\* Salary aggregation

\* Percentage distributions

\* Time-series analysis

\* Geographic analysis

\* Category comparisons

**# 🎨 Dashboard Design**

The report uses a multi-page dashboard structure to separate different analytical perspectives.

The design emphasizes:

\* Clear visual hierarchy

\* Interactive navigation

\* Consistent analytical dimensions

\* KPI-focused summaries

\* Comparative visualizations

\* Geographic exploration

\* Detailed drill-through analysis

The report also uses Power BI's native visualization capabilities together with a custom multi-information card visual.

**# 📁 Project Files**

The repository can be organized as follows:

\`\`\`text

Data-Jobs-PowerBI/

│

├── README.md

│

├── Power BI Project 1.pbi

│

├── dashboard.png

│

\# 🚀 How to Use

\### Option 1 — View the Interactive Dashboard

Use the published Power BI report:

[\*\*🔗 View Interactive Power BI Dashboard →\*\*]\(PASTE-YOUR-POWER-BI-LINK-HERE)

The interactive version allows users to:

\* Navigate between dashboard pages

\* Apply slicers

\* Filter job titles

\* Explore trends

\* Interact with charts

\* Use drill-through functionality

\* Explore geographic visualizations where supported

\### Option 2 — Open the PBIX File

If you have access to \*\*Power BI Desktop\*\*, download and open:

\`\`\`text

Power BI Project 1.pbix

\`\`\`

You can then explore the report locally and inspect its data model, transformations, measures, and visualizations.

**# 💡 Potential Extensions**

Future versions of the project could expand the analysis by adding:

\* Job seniority analysis

\* Industry/company analysis

\* Skills demanded by job title

\* SQL/Python/Excel/Power BI skill requirements

\* Experience requirements

\* Salary distribution rather than only median salary

\* Company-level salary comparisons

\* Remote vs. on-site salary comparisons

\* Job-title growth rates

\* Interactive salary benchmarks

\* Automated data refresh

\* More advanced DAX measures

\* A dedicated executive summary page

**# 🎓 Skills Demonstrated**

This project demonstrates practical skills in:

\* **\*\*Microsoft Power BI\*\***

\* **\*\*Power Query\*\***

\* **\*\*DAX\*\***

\* **\*\*Data visualization\*\***

\* **\*\*Exploratory data analysis\*\***

\* **\*\*Business intelligence\*\***

\* **\*\*Dashboard development\*\***

\* **\*\*KPI design\*\***

\* **\*\*Time-series visualization\*\***

\* **\*\*Geospatial visualization\*\***

\* **\*\*Interactive reporting\*\***

\* **\*\*Data storytelling\*\***

\* **\*\*Drill-through analysis\*\***

\* **\*\*Data-driven decision support\*\***

**# 👤 Author**

**\*\*Nafizur Rahaman\*\***

Finance | Data Analytics | FinTech | Quantitative Research

This project reflects an interest in combining **\*\*financial/business knowledge with data analytics and visualization\*\*** to transform raw data into actionable insights.

**## ⭐ Project Purpose**

This project was created as part of a practical data analytics portfolio to demonstrate the ability to:

\> **\*\*Transform raw job-market data into an interactive business intelligence dashboard that supports exploration, comparison, and data-driven decision-making.\*\***

**## 📜 License**

This project is intended for educational and portfolio purposes.

The licensing status of the underlying dataset should be verified separately before redistribution or commercial use.
