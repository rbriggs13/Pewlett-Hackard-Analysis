# Pewlett-Hackard-Analysis
## Overview
The purpose of this analysis is to provide advice and preparation for the upcoming wave of employees expected to retire.
## Results
- There are 41,380 people retiring from the company.
- Managers are missing from the marketing, finance, development, and quality management departments.
- There are two managers retiring, but there are over 1,500 people that could be mentored to replace them.
- Senior engineers are the title that need the most people to replace those retiring at nearly 30,000.
## Summary
The following query returns how many employees are retiring indicating how many positions will need to be filled
```
SELECT COUNT (emp_no)
FROM retirement_info;
```
This query tells us that there are 41,380 roles that need to be filled. 
The following table shows the amount of employees that are retiring in each role.
![retirement_table](https://user-images.githubusercontent.com/87343629/136822914-2faa0e33-eb29-4cdf-8ab1-9eaa7afff69c.png)
As this table shows there are more than enough senior staff and engineers to mentor the next generation of employees.
