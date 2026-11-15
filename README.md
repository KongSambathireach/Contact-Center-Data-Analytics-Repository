# Contact-Center-Data-Analytics
A contact center analytics project focused on analyzing incoming call volume, service performance, customer waiting time, and operational demand using Microsoft Excel, Power Query, Power Pivot, and Power BI.

## Objectives
The objective of this project is to analyze call center operational performance through historical call volume data.

The analysis aims to understand incoming call patterns, evaluate service efficiency, identify peak demand periods, and provide actionable insights to support operational decision-making and workforce planning.

### Key Analytical Questions

- How many calls are offered, answered, and abandoned?
- What are the daily and monthly call volume trends?
- Which hours and intervals experience the highest call volume?
- What is the Average Speed of Answer (ASA)?
- What is the Service Level (SL)?
- What is the call abandonment rate?
- Are staffing levels sufficient to handle incoming demand?
- Which days and time intervals experience the worst service performance?

### Business Analytical Questions

- Why does call volume fluctuate across different days and time intervals?
- What factors contribute to increased call abandonment?
- How does peak-hour demand affect service performance?
- Is the current workforce capacity sufficient to meet customer demand?
- How much additional staffing capacity is required during peak periods?
- Which operational periods contribute most to poor Service Level performance?
- How does increased call volume affect customer waiting time?
- What are the main causes of declining Answer Rate and Service Level?\
- How can workforce scheduling be optimized to match incoming call patterns?
- What actions should management prioritize to improve service efficiency and customer experience?

## Four layer of Analysis

### Metrics (What do we measure?)

- Offered Calls =	Incoming call demand

- Answered = Calls	Calls handled by agents

- Abandoned Calls	= Calls disconnected before answering

- Answer Rate =	Percentage of calls answered

- Abandonment Rate = Percentage of calls abandoned

- ASA	= Average customer waiting time

- AHT	= Average call handling time

- Service Level =	Percentage of eligible calls answered within the target

- Peak Call Volume =	Highest incoming call demand


### Analytical Dimensions (How do we analyze it?)


| Dimension | Examples | What it Helps Identify |
|---|---|---|
| Date | Daily, weekly, monthly | Demand trends |
| Time | Hourly, 30-minute interval | Peak demand periods |
| Day of Week | Monday–Sunday | Weekly demand patterns |
| Queue | Voice, customer service, support | Demand by service |
| Shift | M1, M2, M3, E, X | Demand across shifts |
| Agent | Agent name or ID | Individual performance |
| Call Outcome | Answered, abandoned | Call distribution |
| Service Level Status | Within target, outside target | Service performance |


### Business Analytical Questions (What do we want to understand?)

|Business area |	Analytical question|
|---|---|
|Demand |	Why does call demand increase during certain periods? |
|Capacity	| Does available staffing match incoming call demand?|
|Service| Quality	Why does Service Level decline during peak periods?|
|Customer Experience	|How does waiting time influence call abandonment?|
|Workforce Planning|	Which shifts experience the greatest workload pressure?|
|Operational Efficiency	|Which periods have the largest gap between demand and service capacity?|
|Forecasting	| Can historical demand patterns predict future call volume?|


### Business Decisions (What actions should management take?)
This is where analytics becomes useful to the business.

|Finding from analysis|	Potential business decision|
|---|---|
|High demand between 09:00–10:00|	Adjust shift schedules to increase morning coverage|
|High abandonment during peak hours|	Review staffing and queue management|
|Low Service Level on Mondays|	Review Monday workforce allocation|
|Consistently high ASA	|Investigate staffing capacity and call handling efficiency|
|Uneven demand across shifts|	Redistribute staffing where operationally feasible|
|Recurring demand patterns	|Introduce call volume forecasting for workforce planning|

#### **Requirements** 

To run and reproduce this project, the following tools are required: 

- Microsoft Excel: Used for data exploration, formulas, PivotTables, and preliminary analysis.
- Power Query: Used for data cleaning, transformation, and automated data preparation.
- Power Pivot: Used for data modeling, relationships, and DAX calculations.
- Microsoft Power BI: Used for advanced data visualization, interactive reporting, and dashboard development.



## Exploratory Data Analysis (EDA)
Exploratory analysis focuses on identifying call volume patterns and understanding operational performance

### **Data Preparation**:

The raw dataset is imported and transformed to ensure data consistency and analytical accuracy.

- Key preparation activities include:
- Removing duplicate and invalid records.
- Handling missing or inconsistent values.
- Standardizing date and time formats.
- Creating date and time interval classifications.
- Aggregating call volume into 30-minute intervals.
- Preparing data for analysis and visualization.


### Analysis Areas

- Call Volume Trends: Daily, weekly, and monthly incoming call patterns.

- Interval Analysis: Call distribution across 30-minute intervals.

- Peak Hour Analysis: Identification of high-demand periods.

- Call Handling Performance: Answered calls, abandoned calls, and waiting times.

- Service Performance: Service Level, ASA, Answer Rate, and Abandonment Rate.


### Key Performance Indicators (KPIs)

| KPI | Description |
|---|---|
| Offered Calls | Total incoming calls offered to the contact center. |
| Answered Calls | Total calls successfully answered by agents. |
| Abandoned Calls | Total calls abandoned before being answered. |
| Answer Rate | Percentage of offered calls answered. |
| Abandonment Rate | Percentage of offered calls abandoned. |
| ASA (Average Speed of Answer) | Average waiting time before calls are answered. |
| AHT (Average Handling Time) | Average time spent handling answered calls. |
| Service Level (SL) | Percentage of eligible calls answered within the defined threshold. |


## Power BI Visualizations

The Power BI dashboard will provide an interactive overview of call center performance, enabling stakeholders to monitor operational KPIs, identify demand patterns, and evaluate service efficiency.

### Dashboard Components

| Dashboard | Description |
|---|---|
| Executive Overview | Provides an overview of total call volume, answered calls, abandoned calls, Answer Rate, and Service Level. |
| Call Volume Trends | Analyzes daily, weekly, and monthly call volume patterns. |
| Interval Analysis | Visualizes call distribution across 30-minute intervals to identify peak demand periods. |
| Service Level Monitoring | Tracks Service Level, ASA, and service performance trends over time. |
| Abandonment Analysis | Examines abandoned call volume, abandonment rates, and recurring abandonment patterns. |
| Peak Demand Analysis | Identifies high-volume periods and evaluates demand fluctuations across different days and intervals. |

## Expected Outcomes

By completing this project, the analysis aims to deliver the following outcomes:

- Develop a clear understanding of incoming call demand and volume patterns.
- Identify peak hours, high-demand intervals, and recurring demand trends.
- Evaluate service performance through Answer Rate, Abandonment Rate, ASA, and Service Level.
- Identify operational inefficiencies and potential service performance gaps.
- Understand the relationship between incoming call demand and available staffing capacity.
- Provide data-driven recommendations to improve workforce planning, resource allocation, and operational efficiency.

## Project Status

**Status:** In Development

### Development Roadmap

| Phase | Activities | Status |
|---|---|---|
| 01. Data Preparation | Import, clean, transform, and validate raw call data using Power Query. | Not Started |
| 02. Exploratory Data Analysis | Analyze call volume trends, distributions, and operational patterns using Excel. | Not Started |
| 03. Data Modeling | Build data models, relationships, and calculated measures using Power Pivot. | Not Started |
| 04. KPI Development | Define and implement contact center KPI calculations using DAX. | Not Started |
| 05. Power BI Development | Build interactive dashboards and operational reports. | Not Started |
| 06. Business Analysis | Interpret findings and develop data-driven business recommendations. | Not Started |


## Contact

**Kong Sambathireach**

- LinkedIn: [Your LinkedIn Profile](linkedin.com/in/kong-sambathireach-ab7305249/
- Email: ksambathireach@gmail.com
