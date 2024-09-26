# Knowledge check

200 XP  
5 minutes

1. You must return a list of all sales employees that have taken sales orders. Employees who have not taken sales orders should not be included in the results. Which type of join is required? 

    - [ ] INNER
    - [ ] LEFT OUTER
    - [ ] FULL OUTER

2. Which type of JOIN operation does not require an ON clause? 

    - [ ] LEFT OUTER JOIN
    - [ ] CROSS JOIN
    - [ ] FULL JOIN

3. You write the following query: SELECT p.Name, c.Name FROM Store.Product AS p CROSS JOIN Store.Category AS c; What does the query return? 

    - [ ] Only data rows where the product name is the same as the category name
    - [ ] Only rows where the product name is not the same as the category name
    - [ ] Every combination of product and category name

---
__SPOILER ALERT__

## Solutions to Knowladge check

1. You must return a list of all sales employees that have taken sales orders. Employees who have not taken sales orders should not be included in the results. Which type of join is required? 

    - [x] INNER
    - [ ] LEFT OUTER
    - [ ] FULL OUTER

2. Which type of JOIN operation does not require an ON clause? 

    - [ ] LEFT OUTER JOIN
    - [ ] CROSS JOIN
    - [x] FULL JOIN

3. You write the following query: SELECT p.Name, c.Name FROM Store.Product AS p CROSS JOIN Store.Category AS c; What does the query return? 

    - [ ] Only data rows where the product name is the same as the category name
    - [ ] Only rows where the product name is not the same as the category name
    - [x] Every combination of product and category name
