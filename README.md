Good evening bhaiya/didi,
My name is Piyush Sharma[2414146] and i have made an User Authentication system using nodemon,mongoose and express. This is my Backend API which receives 3 values name,email and password to signup. I have also used bcrypt for password hashing. I have used Mongodb for data storage. To deploy this project we just need to run the command "npm start" in vscode terminal. 
packages to be installed for deploying are
    
    "bcrypt": "^5.1.1",
    "body-parser": "^1.20.2",
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.19.2",
    "joi": "^17.13.1",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.4.1",
    "nodemon": "^3.1.10"

    
    To check the working of this project in POSTMAN we need to search for the url(http://localhost:8080/auth/signup) for signing up by three key value pair{ "name":"piyush","email":"piyushsharma@gmail.com",
    "password":"spsghy34"} and url(http://localhost:8080/auth/login) for login using two key value pair { "email":"piyushsharma@gmail.com",
    "password":"spsghy34"} using POST method.
