[Back to Portfolio](./)

Final Project - STIG Powershell Script
===============

-   **Class:** Object Oriented Programming - CSCI 325
-   **Grade:** N/A
-   **Language(s):** Java
-   **Source Code Repository:** [STIG Compliance]([])  
    (Please [email me](mailto:trthompson@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project description

This program is a Statistics calculator. It is a GUI program in Java created using Netbeans. This program can take any comma seperated values, and calculate the mean, median, mode of said numbers. It can calculate produce output for those calculations individually or simultaneously. Upon the user providing input, the program "cleans" the data by removing spaces and commas to begin calculations.

## How to run the program

Download the ".ps1" file from the GitHub repository link. Then open Windows PowerShell ISE in administator mode, then open the file in the ISE and press the "run" button. 


## UI Design

When the program is ran in administrator mode, it'll proceed with all feature checks without any error messages (see Fig 1). If the program is not ran in administrator mode, the check for PowerShell v2, printing over HTTP, and TCP/IP compliance will throw an error message because the program needs to have elevated privilege to check those features (see Fig 2).

![screenshot](images/Scripting_adminMode.png)  
Fig 1. Example output when script is ran in administrator mode.

![screenshot](images/Scripting_noAdminMode.png)  
Fig 2. Example output when script is not ran in administrator mode.


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
