# SE-CC-assignment

<b><h1>Read Me:</h1></b>

<b><h2>Minimum Requirements:</h2></b>

-	Latest WAMP/MAMP/LAMP server.
-	PHP >= version 5.
-	MySQL >= version 5.
-	Apache >= version 2.4.
-	Latest edition of a web browser preferably Chrome >= version 50 and Firefox version >=48. Has not been tested on IE.

<b><h2>Installation Istructions:</h2></b>

1.	Install WAMP/MAMP/LAMP according to the running environment.
2.	Unzip the project folder into the www folder residing in the WAMP folder.
3.	Run WAMP/MAMP/LAMP.
4.	Once both APACHE and MySQL are active the service will have a green light on it.
5.	Open a web browser -> navigate to https://localhost:portnumber/phpmyadmin or your IP address if your service is live.
6.	Login to your phpmyadmin.
7.	Go to Import tab and import the MySQL file named database.sql in the Project folder.
8.	Change the login details of phpmyadmin to root and remove the password. (I failed to make a credentials file to hold all the credential in one place which can be modified anytime. In this case each and every file will have to be updated with phpmyadmin id and password where ever the database connections are necessary.)
9.	Now open a web browser and navigate to https://localhost:portnumber/www/Project
10.	 This will open the login page. Default: id: admin & pass: admin


<b><h2>Features:</h2></b>
1.	Book a room according to requirements.
2.	View upcoming bookings in the dashboard view.
3.	Search for bookings.
4.	Edit bookings
5.	Delete bookings
6.	Has a calendar view to view upcoming bookings


    
<b><h2>Random Rantings:</h2></b>
1.	To add more rooms just add them in the rooms table in MySQL according to the columns specified.
2.	This app currently is fit for single person use, how-ever multi person functionality can be added easily with a few tweaks in how booking are made.
3.	Themes and color schemes can be modified and made better and further customization options are needed to be provided to the user.
4.	This app gives basic security using sessions. Login sessions are stored and thus cannot be accessed by people without the credentials.
5.	Almost all of the requests made to the server side are POST requests thus further securing the process.
6.	AJAX requests are used in multiple places to dynamically update pages according to user inputs.
7.	Each of the functions are stored in separate files thus making them easy to understand. 
8.	HTML 5.0, CSS 3.0, JQuery 3.1.2, JQuery UI, Material Dashboard (theme), and various other jquery modules were used in the development of the app.

