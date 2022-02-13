# Pewlett-Hackard-Analysis
## Project Overview
The purpose of this project is to perform analysis on a large-scale of employee data for a company by the name of Pewlett Hackard (PH) by helping their Human Resource team analyze thier concern for retiring population and solicit future leaders as mentors to replace the aging population. 

## Results/Analysis
### Below are several of my findings:
* After creating the unique_titles table by joining the employees and titles tables, filtering them by date of birth and date hired, removing duplicates, and ordering the data points by date hired there are 90,398 employees retiring as per the above criterion.

### Out of those employees retiring, below is the breakdown by titles:
* 29,414 Senior Engineers 
* 28,254 Senior Staff
* 14,222 Engineers
* 12,243 Staff
* 4,502 Technique Leaders
* 1,761 Assistant Engineers
* 2 Managers.

### Mentorship Eligibility
* Created the mentorship_eligibility table by joining the employees, department employees, and titles tables. In this case, the criterion for the join was that the employees were born in 1965 and that they were currently working at PH, in order for them to apply to the retiring/mentorship package. There were **1,549** employees eligible.

## Summary
* Ideally, as Silver Tsunami approaches the idea to prepare and be on the look for **13,505** employees. This number represents the number of people that are currently working at the company, have been there since 1985 to 1988, and their birth date is between 1962 and 1965 to be eligible to leave work. The plan is to offer these people the mentorship program so that they can keep mentoring new employees. However, if they decide to go PH should be ready to hire that amount of people.
* In conclusion, it all depends on how many retiring employees are willing to stay and mentor others. Nevertheless, **a good mentor to mentee ratio I would say is 1:3.** That is one mentor for 3 new employees. Assuming each year, there are more or less 13,000 employees retiring and about 13,000 new employees entering, they would need 3,000-4,000 mentors distributed proportionally in all the departments. Thus, to stay put, at least **25%** of the retirees accept the mentorship program.

