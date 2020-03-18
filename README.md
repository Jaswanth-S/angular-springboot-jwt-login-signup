
This consists of :

1.UserService

2.goldies-gym

Steps to start the setup:

1. make mysql running in local system or in docker container

 create testdb using command
	
	-- create datyabase testdb;

Now navigate to  UserService and run using command 
	
	-- mvn spring-boot:run
	
Now application will be running at localhost:8080

Now go to mysql terminal (mysql -u root -p), now run below sql queries

-->INSERT INTO roles(name) VALUES('ROLE_USER');

-->INSERT INTO roles(name) VALUES('ROLE_MODERATOR');

-->INSERT INTO roles(name) VALUES('ROLE_ADMIN');

2. Now run the frontend and test the working

 commands 
 
	1. Install required dependencies	

		--> npm install (if any issues sudo npm install)
	
	2. start the application
	
		--> ng serve 
Now open http://localhost:4200 in browser and test signup and login,

For admin and moderator you can test from postman and login from app, it works fine
