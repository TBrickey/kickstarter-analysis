# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
## Overview of Project

Your client, Louise, is an up-and-coming playwright. She wants to start a crowdfunding campaign for her play, Fever. She estimates needing $10,000.

### Purpose

Using excel we’ll help organize, filter, sort and analyze crowdfunding data. We’ll need to determine what factors make a campaign successful to help Louise set up her own crowdfunding campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Utilizing Excel pivot tables and graphs gives us the ability to count the number of successful, failed, and canceled campaigns by month while isolate on the Parent Category: Theater. This technique better illustrates the connection between the campaigns viability and launch date.

(https://github.com/TBrickey/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

We used the COUNTIFS () function in Excel and calculated the percentage of successful, failed, and canceled plays based on a funding goal amount range. The graph helps in visualizing percentage successful and failed in Louise’s estimate goal range. 

(https://github.com/TBrickey/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

It was challenging reviewing the ‘The Outcomes Based on Goals’ graph. I felt the graph misrepresented goal outcomes between 30k to 45k due to using percentages with lower project totals. Using Nesting COUNTIFS () for 84 cells was very tedious and getting zeros for “Number” and “Percentage Canceled” made me second guess my functions.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Conclusion 1, Theater has a higher successful outcome that failed and cancelled combined.
Conclusion 2, starting a campaign in May increased Louise’s likelihood for success without much increase to a failed outcome.

- What can you conclude about the Outcomes based on Goals?

The smaller goals have a higher number and percentage or successful outcomes.

- What are some limitations of this dataset?

‘Outcomes Based on Launch Date’ graph, filtering on Theater, which included plays but also brought up musical and spaces. ‘The Outcomes Based on Goals’ graph misrepresented goal outcomes between 30k to 45k due to using percentages with lower project totals. 

- What are some other possible tables and/or graphs that we could create?

We could have ‘The Outcomes Based on Goals’ graph with ranges of 1000 at a time, show percentage and totals, and ignore data with goals over 20k. 
