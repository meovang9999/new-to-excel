# Data Analyst Job Market Dashboard (Excel)
This is just me trying out what I just learned about Excel

In this project, I focused on using only basic Excel features:
- Charts – for visualizing salary distribution
- Formulas and Functions – to calculate things like median salary and job counts,...
- Data Validation – to build interactive filters
No pivot table, macro or advanced tools were used

# Dataset

The dataset used contains real-world information about data science job postings from 2023. It was made publicly available by Luke Barousse: 
lukebarousse.com

# Known Issue: Chart Lag with Filter Changes

In this project, I've encountered many problems but this is the most troublesome one

Issue: While the spilled array formulas update correctly in the cells, the charts sometimes fail to reflect the latest filtered data unless the same filter is reselected again.

I think this problem is due to my using a dynamic array for my chart which causes:
- Charts don’t always respond instantly to dynamic spilled arrays
- They can lag behind data changes, especially when using dropdown filters or handling large datasets

As a result, the chart may only **partially update**, or **not display all expected values** until the filter is reapplied
This problem won't occur if there is only a few data in the array but the more data it has, the more likely to encounter this issue

Workaround: Re-selecting the same filter value again would allow the chart to display correctly.

