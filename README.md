# Insurance_Dashboard_PowerBI-

Dashboard Link: https://app.powerbi.com/groups/58b05ab5-654c-4f61-ade7-21b7f58db4b1/reports/0881e8c0-ff53-4ed2-b783-b5009904107a/74cba56cfdb4376baa24?experience=power-bi

Imported data from SQL database, transformed columns using Power Query Editor and tried to analyze the performance of 'Prism Insurance', through various metrics and provide insights for improvement.

This database comprised of 10004 rows of data across 12 columns. I added a conditional column to find out whether a particular policy was active/inactive, as on the current date.

I added a bar chart in the 1st page, which can be drilled through to the table on the 2nd page, providing the details of a particular insurance type. For example, if someone chooses health insurance in the bar chart, the table will show a list of all policy buyers with health insurance.

As you can see the following insights and suggestions can be provided to Prism Insurance for business improvements:

· Travel is the most bought insurance type and home is the least, so Prism should try to incentivise more people to try its travel insurance; a large portion of revenue comes from this category

· 71.7% are inactive policy holders, which is a cause of concern.

· A significant number of claims have been rejected, which isn't good from a company perspective. There may have been issues with understanding the terms and conditions among customers and this might lead to negative sentiment. Prism can try to make its claim process easier to retain customers.

I also ran a sentiment analysis using AI insights (text analytics) which quantifies the feedback of each customer regarding their insurance experience and summarized them in a bar chart. There is also an attached word cloud, which shows words have appeared frequently in feedbacks.

In addition, I also learnt to implement row-level security and schedule refresh of the data at specific intervals to update the visuals accordingly.
