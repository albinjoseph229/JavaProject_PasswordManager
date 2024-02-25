<h1>Password Manager<h1><br>
The Password Manager is a Java application for managing passwords securely. It allows users to store, retrieve, edit, and remove passwords for various websites or applications.

<br>Features<br>
First-time setup: Set up a username and password for initial access.
Login: Authenticate users with their username and password.
Add Password: Add a new password for a website or application.
Retrieve Password: Retrieve a password for a website or application.
Edit Password: Edit an existing password for a website or application.
Remove Password: Remove a password for a website or application.
<br>Technologies Used<br>
Java
JDBC (Java Database Connectivity)
MySQL Database
AES Encryption Algorithm
<br>How to Use<br>
<br>First-Time Setup:<br>

When you run the program for the first time, it will detect that it's the first-time login and prompt you to set up a username and password.
Login:

After setting up the username and password, you'll be prompted to enter your credentials to log in.
Main Menu:

Once logged in, you'll see a menu with options to add, retrieve, edit, or remove passwords, as well as to exit the program.
Adding a Password:

Choose the "Add a password" option from the menu and follow the prompts to enter the website or application name and the corresponding password.
Retrieving a Password:

Choose the "Retrieve a password" option from the menu and enter the website or application name to retrieve the associated password.
Editing a Password:

Choose the "Edit a password" option from the menu, enter the website or application name whose password you want to edit, and provide the new password.
Removing a Password:

Choose the "Remove a password" option from the menu, enter the website or application name whose password you want to remove, and confirm the action.
Exiting the Program:

Choose the "Exit" option from the menu to exit the program.
<br>Security Considerations<br>
Passwords are stored in an encrypted format using AES encryption to enhance security.
User passwords are hashed using the SHA-256 algorithm before storing them in the database to prevent unauthorized access.
<br>Database Setup<br>
The application uses a MySQL database to store user credentials and passwords.
Ensure that you have a MySQL database set up with the appropriate schema and permissions before running the application.
<br>Dependencies<br>
This project relies on the JDBC driver for MySQL to connect to the database. Ensure that the JDBC driver is included in the project's classpath.
