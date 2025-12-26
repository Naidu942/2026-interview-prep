## 1. Second Highest Salary - Easy
Find the second highest salary from an Employee table. Return null if there's no second highest.
```sql
Table: Employee
+----+--------+
| id | salary |
+----+--------+
```

## 2. Department Top Salaries - Medium
**Pattern:** JOIN + GROUP BY
Write a query to find employees who earn the top salary in each department.
```sql
Tables: Employee (id, name, salary, departmentId)
        Department (id, name)
```

## 3. Consecutive Numbers - Medium
**Pattern:** Self JOIN / Window Functions
Find all numbers that appear at least three times consecutively in a Logs table.
```sql
Table: Logs
+----+-----+
| id | num |
+----+-----+
```

## 4. User Activity for Last 30 Days - Medium
**Pattern:** Date Functions + Aggregation
Calculate the daily active users for a period ending 30 days before 2019-07-27.
```sql
Table: Activity (user_id, session_id, activity_date, activity_type)
```

## 5. Exchange Seats - Hard
**Pattern:** CASE WHEN / Window Functions
Swap the seat id of every two consecutive students. If odd number of students, last seat remains unchanged.
```sql
Table: Seat (id, student)
+----+---------+
| id | student |
+----+---------+
| 1  | Abbot   |
| 2  | Doris   |
| 3  | Emerson |
```