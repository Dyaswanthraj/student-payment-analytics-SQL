# student-payment-analytics-SQL


TITTLE: Student Payment Analytics
DATABASE;studentDb

## Project Overview
This project analyzes student payment data to identify trends, revenue patterns, and top-performing courses and states. 
The goal is to provide insights that help educational institutions understand revenue distribution and course popularity over time.

Key objectives:
- Calculate total revenue generated per year and per course.
- Identify top states by revenue.
- Count student enrollments in each course.
- Analyze payment trends using SQL aggregate functions, GROUP BY, and CASE statements.

## Dataset
The dataset consists of student transaction records with the following fields:  
- `srno` – Serial number  
- `orderid` – Payment order ID  
- `sname` – Student name  
- `payment_date` – Date of payment  
- `course_name` – Name of the course  
- `price` – Amount paid  
- `payment_status` – Payment status (captured/failed)  
- `payment_id` – Payment transaction ID  
- `email` – Student email  
- `state` – Student state  

