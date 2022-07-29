# Pewlett-Hackard-Analysis

## Overview
Pewlett Hackard has asked me to review their employee files and gather some information regarding a possible large wave of retirements within the company known as a "silver tsunami" which would leave Pewlett Hackard with a vast amount of vacant positions. A database diagram was created to organize the data into tables. PostgresSQL was then used via pgAdmin to write queries using the Pewlett Hackard data to create data tables by joining the primary keys of different files and forming foreign keys. Queries were then written to generate lists of the employees that are eligible for retirement as well as a list of employees who can be mentored in a position that is likely to be vacated. 

## Results
1. The first list created compiled all of the potential retirees within Pewlett Hackard. Although this query generated many duplicate results because certain employees hold mulitple positions within the company.
2. After revising the first query using DISTINCT ON within SQL, the duplicates were eliminated by showing only the employee's most recent job title.

![Screen Shot 2022-07-28 at 11 06 03 PM](https://user-images.githubusercontent.com/108902185/181674527-3acbd679-26bf-4167-9cc8-3a5a2ca0baa5.png)
3. Another query was then made to display the distribution of potential retirees throughout each Job Title.

![Screen Shot 2022-07-28 at 11 08 44 PM](https://user-images.githubusercontent.com/108902185/181674941-fdbb1ab1-d112-470d-be1e-6ada2d62c4e8.png)
4. A final query was created to compile a list of all of the employees who are eligible to be mentored for a vacated position.

## Summary
1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  There are over 90,000 positions that are likely to be vacated via retirement.
2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  There are certainly enough mentors within Pewlett Hackard to train the mentiees within the company. However, there are only 1,549 possible employees credentialed to take their spot. 
