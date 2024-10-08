# lab5
Lab #5 C++

## Lab #05 Flowchart

Create a C++ program that calculates the value of a car over the time you own it. For
this assignment, assume that a new car depreciates 12% per year. The value of the car
each year is the previous year’s value minus the previous value times the depreciation
rate.

Your program should:
1. Request the price of your new car.
2. Request the number of years you will own it.
3. Display a table showing the year and the value of your car that year.
Section 5.6 in "Starting Out with C++" gives a C++ example for displaying a table.
Once your Raptor flowchart executes correctly, upload your .rap file. Make sure your
name and assignment are on the flowchart in a comment.

``` Sample Output (inputs in bold)
Please enter the price of your new car: 30000
Please enter the number of years you will own your car: 6
Year           Car Value
===============
1               $30000
2               $26400
3               $23232
4               $20444.1600
5               $17990.8608
6               $15831.9575
```
Extra Credit (5 points)
Extend this program so that it also asks for the depreciation rate. Use that rate to compute the new value instead of 12%.
``` Please enter the price of your new car: 30000
Please enter the number of years you will own your car: 4
Please enter the depreciation rate: 14
Year          Car Value
===============
1                $30000
2                $25800
3                $22188
4                $19081.6800
```
