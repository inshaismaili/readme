# readme
Registration Portal
# registration-portal
a registration  portal for people to sign in and sign up
![home](https://user-images.githubusercontent.com/44523159/47619355-ce759f80-db03-11e8-9f7c-ff7e4601d841.PNG)
![homepage](https://user-images.githubusercontent.com/44523159/47619356-d1709000-db03-11e8-9529-66cebf0747b7.PNG)
![invalidpass](https://user-images.githubusercontent.com/44523159/47619358-d3d2ea00-db03-11e8-983f-8a55379af0ef.PNG)
![invaliduser](https://user-images.githubusercontent.com/44523159/47619361-d59cad80-db03-11e8-9778-367d9c9b8a80.PNG)
![login](https://user-images.githubusercontent.com/44523159/47619362-d6cdda80-db03-11e8-8f7b-e611c902b0b9.PNG)
![registration](https://user-images.githubusercontent.com/44523159/47619363-d8979e00-db03-11e8-90e0-2f0dc23a982a.PNG)
![signin](https://user-images.githubusercontent.com/44523159/47619366-dcc3bb80-db03-11e8-92a8-ce02e397485e.PNG)
![validuser](https://user-images.githubusercontent.com/44523159/47619367-e0efd900-db03-11e8-822b-be9a52564d6e.PNG)
steps
frontend
step1:created a homepage which gives the option of signingin and singningup
if user has already registered he will opt for the option signin,for signing in the user will have to fill in his userid and password.
if the userid and password matches the user will be redirected to home that will display WELCOME, else an error message, "user not registered" or "invalid password" will be displayed.
For new users there is an option of signing up.
The user will have to enter all details,once he has entered,he can then sign in to the portal as now he has been registered.
Backend:
For backend i have used nodejs and mongodb
nodejs is a webserver that  is handled by the user
mongodb is a databaseserver that is handled by the machine
I have used express for  framework
Routing is being  done by get and post request
 mongo is a variable,mongoose is being used to establish a connection between datasrver and webserver.
bodyparser is a middleware which  works between request and response.
bodyparser is used so that so that the data that is recieved by the post request is converted into readable form .
urlep used is the object of bodyparser.
var app=express()is the object of the express.
mongo.connect is used to a connection to the database.
