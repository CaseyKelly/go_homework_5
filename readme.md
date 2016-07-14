- Read a CSV file line by line
- Records contain employee asset information
- First line of CSV is the “column header” line
- Print records sorted by department, then employee name, then assigned date

- Data input example:

Name, Department, Asset, Assigned
Ann, A21B, Laptop, 2016-01-09
Bob, B50, Desktop, 2015-07-30
Jim, A21B, Laptop, 2016-03-29
Ann, A21B, Desktop, 2015-10-31
Bob, B50, Laptop, 2015-02-28
Ann, A21B, Apple iPad, 2015-05-20

- Sample Output:

A21B, Ann, Laptop, 2016-01-09
A21B, Ann, Desktop, 2015-10-31
A21B, Ann, Apple iPad, 2015-05-20
A21B, Jim, Laptop, 2016-03-29
B50, Bob, Desktop, 2015-07-30
B50, Bob, Laptop, 2015-02-28

- Input data provided on 'Box' account as Homework5Input.csv, expected output in Homework5Answer.csv