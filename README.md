# Kickstarter-Analysis
Performing analysis on Kickstarter to uncover trends
# Kickstarting with Excel
## Overview of Project

This is an enalytical project on the crowdfunding campaigns in Kickstarter platform
### Purpose
	The purpose of this project is to help Louise better understand the Kickstarter project failure or success based on multiple categories and conditions.
One of these conditions was the relationship between the Outcomes and Goals set.

## Analysis and Challenges
I performed my Analysis using Excel program on data gathered from Crowndfunding projects on Kickstarter platform. I used multiple excel techniques such as sorting, filtering, pivot table and charts to perform data validation, cleaning, and visualizations.
One of the challenges I had was in the deliverable 2 pivot chart. The results of my filtering using (Countifs) function is some what different than the graph depicted in the question. I went ahead and verified that the functions I used were correct and the results of the filter matched the data set.
for example, to verify the result of countif function to find the number of failed project that had goals less than $35,000, I filtered the original data set for failed outcomes and I filtered the goals less than 35,000 and did a selection and count of the number of rows and verified the result matched the result of my countif formula.
I am still not sure what is the reason for difference between the line charts.
here is the countifs function I used to find number of failed outcomes with goals less than $1,000.( =COUNTIFS(Kickstarter!D:D, "<1000", Kickstarter!F:F, "failed"))
	

### Analysis of Outcomes Based on Launch Date
By using a pivot table and pivot chart, I realized that there was more successful outcomes for the campaigns that had a lunch date in May-July and there was 50-50 chance of failure for the month of December(37 success and 35 failure). This clearly shows that the failure rates for theater projects which started at the month of December are about 50 percent.


### Analysis of Outcomes Based on Goals

Campaigns that had goals less than $1,000, had the highest sucess rate. The campaigns with goals greater than $ 50,000 had the highest failure and cancelation rates.


### Challenges and Difficulties Encountered

I observed an anomoly for the project which had a goal between $10,000 and $15,000 which had an unexpected failure and cancelation rates compared to other projects with closer goals.	
some of the columns with the data set was not clear for me. for example, I do not have a good understanding for Spotlight column
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
theaters that had a lunch date of December had the highest failure rate.
theaters that had a lunch date of May to July, had the highest sucess rates.

- What can you conclude about the Outcomes based on Goals?

the highest sucess rate belongs to the projects which had a goal less than $1,000. the lowest success rate belongs to the project with a goal greater than $5,000.

- What are some limitations of this dataset?
This data set has no information on the states of the campaigns and it only lists the country.
some of the columns with the data set was not clear for me. for example, I do not have a good understanding for Spotlight column

- What are some other possible tables and/or graphs that we could create?
we can also create another pivot table to show the corrolation between different categories and their total rates of success and failures to find which category had the highest and lowest success rates.
Also we can create another analysis to find the relationship between different categories and the goals

