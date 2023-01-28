# Java-Lab-002

## Variables, Types and Operators

Be able to explain what variables are. Understand variable types, allowed names, and valid values.
Know how to create and use string, integer, floating-point, and boolean variables.

### Part 1 - PricelessScript.java - [MasterCard YouTube Ad](https://www.youtube.com/watch?v=Q_6stXKGuHo)

The lab template contains a program that prints the following:
```
2 tickets: $28.00
2 hotdogs, 2 popcorn, 2 sodas: $18.00
1 autographed baseball $45.00
real conversation with 11 year old son: priceless
true
```

Ignore the code that you don't fully recognize and concentrate on changing the variables to alter the MasterCard *Priceless* script to say:
```
3 tickets: $42.00
3 hotdogs, 3 popcorn, 3 sodas: $27.00
2 autographed baseball $90.00
watching the Giants win: priceless
false
```

### Part 2 - Interpretation
Take note of the various variables and their data types. Write a brief summary in this section of the README.md file listing the:
* Variable name
* Its data type
* and example values you can assign them.

1. Character:
   1. Stores a single character of text
   2. ex: e, 2, g, and (.

2. String:
   1. Stores multiple characters of text.
   2. ex: "Hi, how are you doing?", or "1000 - 1200 = (-)200".

3. Integer:
   1. Stores an integer that can be used to perform calculations
   2. ex: 5, 20, 2000000000, or -50

4. Float/Double:
   1. Stores decimal numbers. Float uses 32 bit components and double uses 64 bit components
   2. ex: 11.25, 8.0, 0.5061, or 0.001

5. Boolean:
   1. Stores the value of true or false.
   2. ex: True, or False

Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!

1. char firstInitial = "H"; //"H" is a string value becuase it is contained by quotation marks, not apostrophes.
2. int balance = 500.0; //500.0 is a double, not an integer value.

### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.

![Format Specifiers](JavaStringFormatSpecifiers.png)

### Part 4 - Submission
* Just as you did last week (Reference the Lab video in your Week 1 module), create a Spring2023 feature branch of your code
* Commit your working code to your local copy
* Push it to your Remote/origin branch (i.e. GitHub: Spring2023 -> origin/Spring2023)
* Then issue a Pull request to my instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.
