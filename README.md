# Compound Interest Calculator
## Overview
This project is a straightforward Python command-line compound interest calculator.  Based on the original amount, the yearly interest rate, and the number of years, it enables users to determine the future worth of an investment.  To guarantee significant, positive values for every financial parameter, the application enforces input validation.  The objective is to use mathematical functions, variable management, input/output processing, and fundamental programming concepts as taught in the course syllabus.
## Features
Principal Input: Takes the user's initial investment amount.

- Rate Input: The annual interest rate is accepted.

- Time Input: Takes years as the time period.

- Using input loops, input validation verifies that all inputs (principal, rate, and time) are larger than zero.

- Compound Interest Calculation: Uses the compound interest formula to determine the total sum after the given period of time.

- Formatted Output: The final computed balance is shown, formatted to two decimal places.
## Technologies/tools used
- Python 3.x is used as essential language for implementation.
- Standard Input/Output is used for interacting with users and showing outcomes.
- pow() is used for mathematical exponentiation.
## Steps to Install & Run the project
- Clone The Repository
- Make sure you have Python installed:  Make sure Python 3 is installed on your computer
- Launch the calculator:  Use your terminal to run the main script
- Follow Prompts: The software will ask you to input the principal, interest rate, and years of time
## Instruction for testing
Validation testing and calculation testing of the main computation are the main types of testing for this project
- First.  Testing for Validation (Input Handling)
 Run the script and purposely submit faulty inputs to confirm the loops work as intended:

 Test Case 1 (Zero Input): Enter 0 for the primary, rate, and time

 Anticipated Outcome: The application ought to show the error notice (... cannot be zero less than or equal to zero) and ask for the input once more

 In Test Case 2 (Negative Input), enter -100 for the time, rate, and principal.

 Anticipated outcome: The application ought to show error message (... cannot be zero less than or equal to zero) and ask for input once more

 - Second Calculation Testing (Example of a Unit Test) Check the output by hand for a known situation.
    
 Input:
 
 Principal: 1000
 
 Rate: 10%
 
 Time: 1 year
 
 Anticipated computation: 1000 * (1 + 0.10)^1 = 1100.00
 
 Anticipated Results:  After a year, the balance is $1100.00.
