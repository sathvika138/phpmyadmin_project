# phpmyadmin_project
WEB APPLICATION TESTING PROJECT

**About the project**


This project aims to evaluate the phpMyAdmin website for any issues related to functionality, performance, and data security. To achieve this, we are implementing a structured testing strategy and identifying the most suitable testing scenarios for this project.


**SETTING UP PHPMYADMIN ON LOCAL MACHINE**

****Step 1: INSTALL LOCAL SERVER ENVIRONMENT****
 Choose any local server environment to install on the local machine. In this project XAMPP is used as local server.

 Install XAMMP from the official website. After the installation start Apache and MYSQL servers from the control panel. 

**SETTING UP PHPMYADMIN**

Usually phpmyadmin is bundled with xampp, so there is no need for installing it seperately. 
Open the browser and type in http://localhost/phpmyadmin. 

**OBJECTIVES**: 

Functional Testing: Verify features like database creation, inserting data and user privilage management. 

UI/UX Testing: Testing if the interface, usability and responsiveness is working as expected.

Performance Testing: Analyse performance under load and any complex queries.

Database Integrety Testing: Verify the integrety of the data is managed.

Security Testing: Ensuring the privacy of the data, unauthorised access is maintained. 


**TOOLS USED**

1. XAMPP
2. Phpmyadmin
3. Jira


**TESTING METHODOLOGIES**

**Functional Testing**: Testing the functionality of the web application (Phpmyadmin)

> Create database and check the presence of it.

> Insert Data and retrieve it from the table.

> Import and export of the documents.

**UI/UX testing**: Testing the interface, Usability and aspects of the application

> Check the usability on diffrent sized screen of the application.

> Check the concsistency of the UI.

**Performace Testing**: Testing and analyzing the performance of the application under load and complex queries.

> Check the application on uploading large datasets.

> Load test with multiple users.

**Database Integrety Testing**: Testing the procedure of the application

> Insert, Drop, Update and delete the records

> check the foreign key constraints

**Security Testing**: Testing the maintainace of the unauthorised access and privacy of the data

> Access data from unauthorised account

> Check for any SQL injection vulnerabilities ( which means allowing attackers to insert malicious data into the SQL queries) 

