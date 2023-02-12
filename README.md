# BYGB-7990-HW1

SQT PROGRAM USER GUIDE

The Student Query Tool developed using Python allows the user to retrieve student records based on certain specifications. First, the program will ask the user to input which records they would like to see:

"Please enter which records would you like to retrieve:       "

The user must input one of the following options (excluding quotations):		

    “All”	    To display all student records

    “First”	    To display records for students whose first name begins with a certain string. The user will then be asked to input the desired string or name.

    “Last”	    To display records for students whose last name begins with a certain string. The user will then be asked to input the desired string or name.

    “Year”	    To display all records for students whose graduating year is a certain year. The user will then be asked to input the desired graduation year.

    “Summary”   To display a summary report of number and percent of students in each program, for students graduating on a certain year. The user will then be asked to input the desired graduation year.

In case the user enters an invalid input, the program will return a message of “Invalid Input”. The user must run the program again and re-enter their input.

In case the user enters a value that does not match any of the student records, the program will return a message of “No results match your search criteria”. The user must run the program again and re-enter their input.
