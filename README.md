Trying out excel for first time

# Dataset

The dataset used contains real-world information about data science job postings from 2023. It was made publicly available by Luke Barousse: 
lukebarousse.com

# Known Issue: Chart Lag with Filter Changes

There's many problems but this is the most troublesome one

Issue: While the spilled array formulas update correctly in the cells, the charts sometimes fail to reflect the latest filtered data unless the same filter is reselected again.

I think this problem is due to my using a dynamic array for my chart which causes:
- Charts don’t always respond instantly to dynamic spilled arrays
- They can lag behind data changes, especially when using dropdown filters or handling large datasets

As a result, the chart may only **partially update**, or **not display all expected values** until the filter is reapplied
This problem won't occur if there is only a few data in the array but the more data it has, the more likely to encounter this issue

Workaround: Re-selecting the same filter value again would allow the chart to display correctly.

