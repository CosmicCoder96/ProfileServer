#Profile Server
Profile Server for Attendance and Student's Profile

NOTE : The project is still in development stage , but if you want to contribute , contributions are always welcome :)

##Setup
* import profileserver.sql to your desired database
* in php_includes/dbconnect.php , change mysql_connect("serveraddress","username","password") and mysql_select_db("yourdatabasename") according to your server.
* Voila , you have the project up and running.
* If you are getting an error message , try changing the permissions of project directory with ```sudo chmod -R 755 directory_address``` and the images directory with ```sudo chmod -R 775 directory_address```.
 
##NOTE:
* Any user's profile can be accessed by /profileserver/user_roll_no
