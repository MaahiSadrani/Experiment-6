# Experiment-6

# Aim: Study of conditional statements in python.

# Theory:

Conditional statements in Python are used to control the flow of execution based on certain conditions. 
They allow the program to make decisions and execute specific blocks of code only when a condition is true. 
The main conditional statements in Python are if, if-else, and if-elif-else. The if statement is used to test a single condition. 
The if-else statement is used when there are two possible outcomes. The if-elif-else statement is used to check multiple conditions in sequence. 
Python uses indentation to define the block of code inside conditional statements. Logical operators like and, or, and not are used to combine multiple conditions. 
Comparison operators such as ==, !=, >, <, >=, and <= are used to form conditions. Conditional statements are very important in programming because they help in 
decision-making and make programs interactive and dynamic.
# Syntax of conditional statements:

1).if condition:
  statements
 2).if condition:
  statements1
    else:
  statements2
 3).if condition1:
  statements1
    elif condition2:
  statements2
    else:
  statements3

##   Algorithm:
Q1) Algorithm to Check Whether a Number is Positive, Negative or Zero
1.Start
2.Input a number num
3.If num > 0, print "Number is positive"
4.Else if num < 0, print "Number is negative"
5.Else print "Number is zero"
6.Stop

Q2) Algorithm to Check Whether a Number is Even or Odd
1.Start
2.Input a number num
3.If num % 2 == 0, print "Number is even"
4.Else print "Number is odd"
5.Stop

 Q3) Algorithm to Find the Largest of Three Numbers
1.Start
2.Input three numbers a, b, and c
3.If a >= b and a >= c, then a is largest
4.Else if b >= a and b >= c, then b is largest
5.Else c is largest
6.Display the largest number
7.Stop

Q4) Algorithm to Calculate Grade
1.Start
2.Input marks
3.If marks ≥ 90 → Grade A
4.Else if marks ≥ 75 → Grade B
5.Else if marks ≥ 60 → Grade C
6.Else if marks ≥ 40 → Grade D
7.Else → Grade F
8.Display grade
9.Stop

 Q5) Algorithm to Check Leap Year
1.Start
2.Input year
3.If (year divisible by 4 AND not divisible by 100) OR (year divisible by 400)
4.Then print "Leap year"
5.Else print "Not a leap year"
6.Stop

Q6) Algorithm to Calculate Gross Salary
1.Start
2.Input basic salary
3.If basic ≤ 10000
4.HRA = 20% of basic
5.DA = 80% of basic
6.Else if basic ≤ 20000
7.HRA = 25% of basic
8.DA = 90% of basic
9.Else
10.HRA = 30% of basic
11.DA = 95% of basic
12.Gross Salary = Basic + HRA + DA
13.Display gross salary
14.Stop

Q7) Algorithm to Calculate Income Tax
1.Start
2.Input annual income
3.If income ≤ 2,50,000 → Tax = 0
4.Else if income ≤ 5,00,000
5.Tax = (income − 2,50,000) × 5%
6.Else if income ≤ 10,00,000
7.Tax = (2,50,000 × 5%) + (income − 5,00,000) × 20%
8.Else
9.Tax = (2,50,000 × 5%) + (5,00,000 × 20%) + (income − 10,00,000) × 30%
10.Display tax
11.Stop

Q8) Algorithm to Check Vowel or Consonant
1.Start
2.Input a character ch
3.If ch is in (a, e, i, o, u, A, E, I, O, U)
4.Print "Vowel"
5.Else print "Consonant"
6.Stop

Q9) Algorithm to Increment Date
1.Start
2.Input date in format dd/mm/yyyy
3.Separate day, month, year
4.Determine maximum days in month
5.If month = 1,3,5,7,8,10,12 → 31 days
6.If month = 4,6,9,11 → 30 days
7.If month = 2
8.If leap year → 29 days
9.Else → 28 days
10.If day < max days → day = day + 1
11.Else
12.day = 1
13.If month = 12
14.month = 1
15.year = year + 1
16.Else
17.month = month + 1
18.Display new date
19.Stop

## Conclusion:
Therefore we studied and implemented the conditional statements and their use in python.
Conditional statements are an essential part of Python programming. They help control the flow of execution by allowing the program to 
make decisions based on different conditions. By using `if`, `if-else`, and `if-elif-else` statements along with logical and comparison operators,
programmers can create interactive, flexible, and dynamic programs. Therefore, understanding conditional statements is fundamental for writing effective and efficient Python code.
