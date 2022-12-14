# User Register

### Register Screen

The process of converting anonymous user who have just installed our enerlytics app happens on this screen. It is crucial 
for the app functionality otherwise anonymous can not operate the app without registering and creating a profile. The process only requires minimal data to get started. 

| <img src="./images/profile/Screenshot_1669863373.png" style="zoom:25%;" /> |
| ------------------------------------------------------------ |

User provides their full names; first and last name, email address, mobile phone number,
and a unique password. All these data is required to be able to submit registration form. In case any is omitted an error and
prompt message is show below the form to indicate the value is required. The password should be a minimum of 5 characters and can contain
alphanumeric and special characters. The user is requested to type both fields password field to ensure user can remember the password 
during the login process. At the end of each password field, user can toggle the visibility of the password. This helps the user to read
the typed content to confirm both password are similar. When user finishes entering the data in all the fields, users are provide a disclaimer
to read the term and conditions. This is important since it describes our commitment to ensure user privacy for any personal data provided.
The full content of terms and condition can be read on this link. After reading the whole document user is expected to agree to the term
and conditions. However its worth noting the agreement is not a strict requirement to submit the registration form. The user can now tap
on the registration submit button. This start a background process which validates and submits the data to the server. Its worth noting Internet connection is required 
for this process.  A pop up progress bar is shown to indicate the connection and the message returned from the server. If the registration is successful user can proceed 
to the Phone/Email authentication page. Check the possible error messages in case the registration fails and how to fix them.

| <img src="images/profile/Screenshot_2022-12-26-10-20-34-813.jpg" style="zoom:50%;" /> | <img src="images/profile/Screenshot_2022-12-26-10-20-42-696.jpg" style="zoom:50%;" /> | <img src="images/profile/Screenshot_2022-12-26-10-20-56-675.jpg" style="zoom:50%;" /> |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |



### Two-factor Code Authentication Screen

This screen authenticates phone number and email they have registered are valid. This is commonly referred as two factor authentication. 
It allows the enerlytics team forward important message via email and SMS. In case the user didn't receive a message a link below the code field that allows the user to
resend the code. The process of code authentication can be skipped if the user taps on login button. This is does not escape the authentication but reduces the registration process for a user in a hurry.
In case user entered wrong data in either email or phone, a profile update is 
show below the resend code link. Check the system design to learn more about the code authentication process. This process also requires an Internet connection.
Check the possible error messages in case the authentication fails and how to fix them. When the code is successfully authenticated, user can proceed to login

| <img src="images/profile/Screenshot_2022-12-26-10-21-51-622.jpg" style="zoom:50%;" /> | <img src="images/profile/Screenshot_2022-12-26-10-19-04-745.jpg" style="zoom:50%;" /> | <img src="images/profile/Screenshot_2022-12-26-10-22-01-060.jpg" style="zoom:50%;" /> |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
