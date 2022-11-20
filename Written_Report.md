# Kickstarting with Excel

## Overview of Project
The stakeholder requests to know how diferrent campaigns progress in relation to their launch dates and funding goals using the provided dataset.

### Purpose
Create visualize campaign outcomes based on their lauch dates and funding goals to evaluate the data trend.

## Analysis and Challenges
There were some challenges encountered when using the function COUNTIFS to pull the number of successful, failed and canceled projects for the "Outcomes based on Goal" analysis. The value pulled to 0 for all categories. However, after checking and further research of using "$" appropriately in the fomula, likely outcomes were achieved. 2 data graphs were created based on dataset and criteria provided.

### Analysis of Outcomes Based on Launch Date

Theater_Outcomes_vs_Launch.png

May has the highest number of successful projects while there is no correlation between the lauch date and the number or failed and canceled project.

### Analysis of Outcomes Based on Goals

Outcomes_vs_Goals.png

The two lines represent successful and failed number projects mirror each other exactly, while there is no line indicated canceled project.

### Challenges and Difficulties Encountered
Aside from challenge encountered when using the "$" in COUNTIF fuction, it took awhile to group the row labels column in pivot table for "Theater Outcomes based on launch date"  analysis to show the month of the year instead of quarters.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on an analysis, the month of May has the highest number of successful campaigns, and the number is relative high during summer months (May to August).However, there is no correlation between launch dates and the number of failed and cancelled campaigns.

- What can you conclude about the Outcomes based on Goals?
There is no play project got cancelled. Therefore, based on the datasets that we selected, outcomes were either failed our successful. 

- What are some limitations of this dataset?
This dataset only includes "play" projects while there are many categories can be potentially included for the analysis. Also, within the "play" category, there is data for "live" projects available but isn't included. This leads to "mirror" results in two lines, while the "cancelled" category is irrelevant. With a larger and better sample, we can get a better result for this analysis.

- What are some other possible tables and/or graphs that we could create?
Per limitation identified regarding the data sample, we can potentially create an "Outcomes based on Goal" graph includes "live" project instead of cancelled projects. We can also create an analysis of the goal versus the pledge amount to further evaluate the outcome of successful/failed project to identify the trend for future planning.