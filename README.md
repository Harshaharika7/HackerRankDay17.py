# 📘 Day 17: More Exceptions | HackerRank 30 Days of Code

This repository contains the Python solution for *Day 17* of the HackerRank 30 Days of Code challenge, focusing on the concept of *Exception Handling* using custom error messages in a class-based method.

## 🚀 Challenge Summary

-You are required to write a class `Calculator` with a method `power(n, p)` that returns the result of `n^p`. 

-If either `n` or `p` is negative, the method should raise an exception with a custom message.

## 📝 Problem Statement

Complete the `Calculator` class by:

- Creating a method `power(n, p)` that calculates `n^p`.
  
- If `n < 0` or `p < 0`, throw an exception with the message:
  
n and p should be non-negative

## ✅ Constraints

    - 0 ≤ n, p ≤ 10
       
    - No test case will cause overflow for valid inputs.

## 🔢 Sample Input

          4
          
          3 5
          
          2 4
          
          -1 -2
          
          -1 3

## ✅ Sample Output

            243
            
            16
            
            n and p should be non-negative
            
            n and p should be non-negative

## 💡 Explanation

- 3 and 5 are positive → 3^5 = 243
  
- 2 and 4 are positive → 2^4 = 16
  
- -1 and -2 are negative → Exception
  
- -1 is negative → Exception  

The code properly throws an exception and displays the correct error message when invalid input is given.

## 🧠 Concepts Practiced

- Exception Handling with `try` and `except`
   
- Custom error messages
   
- Class and Method Design
   
- Object-Oriented Programming (OOP)
  
- Input Validation

## 🛠 How to Run

Option 1: With input file

Create a file named `input.txt` with the required input and run:

        python3 more_exceptions.py < input.txt

Option 2: Manual input

Just run:

        python3 more_exceptions.py

## 🔗 HackerRank Challenge Link: 

        HackerRank – Day 17: More Exceptions

🏆 Challenge Completed

✅ Problem Solved 

🎯 Points Earned: 30  

## 📅 Completed On:  

      29th May 2025

## 🔖Tags

#Python #HackerRank #Exceptions #OOP #30DaysOfCode #ProblemSolving #Day17Challenge #TryExcept #CleanCode

## ✍ Author

        Harsha M  
        
        GitHub: @Harshaharika7
        
        LinkedIn: Harsha M
