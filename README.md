# Tic-Tac-Toe-1

This is a very basic Tic-Tac-Toe website that was built using HTML,CSS,JAVASCRIPT,PHP,SQL.

#Frontend

The frontend was built using HTML,CSS,JAVASCRIPT and it consists of four pages:

 1.Login/Registration Page:
 
 On this page a new user can register himself into the database and an existing can login using the credentials he gave in the database.

 2.Homepage:

 On this page a user can decide if he would like to play gainst an AI or another player.

3.Play against AI:

On this page there is a 3X3 grid in which a user can place an X or an O and there is a minmax algorithm implemented using JAVASCRIPT that would be playing against the user.

4.Play with a friend:

On this page there are three options for user to choose (i) 3X3 grid (ii) 4X4 grid (iii) 5X5 grid.

#Backend

The backend of the website was built using PHP and MYSQL

Basically whenever a new user registers himself through the registration page, an isert query is run and the user information is entered into the database successfully.
Later on when the user wants to login through the login page, the page sends a request to fetch the username and password of said username and compares the credentials.
If the credentials are valid the user is granted access to the homepage.If the credentials are invalid the user wil be sent a prompt telling them to use valid credentials.

In the case of a dataleak, if the database was accessed by other people, the user passwords would not be compromised as there is a hashing algorithm that hashes the passwords.

#Hosting

the webpage is hosted on 000webhost.
the link for th webpage is: https://tic-tac-toe-yathnesh.000webhostapp.com/login.php
the mobile apk for the app is in the android folder of the source code.
