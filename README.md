# kickstarter-analysis

##Overview of Project

1. Import excel data into a table and chart for an analysis.
2. Filter worksheet in descending order.
3. Select column for conditional formatting, which helps in easily reflecting and identifying grouped information.
4. Create pivot table and line chart for theatre outcomes. 
5. Create a table and line chart to display outcomes based on goals. 

##Purpose

  The purpose of this report is to examine the Kickstarter data and determine the theatre outcomes by launch date, as well as the outcomes based on goals. This will aid in decision making in terms of which theatre launch dates and goals for the plays will generate the best outcomes.

#Analysis and Challenges

##Analysis of Outcomes Based on Launch Date

  The data was filtered by the theatre category, showing the number of live monthly outcomes. Data is separated, depending on status (canceled, failed, and successful)


<img width="468" alt="image" src="https://user-images.githubusercontent.com/104689119/168200462-07759457-d85f-4755-a4db-712e6a45a54c.png">

##Analysis of Outcomes Based on Goals

  Based on the number of live outcomes, the data was filtered to reflect the goals under the plays subcategory. The total number of successful, failed and cancelled outcomes are calculated, which are then converted into percentages. 
  
  <img width="468" alt="image" src="https://user-images.githubusercontent.com/104689119/168200502-6fba198f-485e-48e7-a7dd-2a2cda5f1e03.png">

##Challenges and Difficulties Encountered

  Based on the formula, the correct information based on each cell needed to reflect the correct data. The problem was solved by ensuring that the formula captured the right information.
  
  The range was manually entered in the COUNTIF formula to properly account for information captured within each data range set. This problem was solved by making sure that the COUNTIFS functions within each cell, particularly those with minimum and maximum ranges, were written accurately.
	
##Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1. The successful months to launch a theatre are during May and June. The success rate significantly drops in the other months. 

2. Cancelled theaters, regardless of months, are minimal, in comparison to theatre plays that either succeed or fail.

- What can you conclude about the Outcomes based on Goals?

  Goals less than 5,000 had the highest success rate. Goals exceeding 45,000 had the highest failed rate. 

- What are some limitations of this dataset?

  No cancelled projects or examples of cancelled projects to alter the data 

- What are some other possible tables and/or graphs that we could create?

•	Tables 
  The report only specifies the possible outcomes based on goals. It might be more beneficial to display these different outcomes based on the actual amounts pledged to date, which is a more realistic view of how much has been raised. 
  
•	Graphs 
  Bar graphs to show comparing data, like the functionality of the line graph


