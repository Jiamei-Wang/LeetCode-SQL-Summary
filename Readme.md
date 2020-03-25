# LeetCode SQL Summary

## Intro

After finishing all 102 Leetcode SQL questions, I feel the urge to summarize them by topics they are trying to test. 

This note aims to **help people _learn and review SQL effeciently_**, espeically when trying to **have a quick catch up on a certain topic**, e.g. complex join, window function, recursive CTE and etc.

And for the first draft, I mainly focus on **_T-SQL/MS SQL Server_**.

## LeetCode SQL Questions by Topcis


### Basics

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 182 | [Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | Easy | [Soln.](../master/Basics/182_Duplicate_Emails.sql) |
| 511 | [Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | Easy | [Soln.](../master/Basics/511_Game_Play_Analysis_I.sql) |
| 578 | [Get Highest Answer Rate Question](https://leetcode.com/problems/get-highest-answer-rate-question/) | Medium | [Soln.](../master/Basics/578_Get_Highest_Answer_Rate_Question.sql) | 
| 584 | [Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | Easy | [Soln.](../master/Basics/584_Find_Customer_Referee.sql) | 

### SQL Command

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 196 | [Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | [Soln.](../master/SQL-Command/196_Delete_Duplicate_Emails.sql) |

### Join


- Simple Join

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 175 | [Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | Easy | [Soln.](../master/Join/Simple-Join/175_Combine_Two_Tables.sql) |
| 181 | [Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Easy | [Soln.](../master/Join/Simple-Join/181_Employees_Earning_More_Than_Their_Managers.sql) |
| 183 | [Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | [Soln.](../master/Join/Simple-Join/183_Customers_Who_Never_Order.sql) |
| 184 | [Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | [Soln.](../master/Join/Simple-Join/184_Department_Highest_Salary.sql) |
| 197 | [Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | [Soln.](../master/Join/Simple-Join/197_Rising_Temperature.sql) |
| 262 | [Trips and Users](https://leetcode.com/problems/trips-and-users/) | Hard | [Soln.](../master/Join/Simple-Join/262_Trips_and_Users.sql) |
| 512 | [Game Play Analysis II](https://leetcode.com/problems/game-play-analysis-ii/) | Easy | [Soln.](../master/Join/Simple-Join/512_Game_Play_Analysis_II.sql) |
| 550 | [Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | [Soln.](../master/Join/Simple-Join/550_Game_Play_Analysis_IV.sql) |
| 570 | [Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | [Soln.](../master/Join/Simple-Join/570_Managers_with_at_Least_5_Direct_Reports.sql) |
| 574 | [Winning Candidate](https://leetcode.com/problems/winning-candidate/) | Medium | [Soln.](../master/Join/Simple-Join/574_Winning_Candidate.sql) |
| 577 | [Employee Bonus](https://leetcode.com/problems/employee-bonus/) | Easy | [Soln.](../master/Join/Simple-Join/577_Employee_Bonus.sql) |
| 580 | [Count Student Number in Departments](https://leetcode.com/problems/count-student-number-in-departments/) | Medium | [Soln.](../master/Join/Simple-Join/580_Count_Student_Number_in_Departments.sql) | 



- Advanced Join 



| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 180 | [Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | [Soln.](../master/Join/Advanced-Join/180_Consecutive_Numbers.sql) |
| 196 | [Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | [Soln.](../master/Join/Advanced-Join/196_Delete_Duplicate_Emails.sql) |
| 534 | [Game Play Analysis III](https://leetcode.com/problems/game-play-analysis-iii/) | Medium | [Soln.](../master/Join/Advanced-Join/534_Game_Play_Analysis_III.sql) |
| 569 | [Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) | Hard | [Soln.](../master/Join/Advanced-Join/569_Median_Employee_Salary.sql) |
| 579 | [Find Cumulative Salary of an Employee](https://leetcode.com/problems/find-cumulative-salary-of-an-employee/) | Hard | [Soln.](../master/Join/Advanced-Join/579_Find_Cumulative_Salary_of_an_Employee.sql) |






### Subquery

- Simple Subquery

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 176 | [Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Easy | [Soln.](../master/Subquery/Simple-Subquery/176_Second_Highest_Salary.sql)|
| 183 | [Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | [Soln.](../master/Subquery/Simple-Subquery/183_Customers_Who_Never_Order.sql) |
| 184 | [Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | [Soln.](../master/Subquery/Simple-Subquery/184_Department_Highest_Salary.sql) |
| 196 | [Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | [Soln.](../master/Subquery/Simple-Subquery/196_Delete_Duplicate_Emails.sql) |
| 197 | [Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | [Soln.](../master/Subquery/Simple-Subquery/197_Rising_Temperature.sql) |
| 512 | [Game Play Analysis II](https://leetcode.com/problems/game-play-analysis-ii/) | Easy | [Soln.](../master/Subquery/Simple-Subquery/512_Game_Play_Analysis_II.sql) |
| 569 | [Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) | Hard | [Soln.](../master/Subquery/Simple-Subquery/569_Median_Employee_Salary.sql) |
| 570 | [Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | [Soln.](../master/Subquery/Simple-Subquery/570_Managers_with_at_Least_5_Direct_Reports.sql) |
| 571 | [Find Median Given Frequency of Numbers](https://leetcode.com/problems/find-median-given-frequency-of-numbers/) | Hard | [Soln.](../master/Subquery/Simple-Subquery/571_Find_Median_Given_Frequency_of_Numbers.sql) |
| 574 | [Winning Candidate](https://leetcode.com/problems/winning-candidate/) | Medium | [Soln.](../master/Subquery/Simple-Subquery/574_Winning_Candidate.sql) |
| 579 | [Find Cumulative Salary of an Employee](https://leetcode.com/problems/find-cumulative-salary-of-an-employee/) | Hard | [Soln.](../master/Subquery/Simple-Subquery/579_Find_Cumulative_Salary_of_an_Employee.sql) | 
| 580 | [Count Student Number in Departments](https://leetcode.com/problems/count-student-number-in-departments/) | Medium | [Soln.](../master/Subquery/Simple-Subquery/580_Count_Student_Number_in_Departments.sql) | 


-  Advanced Subquery

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 262 | [Trips and Users](https://leetcode.com/problems/trips-and-users/) | Hard | [Soln.](../master/Subquery/Advanced-Subquery/262_Trips_and_Users.sql) |
| 550 | [Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | [Soln.](../master/Subquery/Advanced-Subquery/550_Game_Play_Analysis_IV.sql) |
| 569 | [Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) | Hard | [Soln.](../master/Subquery/Advanced-Subquery/569_Median_Employee_Salary.sql) |




-  Recursive CTE

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|




### Window Function

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 176 | [Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Easy | [Soln.](../master/Window-Function/176_Second_Highest_Salary.sql) |
| 177 | [Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | [Soln.](../master/Window-Function/177_Nth_Highest_Salary.sql) |
| 178 | [Rank Scores](https://leetcode.com/problems/rank-scores/) | Medium | [Soln.](../master/Window-Function/178_Rank_Scores.sql) |
| 180 | [Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | [Soln.](../master/Window-Function/180_Consecutive_Numbers.sql) |
| 184 | [Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | [Soln.](../master/Window-Function/184_Department_Highest_Salary.sql) |
| 185 | [Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/) | Hard |  [Soln.](../master/Window-Function/185_Department_Top_Three_Salaries.sql) |
| 197 | [Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | [Soln.](../master/Window-Function/197_Rising_Temperature.sql) |
| 512 | [Game Play Analysis II](https://leetcode.com/problems/game-play-analysis-ii/) | Easy | [Soln.](../master/Window-Function/512_Game_Play_Analysis_II.sql) |
| 534 | [Game Play Analysis III](https://leetcode.com/problems/game-play-analysis-iii/) | Medium | [Soln.](../master/Window-Function/534_Game_Play_Analysis_III.sql) |
| 550 | [Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | [Soln.](../master/Window-Function/550_Game_Play_Analysis_IV.sql) |
| 569 | [Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) | Hard | [Soln.](../master/Window-Function/569_Median_Employee_Salary.sql) |
| 571 | [Find Median Given Frequency of Numbers](https://leetcode.com/problems/find-median-given-frequency-of-numbers/) | Hard | [Soln.](../master/Window-Function/571_Find_Median_Given_Frequency_of_Numbers.sql) |
| 579 | [Find Cumulative Salary of an Employee](https://leetcode.com/problems/find-cumulative-salary-of-an-employee/) | Hard | [Soln.](../master/Window-Function/579_Find_Cumulative_Salary_of_an_Employee.sql) | 


### CASE WHEN

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 262 | [Trips and Users](https://leetcode.com/problems/trips-and-users/) | Hard | [Soln.](../master/CASE-WHEN/262_Trips_and_Users.sql) |


### OFFSET FETCH

| **#** | **Title** | **Difficulty** | **Solution** | 
|---|---|---|---|
| 176 | [Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Easy | [Soln.](../blob/master/OFFSET-FETCH/176_Second_Highest_Salary.sql) |
| 177 | [Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | [Soln.](../master/OFFSET-FETCH/177_Nth_Highest_Salary.sql) |




## LeetCode SQL Questions by ID

 **#** | **Title** | **Difficulty** | **Solution** |
|---|---|---|---|
| 175 | [Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | Easy | [Soln.](../master/Questions_by_ID/175_Combine_Two_Tables.sql) |
| 176 | [Second Highest Salary](https://leetcode.com/problems/second-highest-salary/) | Easy | [Soln.](../master/Questions_by_ID/176_Second_Highest_Salary.sql) |
| 177 | [Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/) | Medium | [Soln.](../master/Questions_by_ID/177_Nth_Highest_Salary.sql) |
| 178 | [Rank Scores](https://leetcode.com/problems/rank-scores/) | Medium | [Soln.](../master/Questions_by_ID/178_Rank_Scores.sql) |
| 180 | [Consecutive Numbers](https://leetcode.com/problems/consecutive-numbers/) | Medium | [Soln.](../master/Questions_by_ID/180_Consecutive_Numbers.sql) |
| 181 | [Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | Easy | [Soln.](../master/Questions_by_ID/181_Employees_Earning_More_Than_Their_Managers.sql) |
| 182 | [Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | Easy | [Soln.](../master/Questions_by_ID/182_Duplicate_Emails.sql) |
| 183 | [Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | Easy | [Soln.](../master/Questions_by_ID/183_Customers_Who_Never_Order.sql) |
| 184 | [Department Highest Salary](https://leetcode.com/problems/department-highest-salary/) | Medium | [Soln.](../master/Questions_by_ID/184_Department_Highest_Salary.sql) |
| 185 | [Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/) | Hard | [Soln.](../master/Questions_by_ID/185_Department_Top_Three_Salaries.sql) |
| 196 | [Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | Easy | [Soln.](../master/Questions_by_ID/196_Delete_Duplicate_Emails.sql) |
| 197 | [Rising Temperature](https://leetcode.com/problems/rising-temperature/) | Easy | [Soln.](../master/Questions_by_ID/197_Rising_Temperature.sql) |
| 262 | [Trips and Users](https://leetcode.com/problems/trips-and-users/) | Hard | [Soln.](../master/Questions_by_ID/262_Trips_and_Users.sql) |
| 511 | [Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | Easy | [Soln.](../master/Questions_by_ID/511_Game_Play_Analysis_I.sql) |
| 512 | [Game Play Analysis II](https://leetcode.com/problems/game-play-analysis-ii/) | Easy | [Soln.](../master/Questions_by_ID/512_Game_Play_Analysis_II.sql) |
| 534 | [Game Play Analysis III](https://leetcode.com/problems/game-play-analysis-iii/) | Medium | [Soln.](../master/Questions_by_ID/534_Game_Play_Analysis_III.sql) |
| 550 | [Game Play Analysis IV](https://leetcode.com/problems/game-play-analysis-iv/) | Medium | [Soln.](../master/Questions_by_ID/550_Game_Play_Analysis_IV.sql) |
| 569 | [Median Employee Salary](https://leetcode.com/problems/median-employee-salary/) | Hard | [Soln.](../master/Questions_by_ID/569_Median_Employee_Salary.sql) |
| 570 | [Managers with at Least 5 Direct Reports](https://leetcode.com/problems/managers-with-at-least-5-direct-reports/) | Medium | [Soln.](../master/Questions_by_ID/570_Managers_with_at_Least_5_Direct_Reports.sql) |
| 571 | [Find Median Given Frequency of Numbers](https://leetcode.com/problems/find-median-given-frequency-of-numbers/) | Hard | [Soln.](../master/Questions_by_ID/571_Find_Median_Given_Frequency_of_Numbers.sql) |
| 574 | [Winning Candidate](https://leetcode.com/problems/winning-candidate/) | Medium | [Soln.](../master/Questions_by_ID/574_Winning_Candidate.sql) |
| 577 | [Employee Bonus](https://leetcode.com/problems/employee-bonus/) | Easy | [Soln.](../master/Questions_by_ID/577_Employee_Bonus.sql) |
| 578 | [Get Highest Answer Rate Question](https://leetcode.com/problems/get-highest-answer-rate-question/) | Medium | [Soln.](../master/Questions_by_ID/578_Get_Highest_Answer_Rate_Question.sql) | 
| 579 | [Find Cumulative Salary of an Employee](https://leetcode.com/problems/find-cumulative-salary-of-an-employee/) | Hard | [Soln.](../master/Questions_by_ID/579_Find_Cumulative_Salary_of_an_Employee.sql) | 
| 580 | [Count Student Number in Departments](https://leetcode.com/problems/count-student-number-in-departments/) | Medium | [Soln.](../master/Questions_by_ID/580_Count_Student_Number_in_Departments.sql) | 
| 584 | [Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | Easy | [Soln.](../master/Questions_by_ID/584_Find_Customer_Referee.sql) | 
