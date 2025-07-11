# Data Analyst Job Market Dashboard (Excel)

This is my first time using Excel, and this dashboard is also my very first Excel project. I created it to apply the skills I’ve just learned.

# Project Purpose
This project was created as a way for me to apply and reinforce what I’ve recently learned in Excel. It focuses on building a functional and insightful dashboard using only core Excel features.

# Skills Demonstrated

In this project, I focused on using only basic Excel features:

- 📈 **Charts** – for visualizing salary distribution
- 📋 **Formulas and Functions** – to calculate things like median salary and job counts,...
- ✅ **Data Validation** – to build interactive filters

No pivot table, macro or advanced tools were used — this project is all about mastering the basics while trying to deal with a large number of data

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


Thank you for visiting! Feel free to explore, fork the project, or share feedback.

