# tehnic.challenge

Basic login and signup app with 2 factor authentification

Work description:
“Write a aplication that allows you to acces a secure area using a two factor authentification mecanism.
Scenario :
Step 1: As a user I acces the application login screen .I enter my username and password .
Step 2: As  system I generate a one-time password (OTP) that is sent to user over email or sms. Every generated password should be valid for 120 seconds.
Step 3: As user, I enter the OTP code  on aplication login screen
Step 4: As system I have to  validate the OTP. If valid redirect the user to the secure area.
Your solution will be evaluated based on coding standards, naming conventions, project structure and the meeting of requirements. The use of unit testing is highly recommended.
Extra points added for improvements made to the given task and additions to the level of complexity”.

Details:
I used XAMPP to localy create and test the implementation, with some changes made to XAMPP so it can send emails for the OTP via the php.ini.
I created a basic login and signup forms app and also added a change password posibility, all of this use the OTP function.
I have tested localy all scenarios and had success with the implementation.
