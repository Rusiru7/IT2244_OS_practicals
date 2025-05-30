# IT2244_OS_practicals
Practical records of IT2244_OS_

Practical Linux Commands and Shell Script Examples
This repository contains a collection of practical Linux command-line examples and two basic shell scripts, demonstrating fundamental operations such as date manipulation, user input handling, arithmetic calculations, and CSV file processing. This content is ideal for beginners learning to navigate and automate tasks in a Linux environment.

Content Overview
The practical.txt file serves as a comprehensive log or tutorial, covering:

Date and Time Commands: Demonstrations of how to display various formats of the current system date and time.

Shell Script Example 01 (example01.sh): A script that takes user input (name and three numbers) and calculates their sum and average.

Shell Script Example 02 (example02.sh): A script that takes two numbers from the user and performs basic arithmetic operations (addition, subtraction, multiplication, and division).

CSV File Operations: Examples of creating, viewing, filtering, extracting, and sorting data within CSV files using commands like grep, head, tail, awk, cut, and sort.

Date and Time Commands
The following date command examples are showcased:

date +%d: Display day of the month (e.g., 14)

date +%m: Display month as a number (e.g., 05)

date +%y: Display year in 2-digit format (e.g., 25)

date +%D: Display date in MM/DD/YY format (e.g., 05/14/25)

date +%Y: Display year in 4-digit format (e.g., 2025)

date +%B: Display full month name (e.g., May)

date +%b: Display abbreviated month name (e.g., May)

date +%A: Display full weekday name (e.g., Wednesday)

date +%a: Display abbreviated weekday name (e.g., Wed)

Note: The output for cal command shows that it might not be installed by default on some systems and suggests installing it.

Shell Script Example 01: Summation and Average Calculator (example01.sh)
This script prompts the user for their name and three numbers. It then calculates and displays the sum and average of these three numbers.
