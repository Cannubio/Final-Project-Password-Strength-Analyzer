# Final-Project-Password-Strength-Analyzer

Project Objectives
The Password Strength Analyzer is a Python-based tool designed to evaluate and enhance password security by:

Validating passwords against specific criteria:
Minimum length: 12 characters
At least one uppercase letter
At least one lowercase letter
At least one special character
At least one number

Providing clear feedback on how to improve password strength.
Scoring passwords on a percentage-based scale (0–100%).
Detecting and preventing the reuse of expired passwords.
Features

Password Strength Analysis:

Classifies passwords as "Strong," "Moderate," or "Weak."
Provides actionable feedback to improve password strength.
Entropy Calculation:

Measures password complexity based on unique character combinations.
Common Password Detection:

Alerts users if the entered password matches commonly used passwords.
Password Expiry and Reuse Prevention:

Tracks password reuse with timestamps and blocks expired passwords.
Interactive Feedback:

Offers real-time suggestions for creating stronger passwords.
Setup and Instructions
Prerequisites
Python 3.x must be installed on your system.
The script uses built-in Python libraries (re, math, getpass, etc.).
Installation
Clone or download the project repository.
Open a terminal or command prompt and navigate to the project directory.

Execution
Run the script using the command:

python password_strength_analyzer.py

Follow the prompts to input and analyze your password.

Dependencies
This project does not require external libraries or installations, as it relies solely on Python's standard library.

Recommended Requirements
Passwords must:
Be at least 12 characters long.
Include uppercase and lowercase letters.
Contain at least one number.
Have at least one special character (e.g., !, @, #, $).
Code Documentation
The code is thoroughly documented with clear comments explaining its logic and functionality. Here’s a summary of key functions:

Functions
1- calculate_entropy(password)
Purpose: Calculates the entropy of a password to measure its complexity.
Returns: A numeric value representing entropy.

2-calculate_password_score(password)
Purpose: Scores the password based on length, character variety, and entropy.
Returns: Password score (0–100).

3-analyze_password(password)
Purpose: Validates the password against the defined criteria and generates feedback.
Returns: A tuple containing strength classification, score, and feedback list.

4-main()
Purpose: Main program loop for user interaction and password analysis.



          CODE EXAMPLE 
          
          Enter your password (input hidden): *********
          Password Strength: Moderate
          Password Score: 70%
          Feedback:
         - Add at least one special character (e.g., !, @, #, $).
         - Increase password length to at least 12 characters.

