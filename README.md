## Name
On-the Job Training (OJT) Monitoring Website

## Description
This is a website that allows an adviser or an admin to monitor the ojt progress or requirements of their students. On the otherhand, the students are also able to monitor their own ojt progress. They can record their attendance which reflects on a timesheet, check their required documents and see announcements from their advisers.

## Tutorial
# Set up SQL database
Note: Make sure you have a tool to use for MySQL (phpMyAdmin or MySQL Workbench) and the Wampserver downloaded
1. After cloning the repository, either checkout to the node-js or php branch to download the ojt.sql
2. Run the Wampserver and import the ojt.sql in the chosen tool to view the data.
   - For example in MySQL Workbench:
     a. Select a MySWL Connection
     b. Select Server -> Data Import -> Import from Self-Contained File -> Change path to the path of the ojt.sql -> Click new -> Name the schema as "ojt" -> Click Import Progress tab -> Start Import
     
# Running adviser side of the website (Node.js):
1. Checkout to the node-js branch
2. Run the app.js file
3. Proceed to the website "http://localhost:8080/ojt-login-page/" and login as an adviser (Check the database for the email and password)

# Running student side of the website (Php):
1. Checkout to the php branch
2. Proceed to the website "http://localhost/ojt-monitoring/login.php" and login as a student (Check the database for the id number and password

## Visuals
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/b3eb0377-5e54-49f4-aff2-525e0449527f)
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/61d04229-382b-4103-8d3d-76aeb88f6fcb)
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/90fe823d-f93f-4bdd-8091-18af4c18eacc)
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/df55a69e-53a0-4246-a719-e8d38554e4be)
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/e9cf25ec-be35-4218-a57b-b4013a401d51)
![image](https://github.com/Yahds/OJT-Monitoring-Website/assets/137850019/9d830d02-3921-4079-be57-93018f87383e)

## Authors and acknowledgment
Worked on the Database and Documentation
Albert Jannsen Ramos 
Ariel Tarlit Jr. 

Worked on the Adviser Side (Node.js):
Jahn Crystan Abella 
Joshua Daniel David 
Haydee Shane Saguid 

Worked on the Intern/Student Side (PHP):
Jonison Martel Molintas 
Haydee Shane Saguid 
Maervin Villalobos 

Worked on the About us page:
Ariel Tarlit Jr. 
