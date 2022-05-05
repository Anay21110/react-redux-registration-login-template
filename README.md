## Web Application Development Project :



# react-redux-registration-login-example

React + Redux - User Registration and Login Tutorial & Example

##  ## Hosting on AWS EC2 :

1) Creating an Amazon Machine Image (AMI) --> Ubuntu Server 18.04 LTS 

![Creating an AMI](https://user-images.githubusercontent.com/56868253/166943486-aaea69d5-f4d8-4e2f-a201-f17f726ef144.png)

(2) Connected to the new ubuntu instance from local machine --> 

![2](https://user-images.githubusercontent.com/56868253/166943778-3e504f76-a746-43db-b561-f519a63baa18.png)

(3) Cloning Git Repo on to the Instance -->

![3](https://user-images.githubusercontent.com/56868253/166944122-c7cbce8b-4a51-4e6c-a535-528e3ca37c66.png)

(4) Start the API using the PM2 process manager with command `sudo pm2 start server.js` -->  
*The API is now running on Node.js under the PM2 process manager and listening on port 4000. Only port 80 (HTTP) is publicly accessible on the server so we can't hit the API yet, this will be possible after we've configured NGINX as a reverse proxy to pass through HTTP traffic to the api.*

![snap](https://user-images.githubusercontent.com/56868253/166946337-1ed9d7df-5b3c-49b9-b09c-db91e61f623c.png)


(5) Registration Page -->

![Register Page](https://user-images.githubusercontent.com/56868253/166948040-f699579a-658b-4edf-9b4a-7027af602ebb.png)



(6) Login Page --> 

![Login](https://user-images.githubusercontent.com/56868253/166947494-5eb719b6-0590-4b23-a85b-b0152ebdde44.jpg)

(7) Logged IN -> 

![Logged in !](https://user-images.githubusercontent.com/56868253/166948134-963e7986-8fb1-44d6-b1be-62ba83587b5f.png)


Happy Learning !
