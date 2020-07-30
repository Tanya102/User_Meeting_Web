# User_Meeting_WebApp
This is a user registration/login system for a web based meeting for authorized users. 
# Refer to wiki for the flowchart explaining the workflow of this potential web based application.


# WorkFlow Explaination:
User visits the registration page, if it is a registered user it is redirected to "Login Page" via link, else is required to enter user details in the "Registration Page". These details are inserted into database and the status of the user is changed to "inactive". When the user logs in, a query is used to determine its current status from the database, if its status is "active", it is redirected to "Meeting Page" else is redirected to error page for unauathorised users. When the user visits this meeting page, it shows the count of currently active (status=="active") users on the same page as the currently viewing audience.




# References:
1. https://speedysense.com/create-registration-login-system-php-mysql/
2. https://medium.com/agora-io/building-a-group-video-chat-app-bc05e8962c41


