# Week 6 Assignment - Safe Functions

## Files

- safe_tools.py - Contains three safe functions using try and except to handle errors.
- week6_output.png - Screenshot showing the successful program output.
- README.md - Assignment description and explanation.

## Question: Why can the if check not catch abc on its own?

An if statement only checks conditions that we explicitly define. The int() function raises a ValueError when text such as "abc" cannot be converted into a whole number, so try and except are used to handle that error safely.