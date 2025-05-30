# IT2244_OS_practicals
Practical records of IT2244_OS_

# Linux File Operations Showcase

This repository contains a simple shell script (`day3.sh`) demonstrating fundamental Linux commands for file manipulation, viewing, and searching. It's a great starting point for beginners to understand common command-line operations.

## Script Overview

The `day3.sh` script includes examples of:

* **Listing Files**: Showing visible and hidden files and directories.
* **Viewing File Contents**: Displaying entire files, page by page, and specific lines.
* **Creating Files**: Making empty files.
* **Editing Files**: Opening files in `vi` editor.
* **Filtering Content**: Extracting specific lines or patterns using `grep` and `awk`.

## Commands Demonstrated

Here's a breakdown of the commands used in the script:

* `ls`: List directory contents.
* `more`: Display output one screen at a time.
* `touch`: Change file timestamps; create a file if it does not exist.
* `vi`: Vi improved, a programmer's text editor.
* `head`: Output the first part of files.
* `tail`: Output the last part of files.
* `grep`: Print lines matching a pattern.
* `awk`: Pattern-directed scanning and processing language.

## How to Use

To run the script, save the content as `day3.sh` and execute it in your Linux terminal:

```bash
bash day3.sh



//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////



Windows Batch Script: Date Information Extractor
This repository contains a simple Windows batch script (date_extractor.bat) designed to demonstrate basic command prompt operations, specifically focusing on extracting and displaying different parts of the current system date. It's a useful example for those learning batch scripting and manipulating system variables.

Script Overview
The date_extractor.bat script performs the following actions:

Disables Command Echo: Prevents commands from being displayed in the command prompt window, making the output cleaner.

Displays Full System Date: Shows the complete current date as recognized by the system.

Extracts Month: Isolates and displays the month part of the date.

Extracts Day: Isolates and displays the day part of the date.

Extracts Year: Isolates and displays the year part of the date.

Extracts Weekday: Isolates and displays the weekday (e.g., "Fri") part of the date.

Pauses Execution: Waits for user input before closing the command prompt window, allowing the user to view the output.

How it Works
The script leverages the %date% environment variable, which holds the current system date. It then uses string manipulation (substring extraction) with the :~start,length syntax to pull out specific parts of the date string.

%date%: Represents the full current system date (e.g., "Fri 03/21/2025").

%date:~4,2%: Starts at the 4th character (index 4) and takes 2 characters (e.g., "03" for March).

%date:~7,2%: Starts at the 7th character (index 7) and takes 2 characters (e.g., "21" for the 21st day).

%date:~10,4%: Starts at the 10th character (index 10) and takes 4 characters (e.g., "2025" for the year).

%date:~0,3%: Starts at the 0th character (index 0) and takes 3 characters (e.g., "Fri" for Friday).

How to Use
To run this script:

Save the code provided into a file named date_extractor.bat (or any other name with a .bat extension).

Open a Command Prompt window.

Navigate to the directory where you saved the .bat file.

Execute the script by typing its name and pressing Enter:
