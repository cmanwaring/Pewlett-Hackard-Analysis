# Pewlett Hackard Analysis
---

## Overview:
---
Bobby from Pewlett-Hackard would like for us to setup a database where we can import and house employee and department data. Furthermore, Bobby would like for us to calculate the number of employees by title that can be anticipated to be retiring soon. Bobby is considering starting up a mentorship program where employees that are going to retire soon can move to a part time position and mentor newer employees for their future with the company.

---
## Results:
 - We created a table (retirement_titles) with a list of employees born bwtween 1952-01-01 and 1955-12-31 to determine employees that would be eligible for retirement. CSV available here: [retirement_titles.csv](Data/retirement_titles.csv)  
 - From the retirement_titles table we created the unique_titles table that only contains each potential-retiree's most recent title. CSV available here: [unique_titles.csv](Data/unique_titles.csv)  
 - We then created the retiring_titles table where we counted how many potential-retirees there may be per job title.  
   ![Number Retiring by Title](Resources/retiring_titles.png)  
 - We then created a table (mentorship_eligibility) that lists employees that will be eligible for Bobby's upcoming mentorship program. CSV available here: [mentorship_eligibility.csv](Data/mentorship_eligibility.csv)  
 - I decided to go one step further to make Bobby's job a little easier, and I made a table (mentorship_eligibility_count) to count the number of potential mentors by job title.  
   ![mentorship_eligibility_count](Resources/mentorship_eligibility_count.png)  

---
## Summary:
With 90,398 employees approaching retirement, Bobby will need to get some measures in place to fill the newly available positions and train the new employees!




The written analysis has the following:
  - Overview of the analysis:
    -    
  - Results:
    - There is a bulleted list with four major points from the two analysis deliverables. (6 pt)
  - Summary:
--
--
--
--
--
--
As a reminder, the deliverables for this Challenge are as follows:

 - Deliverable 1: The Number of Retiring Employees by Title
 - Deliverable 2: The Employees Eligible for the Mentorship Program
 - Deliverable 3: A written report on the employee database analysis (README.md)

--
Analysis (14 points)
The written analysis has the following:
  - Overview of the analysis:
    - The purpose of the new analysis is well defined. (3 pt)    
  - Results:
    - There is a bulleted list with four major points from the two analysis deliverables. (6 pt)
  - Summary:
    - The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)

---
Mastery
 - ✓The purpose is well defined. 
 - ✓There is a bulleted list that addresses FOUR major results. 
 - ✓The summary addresses the TWO questions and contains TWO additional queries or tables.

