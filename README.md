UniChat a chat app with Tkinter GUI. Sockets are used for networking in this project.
to run the application first run the server file it uses python-3 then execute run.py file 
for database you can create your own local database for the user.
querys:

 
i). CREATE DATABASE LOGIN_APP;
 

ii). CREATE TABLE LOG_DETAILS(NAME VARCHAR(20), USERNAME VARCHAR(20), PASSWORD VARCHAR(20), AVATAR VARCHAR(20));
 


Configuration for the Database:

user: root

password : password

host: localhost

Requirements
1. python3
  | sudo apt-get install python3
2. Install tkinter
  | sudo apt-get install python3-tk
3. Install Mysql
  | sudo apt-get install mysql-server
and configure it
  | sudo mysql_secure_installation


for Python Packages:
  
  | python3  -m pip install -r requirements.txt
