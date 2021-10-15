# PaaS Practicum


### 1. Create Database Through Oracle
First, we can create database with oracle. The things that's important for creating database in oracle is username and password because if we want remote the database we should know about the database and the password. Also, when we create an database, make sure the VCN and VM already running.

### 2. Create database via SSH
Before create database through SSH VM, we have to login to our database that already created in oracle. the command like below : 

> mysql -u admin -p -h (private IP database)

after type this command, we have to enter the password that already create when create a database.

### 3 Create Wordpress Database
After login in database we can directly make database, give the name of database is "wordpress". comamnd to make wordpress like below 

> create database wordpress;

If success, we can download package file of wordpress but make sure we donwload it in directory /var/www/html. the command to open directory like below :

> cd /var/www/html

When success to download the file, we can extract the file using command :
> tar zxvf latest.tar.gz 


