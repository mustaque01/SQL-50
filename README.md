# SQL 50 – LeetCode Progress

Profile: https://leetcode.com/u/mustak_11/

Quick log of daily solutions. Each file contains a single query that passes the corresponding LeetCode SQL 50 challenge. Run them directly in the LeetCode editor or in MySQL-compatible environments.

| Day | Problem | Idea | Solution |
| --- | --- | --- | --- |
| 1 | Recyclable and Low Fat Products | Filter rows where `low_fats = 'Y'` and `recyclable = 'Y'` | [day1.sql](day1.sql) |
| 2 | Find Customer Referee | Select customers whose `referee_id` is not 2 or is null | [day2.sql](day2.sql) |
| 3 | Big Countries | Keep countries with very large `area` or `population` | [day3.sql](day3.sql) |
| 4 | Article Views I | Authors who viewed their own articles, de-duplicated and ordered | [day4.sql](day4.sql) |
| 5 | Invalid Tweets | Tweet IDs where `content` length exceeds 15 | [day5.sql](day5.sql) |
| 6 | Employee Unique ID Mapping | Left join `Employees` with `EmployeeUNI` to list names lacking a mapped `unique_id` | [day6.sql](day6.sql) |
| 7 | Product Sales Analysis I | Join `Sales` with `Product` to show `product_name`, `year`, `price` | [day7.sql](day7.sql) |
| 8 | Customer Who Visited but Did Not Make Any Transactions | Count visits with no matching transaction per `customer_id` | [day8.sql](day8.sql) |
| 9 | Rising Temperature | Compare each day to the previous day and keep warmer days | [day9.sql](day9.sql) |
| 10 | Average Time of Process per Machine | Pair start/end events and average durations per `machine_id` | [day10.sql](day10.sql) |
| 11 | Employee Bonus | Left join bonuses and keep missing or sub-1000 bonuses | [day11.sql](day11.sql) |
| 12 | Students and Examinations | Cross join students/subjects and count exams taken for each pair | [day12.sql](day12.sql) |
| 13 | Managers with at Least 5 Direct Reports | Managers whose `managerId` appears 5+ times | [day13.sql](day13.sql) |
| 14 | Confirmation Rate | Confirmation ratio per user with null-safe division | [day14.sql](day14.sql) |

## Notes
- Dialect: MySQL-style SQL used by LeetCode.
- Feel free to extend the table as you add more days or swap in alternative solutions.
