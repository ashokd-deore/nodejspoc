"# NodeJSPOC" 

Recipe Project

This project runs locally using port 8080.

INSTALLATION
1.	Node js
2.	Visual Studio code
3.	Postman
4.	Mongodb
		
STEPS TO RUN PROJECT
1.	npm init
2.	npm install             
3.	Start Mongodb server
4.	Command to run project
	nodemon app
        
Run requests using postman

1.	Registration of User
	
POST http://localhost:8080/signup

Body: {
“email” : “jimin@gmail.com”,
“password” : “1234567”
}

2.	Login
	
POST https://localhost:8080/login

 
JWT token generated

3.	Logout

GET http://localhost:8080/logout

