# Pewlett-Hackard-Analysis
### Programs Used:
- pgAdmin 4
- Quick DBD
- Visual Studio Code
- .csv, .sql and .png files

## Overview
The Pewlett-Hackard Analysis seeks to conduct a generalized HR analysis of the current population of employees working at the Pewlett-Hackard company. As many of the senior members reach their retirement age, we want to find out not only the precise number of those who are retiring and eligible for retirement packages, but also what their present titles are within the company so that proper replacements can be found for the future absence.

## Deliverable 1

### Results
![retiring_titles](https://user-images.githubusercontent.com/107447038/183345650-c552b421-f553-41f4-adf9-e79e9435b5ed.png)

1. The analysis returned 90398 results of members eligible for retirement.
2. It was constructed of four columnn keys: emp_no, first_name & last_name, and title.
3. Analysis shows that a large number of senior engineers will be retiring in the coming years.
4. In sharp contrast, there are only two managers who will be retiring in the coming years. 


## Deliverable 2
### Results
1. The mentorship eligibility csv was constructed of seven different column keys: emp_no, first_name & last_name, birth_date, from_date & to_date (employment) and title.
2. It returned a total of 1550 lines (1499 not including the key).
3. Senior staff and senior engineer were the titles most eligible for mentorship. 
4. Assistant engineers was the title with least eligibile numbers for mentorship.

## Summary 
### Additional Queries

Two additional queries I wanted to make were:

1. What are the title distributions for the mentorship eligibility? and-
2. What are the overall population distribution for the different titles?

These questions are relevant to this analysis as the title distribution of those who are eligible for mentorship should, in theory, match the overall distribution of titles in the company, and for the best benefits of the company, also match the count of those who are retiring, as suitable replacements are guaranteed to be on their way. The results were the following:

Mentorship Eligibility Title Count:

![mentorship_eligibility_titles](https://user-images.githubusercontent.com/107447038/183346110-631939fd-30fe-4b51-a2bf-ed51790112aa.png)

Titles Count:

![titles_count](https://user-images.githubusercontent.com/107447038/183346103-9d1f6279-fc37-4bb4-ac11-b25c85b09865.png)

### Conclusion
Senior staff and senior engineer are prevalent in the count of those who are retiring as well as those who are eligible to receive mentorships. While there will still need to be new hires to fill these positions, loyal employees of the Pewlett-Hackard company who are currently active can receive mentorship to fill many of the positions that will go empty with the incoming wave of retirement. 
