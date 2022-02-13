# Pewlett-Hackard-Analysis
## Project Overview
The purpose of this project is to perform analysis on a large-scale of employee data for a company by the name of Pewlett Hackard by helping their Human Resource team analyze thier concern for retiring population and solicit future leaders as mentors to replace the aging population. 

## Results/Analysis
## Below are several of my findings:
* After creating the unique_titles table by joining the employees and titles tables, filtering them by date of birth and date hired, removing duplicates, and ordering the data points by date hired there are 90,398 employees retiring as per the above criterion.
*
### Out of those employees retiring, below is the breakdown by titles:
* 29,414 Senior Engineers, 28,254 Senior Staff, 14,222 Engineers, 12,243 Staff, 4,502 Technique Leaders, 1,761 Assistant Engineers, and 2 Managers.
* 
### Mentorship Eligibility
Created the mentorship_eligibility table by joining the employees, department employees, and titles tables. In this case, the criterion for the join was that the employees were born in 1965 and that they were currently working at PH, in order for them to apply to the retiring/mentorship package. There were 1,549 employees eligible.
