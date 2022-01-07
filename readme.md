docker-php-login-system
php login system with registration and user management. My verry first project that I make public, if you have any suggestions or would like to contribute to it, you are welcome to. I would like to make sure this is a secure login system.

Setup
Clone the project,
Rename the file env_sample.php to env.php
Change configuration on env file to meet your needs.
After that its a typical Docker compose deployment, default user credentials are the following:

Default Users
Admin
email: pancho@gmail.com
pass: PanchoAdmin!

User
email: edgar@gmail.com
pass: edgarUser!

Pages:
register.php ☑
login.php ☑
logout.php ☑
home.php ☑
smtp email ☑

Admin Panel
List Users
Disable or enable Accounts

Features
Roles: allows a user to have more than one role, The admin.php page includes files within it to display different sections of its page. else it displays a default main page.
