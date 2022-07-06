# docker-php-login-system
php login system with registration and user management based on docker. If you have any suggestions or would like to contribute to it, you are welcome to.  I would like to make sure this is a secure login system. 
# Setup
Clone the project,<br/>
Rename the file env_sample.php to env.php<br/>
Change configuration on env file to meet your needs. <br/>
do docker-compose up -d<br/>
Visit the phpmyadmin site under the 8080 port<br/>
Select the mydatabase Database and import the database.sql file<br/>
This will import the database tables and default users.<br/>
After that its a typical Docker compose deployment, using the docker-compose.yml as your compose file. The default user credentials are the following: 
<br/>
# Default Users
Admin<br/>
email: pancho@gmail.com<br/>
pass: PanchoAdmin!<br/>
<br/>
User<br/>
email: edgar@gmail.com<br/>
pass: edgarUser!<br/>

# Pages:<br/>
register.php &#9745;<br/>
login.php &#9745;<br/>
logout.php &#9745;<br/>
home.php &#9745;<br/>
smtp email &#9745;<br/>


# Admin Panel
List Users<br/>
Disable or enable Accounts<br/>


# Features
Roles: allows a user to have more than one role, 
The admin.php page includes files within it to display different sections of its page.
else it displays a default main page. 
