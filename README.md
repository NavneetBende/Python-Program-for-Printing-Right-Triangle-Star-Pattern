Printing Right Triangle Star Pattern
In this Python Program, we will be discussing about how to write a program to print Right Triangle Star Pattern. In this pattern, there are n rows with i numbers of time of iterations through all the rows and i+1 numbers of column are present. So, User have to enter a single value, that will be determine as a number of rows of the pattern. With the help of “Nested For Loop” , we will print the Right Triangle Star Pattern.

C Program for Printing Right Triangle Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows as input from the user and stored it into num.

Step 3. Run a for loop starting from 0 to user entered num value.

Step 4. Inside for loop, Run a loop ‘i’ number of times to iterate through all the rows which starting from 0 to i+1.

Step 5. Print ‘*’ inside the nested loop to print ‘*’s in all the columns of a row.

Step 6. Move to the next line by printing a new line using print() function.

Stop 7. Stop

Python Program:
num = int(input("Enter Number:"))

for i in range(0, num):
    for j in range(0, i+1):
        print("*", end="")
    print()
