# powerbisqlauto
PowerBI SQL automation

Python version - 3.7.4 

Pre-requisite:
1.	Connect to Actian product and create db with sample tables.
2.  Establish connection to powerbi using Actian connector and Create a sample PBIX Report by using powerbi DAX functions.
3.	Enable server trace logs for Actian product and capture the SQL's generated during the powerbi report creation.

How to Run:

4.	Clone the repository to your local and Prepare an inputsqlfile with all the SQL queries traced from PowerBI PBIX Reports or your own set of SQL's
5.	Open the script.py file and update DSN for your database or supply ODBC database connections strings in the script.
6.  Run script.py
7.	Verify TestResultssheet for results comparision( Sample results sheet)
