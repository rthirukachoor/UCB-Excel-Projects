# Kickstarting with Excel

## Overview of Project
To help the upcoming playwright "Louise" who wants to start the crowdfunding compaign anlayze the Kickstarter data. The analysis will give her the insight on various compaigns and to understand various factors that 
wil help her to mirror her compaign to other successfull ones in the same category.

### Purpose
The main objective of the project to provide Louis about the compaign outcomes based on their launch dates and their funding goals. She understood with her intial analysis that the play "Fever" came close to its fundraising goal in a short amount of time. She would like to know how different compaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges
    The requirement of this analysis is to find the following:
    1. Outcomes based on Launch Date:
        This KPI was derived using excel Pivot Tables and a Line Chart to derive and visualize compaign outcomes ("successfull", "failed" and "canceled") based on the launch date.
        The pivot table provides the details on the total compaign outcomes of each category month wise. Also, it had the capability to filter by parent category and by each year.        

    2. Outcomes based on Goal Chart:
        This KPI is shown in the line chart to visualize the relationship between outcomes and launch month

    Challenges:
    1. To derive the month from "Data Created" field
    2. To decide the kind of chart that could provide the easy visualiation of relationship between outcomes and launch month

### Analysis of Outcomes Based on Launch Date
    1. It could be inferred from the Line chart that the compaigns that started in the month of May had the most success stories and started decreasing gradually from there on.
    2. Least number of campaign failed in November and most number in May
    3. Interesting to note that the most number of Success and failed campaigns happened in the month of May
    4. The number of canceled campaigns remains almost the same throught the year (on a average of 3)
    Please refer to the below link that supports my analysis
    https://github.com/rthirukachoor/UCB-Excel-Projects/blob/main/Theater_Outcomes_vs_Launch.png

### Analysis of Outcomes Based on Goals
    1. The lower the goal amount the higher the chances of success. When the goal amount is less than 1000, the chance of success is around 75%
    2. Similarly, the higher the goal amount the lower are the chances of success. For eg: When the goal amount $45K to $50k, there was 0% success rate
    Please refer to the below link that supports my analysis.
    https://github.com/rthirukachoor/UCB-Excel-Projects/blob/main/Outcomes_vs_Goals.png

### Challenges and Difficulties Encountered
    1. To decide on the type of graph that would help to visualize the required KPI's
    2. To dervie the insights from the data


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. It could be inferred from the Line chart that the compaigns that started in the month of May had the most success stories and started decreasing gradually from there on.
    2. Least number of campaign failed in November and most number in May
    3. Interesting to note that most number of Success and failed campaigns happened in the month of May
    4. The number of canceled campaigns remains almost the same throught the year (on a average of 3)

- What can you conclude about the Outcomes based on Goals?
    1. The lower the goal amount the higher the chances of success. When the goal amount is less than 1000, the chance of success is around 75%
    2. Similarly, the higher the goal amount the lower are the chances of success. For eg: When the goal amount $45K to $50k, there was 0% success rate

- What are some limitations of this dataset?
1. Analysis of each comapaign over the years cannot be dervied as the dataset provides data for only one year for each compaign.
2. Analysis based on the individual states for each country cannot be dervied as the dataset is based on the country level

- What are some other possible tables and/or graphs that we could create?
1. stacked bar chart that could show the outcome categories (successful, failed, canceled) for each month
2. Box and Whisker plot to find the outliers that could not eliminate from the analysis
3. Pie chart for each category across all countries(eg: one pie chart to show only success rate across all countries)






