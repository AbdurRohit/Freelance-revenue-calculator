# Freelance-revenue-calculator
This is a desktop application designed to help freelancers who charge hourly track their time and calculate their earnings. The app allows users to input the amount of time spent on client work down to the minute and their hourly rate. It then automatically calculates the amount earned for that time period and logs it in a database.
<br>
## Features:
<br>
User input fields:<br>
Time spent on work in hours and minutes
<br>

Hourly rate<br>
Automated calculation of earnings based on time x rate<br>
Database to store records of:<br>
Date<br>
Time spent<br>
Hourly rate<br>
Total amount earned<br>
Reporting features to view/export earnings records<br>
User Flow:<br>
<br>
User inputs time spent on work for a specific date<br>
The user inputs their hourly rate<br>
![IMG-20230220-WA0001](https://github.com/AbdurRohit/Freelance-revenue-calculator/assets/96853180/293dffa9-4043-4112-af7a-f74538e1dafa)
# Technologies Used

- Java Swing for the graphical user interface
- MySQL for the database to store earnings records

## Key Steps

1. Create the Swing UI with text fields for time and rate entry, a button to calculate earnings, and a table to display results.

2. Connect to the MySQL database using JDBC and create the earnings table if it does not already exist. 

3. When the user hits the Calculate button, read the input values, calculate the earnings, and insert a new record into the MySQL earnings table.

4. Retrieve records from the earnings table and display them in the Swing UI table on demand to give the user visibility into their past earnings.

5. Allow exporting earnings records to a CSV file for portability.

The Java Swing front-end will provide a clean and responsive interface while MySQL on the back-end will reliably store the earnings data. This combination of technologies is common for desktop business applications requiring a database.
