# Password Strength Checker
This repository contains a Python script that evaluates the strength of a password based on multiple criteria. The script provides feedback on whether the password meets these criteria and rates its overall strength.

# Features

Password Length Check: Ensures the password has a minimum length of 8 characters.
Uppercase Letter Check: Verifies the presence of at least one uppercase letter.
Lowercase Letter Check: Verifies the presence of at least one lowercase letter.
Digit Check: Checks if the password contains at least one numeric digit.
Special Character Check: Ensures the password includes at least one special character (e.g., !@#$%^&*()).
Strength Rating: Rates the password as Very Weak, Weak, Moderate, or Strong based on the number of criteria met.

# Installation
This script requires Python 3 and the re (regular expressions) module, which is included in the Python standard library.

# Usage
Clone the Repository:

git clone https://github.com/yourusername/password-strength-checker.git.

cd password-strength-checker


Run the Script:

python password_strength_checker.py

Input Parameters:

The script will prompt you to enter a password to check its strength.

Enter a password to check its strength: YourPassword123!

# Example Output:

The script will evaluate the password and provide detailed feedback:
Password Strength Feedback:
Length Criteria Met: Yes
Uppercase Criteria Met: Yes
Lowercase Criteria Met: Yes
Digit Criteria Met: Yes
Special Character Criteria Met: Yes
Strength: Strong

#How It Works
Criteria Evaluation:
The script checks the password against five criteria:

Length: The password must be at least 8 characters long.

Uppercase: The password must contain at least one uppercase letter.
Lowercase: The password must contain at least one lowercase letter.
Digit: The password must contain at least one numeric digit.
Special Character: The password must contain at least one special character.
Strength Calculation:

The script sums the number of criteria met by the password.
Based on the score, it rates the password's strength:
5/5: Strong
4/5: Moderate
3/5: Weak
0-2/5: Very Weak
