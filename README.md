# Jira

Back to previous view
[UTMA20-419] Add suggestion dropdown for previously used email addresses Created: 21/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Improvement	Priority:	Low
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

Currently, users have to manually type in their email address every time they log in, even if they have used the same email address in the past. This can be time-consuming and inconvenient, especially for users who log in frequently. To improve the user experience, we should add a suggestion dropdown that shows previously used email addresses when the user starts typing their email address.
Acceptance Criteria:

When the user starts typing their email address in the login or registration form, a dropdown should appear with previously used email addresses.
The dropdown should be ordered by the most recently used email addresses first.
The user should be able to select a previously used email address from the dropdown, which will automatically populate the email address field.
If the user types in an email address that has not been used before, the suggestion dropdown should not appear.
The suggestion dropdown should be accessible and usable with a keyboard, without requiring the use of a mouse.




[UTMA20-418] Disable the 'Login' button when the email or password fields are empty. Created: 21/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Improvement	Priority:	Low
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

Currently, the 'Login' button can be clicked even when the email or password fields are empty. This improvement aims to make the login page more secure by disabling the 'Login' button when the email or password fields are empty.
Acceptance Criteria:

The 'Login' button should be disabled when the email or password fields are empty.




[UTMA20-417] Make the 'Forgot password?' button functional Created: 21/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Improvement	Priority:	High
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Issue Links:	
Blocks
blocks	UTMA20-340	Forgot Your Password Feature Not Func...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

Currently, the 'Forgot password?' button is not functioning. This improvement aims to make the 'Forgot password?' button functional by redirecting users to the 'Forgot password' page when they click it.
Acceptance Criteria:

When the user clicks the 'Forgot password?' button, they should be redirected to the 'Forgot password' page.




[UTMA20-416] Add loading spinner during login verification Created: 21/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Improvement	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Trivial

 Description 	 
Description:

Currently, when a user clicks on the 'Login' button, there is no indication that the system is processing the request. This can lead to confusion and frustration for users who may think the application is not responding. To improve the user experience, we propose adding a loading spinner to the login page that appears while the system is verifying the login credentials.
Acceptance Criteria:

A loading spinner should be added to the login page
The spinner should appear when the user clicks on the 'Login' button
The spinner should disappear once the login credentials have been verified
The spinner should not interfere with any other functionality on the login page
Additional informations:

By adding a loading spinner to the login page, we can provide users with a clear indication that the system is processing their request. This will help to reduce confusion and frustration, and improve the overall user experience.




[UTMA20-415]  Implement Login module for 'Wantsome booking' app Created: 21/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Story	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

As a user, I want to be able to login into the 'Wantsome booking' app so that I can access the full suite of functionalities available to registered users.
Acceptance Criteria:

      a) The 'Login' button should be visible on the landing page at the end of the content and on the header of the application present on every page for users who are not logged in.

      b) The 'Login' page should have the following functionalities:

'Don't have an account yet? Created one!' button. When pressed, the user will get redirected to the 'Register' page.
'Forgot password?' button. When pressed, the user will be redirected to the 'Forgot password' page
     c) The login functionality should have the following particularities:

Email field (mandatory field, validation of type {text}@{text}.{text}, 40 max characters)
Password field (mandatory field, validation is met if the following conditions are met: at least 8 characters, at least one uppercase letter, at least one lowercase letter, at least one number, at least one special character)
'Remember me' checkbox (if checked while the 'Login' button is pressed, the next times user accesses this app they will be automatically logged in)
Login button (if pressed and a correct combination of email and password is inserted, user is redirected to the Start page; if an incorrect combination is inserted, an error message appears)
Error message if an account with the provided email exists but using the wrong password: "You have inserted the wrong password!"
Error message if there isn’t an account using the provided email: “The credentials you inserted are incorrect!”
     d) The 'Login information' section should have the following fields:

First name (text field, mandatory field, accepts all types of characters, 30 max characters);
Last name (text field, mandatory field, accepts all types of characters, 30 max characters)
Email (mandatory field, validation of type {text}@{text}.{text}, 50 max characters)
Password (mandatory field, validation is met if the following conditions are met: at least 8 characters, at least one uppercase letter, at least one lowercase letter, at least one number, at least one special character)
Re-type password (mandatory field, has to be the same value as the password, validation is met if the following conditions are met: at least 8 characters, at least one uppercase letter, at least one lowercase letter, at least one number, at least one special character)
Tasks:

Create a 'Login' button and add it to the landing page and header of the application.
Implement the functionality for the 'Don't have an account yet? Created one!' button, redirecting the user to the 'Register' page.
Implement the functionality for the 'Forgot password?' button, redirecting the user to the 'Forgot password' page.
Create the 'Login' page with the email and password fields, 'Remember me' checkbox and 'Login' button.
Implement the validation rules for the email and password fields.
Implement the functionality for the 'Remember me' checkbox.
Implement the redirection to the Start page for successful logins and error messages for incorrect email/password combinations.
Create the 'Login information' section with the required fields.
Implement the validation rules for the fields in the 'Login information' section.
Ensure that all fields are mandatory and that the password and re-typed password fields match.
Add tests for all the implemented functionalities.
Definition of Done:

The Login page is fully functional and available for both registered and unregistered users.
The 'Login' button is visible on the landing page at the end of the content and on the header of the application, present on every page for unregistered users.
The 'Login' page has the 'Don't have an account yet? Create one!' button and 'Forgot password?' button, which redirect the user to the corresponding pages.
The login functionality requires an email and password to be entered, and validates the inputs according to the specified criteria.
If the combination of email and password is correct, the user is redirected to the Start page.
If an incorrect combination of email and password is inserted, an error message appears indicating the reason for the failure.
If an account with the provided email exists, but using the wrong password, the error message reads "You have inserted the wrong password!".
If there isn’t an account using the provided email, the error message reads “The credentials you inserted are incorrect!”.
The 'Remember me' checkbox allows the user to stay logged in across sessions.
The 'Login information' section has mandatory fields for first name, last name, email, password, and re-type password, which all have specific validation criteria.
The email and password fields have maximum character limits.
The registration process is fully functional and available to users who do not have an account.
The Login module is fully tested and free of bugs.
The Login module is integrated with the rest of the application and is deployed to the production environment.
 





[UTMA20-414]  'Remember me' Checkbox Not Present on Login Page Created: 20/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	High
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit

Attachments:	PNG File Remember me button not present .png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

The 'Remember me' checkbox is not present on the login page, even though it is specified in the functional requirements that it should be available. The absence of this feature is causing inconvenience to users who wish to stay logged in after closing the application.
Steps to Reproduce:

Open the Wantsome booking application on http://138.68.69.185:3333/.
Click on the 'Login' button.
Check if the 'Remember me' checkbox is present on the page.
Expected Result:

The 'Remember me' checkbox should be present on the login page, as specified in the functional requirements.
Actual Result:

The 'Remember me' checkbox is not present on the login page.
Reproducibility/ Frequency:

This issue is reproducible every time the login page is accessed.
Additional Information:

The absence of the 'Remember me' checkbox is causing inconvenience to users who have to log in every time they close the application.
This feature was specified in the functional requirements, and its absence violates the requirements.
The issue may be related to a UI bug or a misconfiguration of the login page.
Screenshot of the login page without the 'Remember me' checkbox is attached




[UTMA20-413] Verify an error message appears when using an incorrect combination of email and password. Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Error message .png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user has an valid account in the booking application.




[UTMA20-412] Verify the password field accepts input with at least 8 characters, one uppercase letter, one lowercase letter, one number, and one special character. Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	None
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File My account page .png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user has opened the Url: http://138.68.69.185:3333/
The user has an valid account, with a password in this format: at least 8 characters, one uppercase letter, one lowercase letter, one number, and one special character.
The user is on the'Login' oage




[UTMA20-411] Verify if email field accepts input with the correct format ({text}@{text}.{text}) and up to 40 characters. Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Login with 40 characters .png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user opens the Url : http://138.68.69.185:3333/
The user has a valid account already registered.




[UTMA20-410] Verify that when the 'Forgot password?' button is clicked on the Login page, the user is redirected to the 'Forgot password' page. Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	High
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Forgot your password-bug.png    
Issue Links:	
Blocks
blocks	UTMA20-340	Forgot Your Password Feature Not Func...	To Do
Relates
relates to	UTMA20-340	Forgot Your Password Feature Not Func...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Preconditions:

The user has a valid internet connection.
The user has not logged in to the application before.




[UTMA20-409]  Verify 'Don't have an account yet? Created one!' button redirects to the 'Register' page Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Register page.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user has a valid internet connection.
The user has not logged in to the application before.




[UTMA20-408] Verify 'Login' page is displayed after clicking the 'Login' button Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Login page is visible.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user has a valid internet connection.
The user has not logged in to the application before.




[UTMA20-407] Verify 'Login' button visibility for unregistered users Created: 20/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Low
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Login button is visible 1.png     PNG File Login button is visible.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user has a valid internet connection.
The user has not logged in to the application before.
 





[UTMA20-406] [Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application Created: 20/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	LoginFunction
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Name:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

As a team, we aim to develop a Login Module for the Wantsome Booking Application that allows users to log in to their account and manage their account details. The Login Module will provide a secure and user-friendly interface that is optimized for desktop and mobile devices. We need to create an epic to develop a Login Module that meets our customer's needs and expectations and provides them with a personalized and efficient booking experience when booking hotels in Romania.
Desired Outcome and/or Benefits:

Provide users with a personalized and efficient booking experience when booking hotels in Romania.
Increase customer satisfaction and loyalty by providing a user-friendly and easy-to-use Login Module.
Enable users to manage their account details, including login information, in one place.
Ensure the security and privacy of users' personal and financial information.
Business Value:

Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
Increased revenue from repeat bookings.
In Scope:

Develop a new and improved Login Module for the Wantsome Booking Application.
Implement a user login functionality.
Implement a My Account Details section with Login Information.
Provide a user-friendly interface that is optimized for desktop and mobile devices.
Ensure the security and privacy of users' personal and financial information.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing booking and payment modules.
Development of a secure and efficient Login Module.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing booking and payment modules.
Assumptions:

Users prefer a personalized and efficient booking experience when booking hotels in Romania.
Users prefer a mobile-optimized interface for managing their account details.
Users are willing to log in to their account to access personalized features.
References:

Existing login modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Implement a user login functionality.
Provide a My Account Details section with Login Information.
Ensure a seamless user experience throughout the Login Module.
Implement a secure Login Module that protects users' personal and financial information.




[UTMA20-348] User Profile Module not allowing the user to update Login Information Created: 06/Apr/23  Updated: 06/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	High
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit)

Attachments:	File Update informations.avi    
Issue Links:	
Blocks
blocks	UTMA20-329	User Profile Module for Wantsome Book...	To Do
Relates
relates to	UTMA20-329	User Profile Module for Wantsome Book...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

The User Profile Module for Wantsome Booking Application doesn't allows the user to manage their profile details, including Login Information such as First Name, Last Name, Email, Password, and Confirm Password.
Preconditions:

The user is logged into the Wantsome Booking Application with valid credentials.
Steps to reproduce:

Click on the user profile icon at the top right corner of the page.
Update the Login Information by entering new values for First Name, Last Name, Email, Password, and Confirm Password.
Click on the "Save Changes" button.
Expected Results:

The user is able to update the Login Information by entering new values for First Name, Last Name, Email, Password, and Confirm Password.
The user is able to click on the "Save Changes" button and the updated Login Information is successfully saved.
Actual Results:

The user is unable to update the Login Information in the User Profile Module. After entering new values for First Name, Last Name, Email, Password, and Confirm Password, clicking on the "Save Changes" button results in an error message stating that the changes could not be saved. This bug can be observed consistently.
Additional informations:

This bug is impacting the functionality of the User Profile Module and preventing users from updating their Login Information. This could negatively impact the user experience and result in a decrease in user engagement.
The developers should investigate the root cause of the issue and work on resolving it as soon as possible to ensure that the User Profile Module is functioning properly.
Testing should be done to confirm that the issue has been resolved before deploying the changes to the live website.




[UTMA20-347] Unable to Send Feedback in the Suggestions Section Created: 06/Apr/23  Updated: 06/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	High
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit)

Attachments:	File Suggestions.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Relates
relates to	UTMA20-332	Suggestions section	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

The objective of the Suggestions section in the Wantsome booking application is to provide personalized recommendations to users based on their search history and preferences. This feature should enhance the user experience by offering relevant options and increasing the chances of a successful booking.
Preconditions:

The user is on the landing page of the Wantsome Booking Application with the URL http://138.68.69.185:3333/
Steps to reproduce:

Look for the "Suggestions" section on the landing page.
Click on the "Suggestions" button.
Wait for the new page to load.
Check if the "Send Feedback" button is present on the new page.
Write a feedback in the box provided.
Click on the "Send Feedback" button.
Expected Results:

The user is able to successfully click on the "Send Feedback" button and the feedback is sent.
Actual Results:

The user is unable to send feedback in the Suggestions section. After clicking on the "Send Feedback" button, nothing happens, and the feedback is not sent. This bug can be observed consistently.
Additional informations:

This bug is impacting the functionality of the Suggestions section and preventing users from providing feedback. This could negatively impact the user experience and result in a decrease in user engagement. The developers should investigate the root cause of the issue and work on resolving it as soon as possible to ensure that the Suggestions section is functioning properly. Testing should be done to confirm that the issue has been resolved before deploying the changes to the live website.




[UTMA20-346] User is automatically logged out when refreshing the page Created: 06/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit)

Attachments:	File Logged out by refresh.avi    
Issue Links:	
Blocks
blocks	UTMA20-328	User Login Module for Wantsome Bookin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

The website is logging users out automatically when they refresh the page. This bug can be observed by logging into the website and then refreshing the page, which results in the user being logged out and directed back to the login page.
Precondition:

The user has already a valid account for the  Wantsome booking application
Steps to Reproduce:

Go to the Wantsome booking application at http://138.68.69.185:3333/
Log in to your account using valid credentials
Refresh the page
Expected Result:

The user remains logged in after refreshing the page.
Actual Result:

The user is automatically logged out after refreshing the page, without any confirmation or warning.
Reproducibility: Always

Workaround: Users can avoid this issue by logging back in after each page refresh.

Additional informations:

This issue was tested using a valid account and may affect other users as well.
The issue may be caused by a server-side timeout or a problem with session management.
The issue persists across multiple sessions and different browsers, indicating that it is a systemic issue rather than a local problem.




[UTMA20-345] User is able to register an account with only one letter, even for email field Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit)

Attachments:	File Register with c.avi    
Issue Links:	
Blocks
blocks	UTMA20-326	User Registration Module for Wantsome...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

On the Wantsome booking application, it is possible to register a new account using only one letter, for example the letter "c" on every field, including the email field. This allows users to bypass the application's validation checks and create an account with invalid or non-existent information.
Steps to reproduce:

Go to the Wantsome booking application at http://138.68.69.185:3333/
Click on the "Register" button at the top right of the page
Enter the letter "c" in every field on the registration form, including the email field
Submit the form by clicking the "Register" button at the bottom of the page
Expected result:

The application should validate the input and require valid information to be entered in each field, including the email field.
Actual result:

The application allows the user to register an account with only the letter "a" on every field, including the email field.
Additional Information :

This bug allows users to bypass the application's validation checks and create an account with invalid or non-existent information. This could lead to confusion and errors when attempting to use the application, and potentially compromise the security of user data.
The application should validate all input fields and require valid information to be entered before allowing users to register an account. Additionally, the email field should be validated to ensure that a valid email address is entered.




[UTMA20-344] No image displayed for Hotel of the day section on the landing page Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	BookingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Operating System: Windows 10 Pro, version 22H2
Browser: Google Chrome, version 111.0.5563.147 (Official Build) (64-bit

Attachments:	File Hotel of the day.avi    
Issue Links:	
Blocks
blocks	UTMA20-315	[Razvan Darasteanu]_[Unboxing] Hotel...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

The "Hotel of the Day" section on the landing page is not displaying an image, as intended. This bug can be observed by navigating to the landing page and seeing that the "Hotel of the Day" section is missing an image. Instead, a placeholder image or no image at all is displayed.
Steps to reproduce:

Open the Wantsome booking application on http://138.68.69.185:3333/
Scroll down on the landing page
Observe the Hotel of the day section
Expected result:

The Hotel of the day section should display an image of the hotel that is currently being featured.
Actual result:

The Hotel of the day section does not display any image. However, when refreshing the page, the image appears briefly but disappears after a new refresh of the page.
Reproducibility:

The issue can be reproduced consistently.
Additional information:

The issue occurs regardless of whether the user is logged in or not.
The issue appears to be intermittent, as the image of the Hotel of the day appears briefly but disappears quickly upon refreshing again the page.
No error messages are displayed when the issue occurs.
Workaround:

The user can try refreshing the page multiple times to see the image of the Hotel of the day, but this is not a reliable workaround.




[UTMA20-343] About Us section shows text in Latin language and lacks information in English Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File About Us.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

The "About Us" section on the website is not functioning as intended. The section is displaying text in Latin language and is missing important information that should be displayed in English. This bug can be observed by navigating to the "About Us" section of the website and seeing that the text is in Latin, making it difficult for users to understand the content.
Steps to reproduce:

Open the Wantsome booking application on http://138.68.69.185:3333/
Navigate to the bottom of the Wantsome booking application page
Click on the About Us section
Expected Result:

The About Us section should display information about the company in English.
Actual Result:

The About Us section displays text in Latin language and lacks information in English.
Additional Information:

Users might not be able to understand the information provided in the About Us section, which could impact their decision-making process or perception of the company.
The developers should update the About Us section of the website to include relevant information about the company in English language.




[UTMA20-342] Contact page displays text in Latin language Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2
Google Chrome, version 111.0.5563.147 (Official Build) (64-bit)

Attachments:	File Contact.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

The contact page on the website is displaying text in Latin language instead of the intended language. This issue can be observed by visiting the contact page and seeing that all the text on the page, including the headings, labels, and input fields are in Latin language.
Steps to reproduce:

Open the Wantsome booking application on http://138.68.69.185:3333/
Scroll down to the bottom of the page
Click on the "Contact" link
Expected result:

The Contact page should display information in English, including a contact form and contact details for the Wantsome booking application.
Actual result:

The Contact page displays text in Latin language, which is not understandable by most users. There is no contact form or contact details for the Wantsome booking application on this page.
Cause:

The developer likely forgot to update the Contact page with relevant information in English, and the Latin text may have been a placeholder that was not removed before deployment.
Additional Information:

The developer should update the Contact page with relevant information in English, including a contact form and contact details for the Wantsome booking application. The Latin text should be removed or replaced with English text. The developer should test the updated Contact page thoroughly to ensure that it is functioning as expected.




[UTMA20-341] Terms and Conditions section contains no English information Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Terms and Conditions.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

When clicking on the Terms and Conditions section at the bottom of the booking page on the Wantsome booking application, it opens a new page with a text in a latin language and no other information in English. This issue occurs regardless of whether the user is logged in or not.
Steps to Reproduce:

Open the Wantsome booking application on  http://138.68.69.185:3333/
Scroll down to the bottom of the booking page.
Click on the "Terms and Conditions" section.
Expected Result:

When the "Terms and Conditions" section is clicked, it should open a new page with the terms and conditions of the booking site in English.
Actual Result:

When the "Terms and Conditions" section is clicked, it opens a new page with a text in a latin language and no other information in English.
Additional Information:

Users who are not familiar with the Latin language may be unable to understand the information on the new page, which may result in confusion and frustration. Additionally, the lack of information in English may lead users to believe that the website is not reliable or trustworthy.




[UTMA20-340] Forgot Your Password Feature Not Functional Created: 05/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Forgot your password.avi    
Issue Links:	
Blocks
blocks	UTMA20-317	[Razvan Darasteanu]_[Unboxing] User ...	To Do
is blocked by	UTMA20-410	Verify that when the 'Forgot password...	To Do
is blocked by	UTMA20-417	Make the 'Forgot password?' button fu...	To Do
Relates
relates to	UTMA20-410	Verify that when the 'Forgot password...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Description:

When clicking on the "Forgot your password?" link on the login page of the Wantsome booking application, nothing happens. The link is supposed to allow users to reset their password by entering their email address, but it does not respond to user input. This behavior is observed regardless of whether the user is logged in or not and affects the functionality of the application by preventing users from resetting their password.
Precondition:

The user has already a valid account for the  Wantsome booking application
Steps to Reproduce:

Access the Wantsome booking application using the URL: http://138.68.69.185:3333/
Click on the "Login" button located in the top right corner of the page.
Enter your email and password or click on the "Dont have an account yet? Create one!" button to create a new account.
Click on the "Forgot your password?" link.
Observe that nothing happens and the feature does not respond to user input.
Expected Result:

When clicking on the "Forgot your password?" link, the application should open a new window or a modal, allowing users to enter their email address and reset their password.
Actual Result:

When clicking on the "Forgot your password?" link, nothing happens and the feature does not respond to user input.
Reproducibility:

The issue is reproducible consistently on the given environment and browser.
Additional Information:

The "Forgot your password?" link does not respond to user input, and there is no feedback or error message displayed to the user. The functionality of the link is crucial for users who forget their password and need to reset it. The inability to use this feature can affect the user experience and prevent users from using the application altogether.




[UTMA20-339] Easy Holiday Plan Wizard Feature Not Functional Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Easy holiday plan wizard.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Booking Application for Romanian Hotels, for the client Wantsome
Severity:	Major

 Description 	 
Description:

When clicking on the Easy Holiday Plan Wizard feature button located on the upper page of the Wantsome booking application, nothing happens. The button is supposed to allow users to access a wizard that helps them plan their holiday, but it does not respond to user input. This behavior is observed regardless of whether the user is logged in or not and affects the functionality of the application by preventing users from utilizing the holiday planning feature.
Steps to Reproduce:

Access the Wantsome booking application using the URL: http://138.68.69.185:3333/
Locate the Easy Holiday Plan Wizard feature button on the upper page.
Click on the Easy Holiday Plan Wizard feature button.
Observe that nothing happens and the feature does not respond to user input.
Expected Result:

When clicking on the Easy Holiday Plan Wizard feature button, the application should open a new window or a modal, allowing users to access the holiday planning wizard and plan their holiday.
Actual Result:

When clicking on the Easy Holiday Plan Wizard feature button, nothing happens and the feature does not respond to user input.
Reproducibility:

The issue is reproducible consistently on the given environment and browser.
Additional Information:

The Easy Holiday Plan Wizard feature button does not respond to user input, and there is no feedback or error message displayed to the user. The functionality of the button is crucial for users who need help planning their holiday, and the inability to use this feature can affect the user experience and prevent users from using the application altogether.




[UTMA20-338] Currency Exchange Feature Not Functional Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Currency exchange.avi    
Issue Links:	
Blocks
blocks	UTMA20-319	[Razvan Darasteanu]_[Unboxing] Admin...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Booking Application for Romanian Hotels, for the client Wantsome
Severity:	Major

 Description 	 
Description:

When clicking on the Currency Exchange feature button located on the upper page of the Wantsome booking application, nothing happens. The button is supposed to allow users to exchange currencies, but it does not respond to user input. This behavior is observed regardless of whether the user is logged in or not and affects the functionality of the application by preventing users from utilizing the currency exchange feature.
Steps to Reproduce:

Access the Wantsome booking application using the URL: http://138.68.69.185:3333/
Locate the Currency Exchange feature button on the upper page.
Click on the Currency Exchange feature button.
Observe that nothing happens and the feature does not respond to user input.
Expected Result:

When clicking on the Currency Exchange feature button, the application should open a new window or a modal, allowing users to exchange currencies and perform transactions.
Actual Result:

When clicking on the Currency Exchange feature button, nothing happens and the feature does not respond to user input.
Reproducibility:

The issue is reproducible consistently on the given environment and browser.
Additional Information:

The Currency Exchange feature button does not respond to user input, and there is no feedback or error message displayed to the user. The functionality of the button is crucial for users who need to book hotels in different currencies, and the inability to use this feature can affect the user experience and prevent users from using the application altogether.




[UTMA20-337] Random hotel Information appearing before selected hotel Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	HotelSearchModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Random Big Hotel.avi    
Issue Links:	
Blocks
blocks	UTMA20-314	[Razvan Darasteanu]_[Unboxing] Hotel...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Search Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

When clicking on any hotel in the Wantsome booking application, a random hotel called "Big Hotel" appears first for 1-2 seconds before the previously selected hotel appears with its details and photos. This behavior is observed regardless of whether the user is logged in or not and affects the user experience by displaying incorrect hotel information.
Steps to Reproduce:

Access the Wantsome booking application using the URL: http://138.68.69.185:3333/
Search and select any hotel from the list of available hotels.
Observe that for 1-2 seconds, the details and photos of a random hotel called "Big Hotel" appear before the selected hotel information is displayed.
Expected Result:

When clicking on a hotel, the application should immediately display the details and photos of the selected hotel without any delay or displaying information about a different hotel.
Actual Result:

When clicking on a hotel, the application displays the details and photos of a random hotel called "Big Hotel" before displaying the details of the selected hotel.
Reproducibility:

The issue is reproducible consistently on the given environment and browser.
Additional Information:

The random hotel information appears for only 1-2 seconds before the selected hotel information is displayed. It is unclear whether this is a design feature or a bug, but it can affect the user experience by displaying incorrect information.




[UTMA20-336] Add to Favorites Button Not Functioning Properly Created: 05/Apr/23  Updated: 06/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application running on http://138.68.69.185:3333/

Attachments:	File Add to favorites.avi    
Issue Links:	
Blocks
blocks	UTMA20-330	Favorites feature	To Do
Relates
relates to	UTMA20-330	Favorites feature	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
 

Description:

When clicking on the "Add to favorites" button in the Wantsome booking application, which is designed to add the hotel to the user's favorites list, nothing happens. The button has a heart icon, but it does not change color or indicate that the hotel has been added to the user's favorites list. This behavior is observed regardless of whether the user is logged in or not. 
Precondition:

 The user has already a valid account for the  Wantsome booking application
Steps to Reproduce:

Access the Wantsome booking application using the URL: http://138.68.69.185:3333/
Log in to the Wantsome booking application using valid credentials.
Search and select a hotel from the list of available hotels.
Click on the "Add to favorites" button located next to the hotel name.
Observe that nothing happens, and the heart icon on the button does not change.
Expected Result:

Clicking on the "Add to favorites" button should add the selected hotel to the user's favorites list and change the color of the heart icon on the button to indicate that the hotel has been added to the list.
Actual Result:

Clicking on the "Add to favorites" button does not add the hotel to the user's favorites list, and the heart icon on the button does not change.
Reproducibility:

The issue is reproducible consistently on the given environment and browser.
Additional Information:

The issue is observed regardless of whether the user is logged in or not. It is unclear whether the "Add to favorites" feature is implemented but not functioning correctly or if it is not implemented at all.
 





[UTMA20-335] Clicking the Booking Button Automatically Logs out the User without Permission Created: 05/Apr/23  Updated: 11/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Bug	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified
Environment:	
Windows 10 Pro, version 22H2 and Google Chrome, version 111.0.5563.147 (Official Build) (64-bit).
Wantsome booking application is running on http://138.68.69.185:3333/.

Attachments:	File Booking button.avi    
Issue Links:	
Blocks
blocks	UTMA20-334	Booking button/feature functionality	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Booking Application for Romanian Hotels, for the client Wantsome
Severity:	Major

 Description 	 
Description:

When clicking on the "Booking" button on the Wantsome booking application, which is designed to take the user back to the landing page, the application automatically logs out the user without asking for their permission. This behavior is observed only when the user is already logged in, and it does not occur when the user is not logged in.
Precondition:

 The user has already a valid account for the  Wantsome booking application
Steps to Reproduce:

Log in to the Wantsome booking application using valid credentials.
Navigate to any page within the application.
Click on the "Booking" button located in the header section of the website.
Observe that the application automatically logs out the user without asking for permission.
Expected Result:

The "Booking" button should take the user back to the landing page without logging them out of the application.
Actual Result:

Clicking the "Booking" button logs the user out of the application without asking for permission.
Reproducibility:

The issue is reproducible consistently.
Additional Information:

The issue occurs only when the user is logged in. When the user is not logged in, clicking on the "Booking" button takes them to the landing page without any issues.
Workaround:

Clicking on the back button, will keep the user logged in and the page will load the previous session.
 





[UTMA20-334] Booking button/feature functionality Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	BookingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Booking button.png     PNG File Selection' hotels.png    
Issue Links:	
Blocks
is blocked by	UTMA20-335	Clicking the Booking Button Automatic...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

The objective of the test case is to verify the functionality of the "Booking" button/feature in the Wantsome booking application. When the user presses the "Booking" button/feature, it should return them to the home page from wherever they are on the website. This test case aims to ensure that the "Booking" feature works as intended and provides a smooth user experience.
 





[UTMA20-333] Hotels' Selection feature from the landing page Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	HotelSearchModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Selection' hotels.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Search Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

The "Hotels' Selection" feature, from photos, on the Wantsome booking application landing page allows users to select a hotel based on its photo. When the user clicks on a photo, they are taken to a page that displays more information about the hotel and allows them to book a room.





[UTMA20-332] Suggestions section Created: 05/Apr/23  Updated: 06/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	RatingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Feedback.png    
Issue Links:	
Relates
relates to	UTMA20-347	Unable to Send Feedback in the Sugges...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] Rating Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

The objective of the Suggestions section in the Wantsome booking application is to provide personalized recommendations to users based on their search history and preferences. This feature should enhance the user experience by offering relevant options and increasing the chances of a successful booking.
Preconditions:

The user is on the landing page of the Wantsome Booking Application with the URL http://138.68.69.185:3333/
No login is required




[UTMA20-331] Amenities feature Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	BookingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Amenities.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

The objective of the test case for the Amenities feature in the Wantsome booking application is to ensure that the amenities listed for a particular property are accurately displayed on the application, and that users are able to view and filter properties based on their desired amenities.
Preconditions:

The user has access to the Wantsome Booking Application website.
The user is logged on the home page of the website.




[UTMA20-330] Favorites feature Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Favorites.png    
Issue Links:	
Blocks
is blocked by	UTMA20-336	Add to Favorites Button Not Functioni...	To Do
Relates
relates to	UTMA20-336	Add to Favorites Button Not Functioni...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Preconditions:

The user must be registered on the Wantsome Booking Application
The user must be logged in
The user must have accessed the Wantsome Booking Application homepage




[UTMA20-329] User Profile Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 06/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Error My account.png    
Issue Links:	
Blocks
is blocked by	UTMA20-348	User Profile Module not allowing the ...	To Do
Relates
relates to	UTMA20-348	User Profile Module not allowing the ...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

To verify that the User Profile Module for Wantsome Booking Application allows the user to manage their profile details, view their favorites and logout from the application.
Preconditions:

The user is already registered with the Wantsome Booking Application.
The user has logged in to the application with their valid credentials.




[UTMA20-328] User Login Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Login.png    
Issue Links:	
Blocks
is blocked by	UTMA20-346	User is automatically logged out when...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Login Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

To verify that the User Login Module for Wantsome Booking Application allows the user to login to the application successfully.
Preconditions:

The user is already registered into the Wantsome Booking Application.
The user has a valid email and password associated with their account.




[UTMA20-326] User Registration Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Register.png    
Issue Links:	
Blocks
is blocked by	UTMA20-345	User is able to register an account w...	To Do
Epic Link:	[Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

To verify that the User Registration Module for Wantsome Booking Application allows the user to create a new account successfully.
Preconditions:

The user is not currently registered with the Wantsome Booking Application.
The user has access to a valid email address to complete the registration process.




[UTMA20-325] Hotel Payment Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	PaymentModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Book holiday1.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] Payment Module for the Wantsome Booking Application
Severity:	Major

 Description 	 
Objective:

To verify that the Hotel Payment Module for Wantsome Booking Application allows the user to make a payment for the hotel reservation successfully.




[UTMA20-323] Hotel Booking Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	BookingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Book holiday.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

To verify that the Hotel Booking Module for Wantsome Booking Application allows the user to book a hotel room successfully with the selected options and payment method.
Preconditions:

The user has a valid account for the Wantsome Booking Application.




[UTMA20-321] Hotel Search Module for Wantsome Booking Application Created: 05/Apr/23  Updated: 05/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Test	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	HotelSearchModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Attachments:	PNG File Hotel Iasi.png    
Epic Link:	[Razvan Darasteanu]_[Unboxing] Hotel Search Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Objective:

To verify that the Hotel Search Module for Wantsome Booking Application returns the correct results based on the selected filters  for hotels located in Iasi, Romania.




[UTMA20-319]  [Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	AdminModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Issue Links:	
Blocks
is blocked by	UTMA20-347	Unable to Send Feedback in the Sugges...	To Do
is blocked by	UTMA20-338	Currency Exchange Feature Not Functional	To Do
is blocked by	UTMA20-339	Easy Holiday Plan Wizard Feature Not ...	To Do
is blocked by	UTMA20-341	Terms and Conditions section contains...	To Do
is blocked by	UTMA20-342	Contact page displays text in Latin l...	To Do
is blocked by	UTMA20-343	About Us section shows text in Latin ...	To Do
Epic Name:	 [Razvan Darasteanu]_[Unboxing] Admin Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

As a team, we aim to develop an admin module for the Wantsome Booking Application that allows the admin to manage and monitor the platform's functionality and performance. The admin module will provide the admin with the tools necessary to manage users, bookings, payments, hotels, and reviews. We need to create an epic to develop an admin module that meets our customer's needs and expectations and provides the admin with the necessary tools to manage and monitor the platform.
Desired Outcome and/or Benefits:

Provide the admin with the necessary tools to manage and monitor the platform.
Enable the admin to manage users, bookings, payments, hotels, and reviews.
Ensure the security and privacy of users' personal and financial information.
Provide the admin with insights into platform performance and user behavior.
Business Value:

Increased efficiency and effectiveness in managing the platform.
Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
Increased revenue from repeat bookings.
In Scope:

Develop a new and improved admin module for the Wantsome Booking Application.
Implement a user management functionality to manage user accounts and roles.
Implement a booking management functionality to manage and monitor bookings.
Implement a payment management functionality to manage and monitor payments.
Implement a hotel management functionality to manage and monitor hotels.
Implement a review management functionality to manage and monitor reviews.
Ensure the security and privacy of users' personal and financial information.
Provide the admin with insights into platform performance and user behavior.
Precondition:

User research and analysis to identify admin needs and expectations.
Integration with existing hotel search, booking, and payment modules.
Development of a secure and efficient admin module.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing booking and payment modules.
Assumptions:

The admin needs a comprehensive set of tools to manage and monitor the platform effectively.
The admin needs insights into platform performance and user behavior to make informed decisions.
The admin needs a secure and efficient admin module that protects users' personal and financial information.
References:

Existing admin modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Implement a user management functionality to manage user accounts and roles.
Implement a booking management functionality to manage and monitor bookings.
Implement a payment management functionality to manage and monitor payments.
Implement a hotel management functionality to manage and monitor hotels.
Implement a review management functionality to manage and monitor reviews.
Provide the admin with insights into platform performance and user behavior.
Implement a secure admin module that protects users' personal and financial information.




[UTMA20-318]  [Razvan Darasteanu]_[Unboxing] Rating Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	RatingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Name:	 [Razvan Darasteanu]_[Unboxing] Rating Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

As a team, we aim to develop a rating module for the Wantsome Booking Application that allows users to rate the hotels they have stayed at. The rating module will provide valuable feedback to other users who are considering booking the same hotel and help them make informed decisions. We need to create an epic to develop a rating module that meets our customer's needs and expectations and provides them with a platform to share their experiences and opinions.
Desired Outcome and/or Benefits:

Enable users to rate and review hotels they have stayed at.
Provide valuable feedback to other users who are considering booking the same hotel.
Help users make informed decisions when booking hotels in Romania.
Increase customer engagement and participation on the platform.
Business Value:

Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
Increased revenue from repeat bookings.
In Scope:

Develop a new and improved rating module for the Wantsome Booking Application.
Implement a rating and review functionality for hotels.
Enable users to rate hotels based on various criteria such as cleanliness, comfort, location, and service.
Provide a user-friendly interface that is optimized for desktop and mobile devices.
Implement a moderation system to ensure the quality and relevance of reviews.
Ensure the security and privacy of users' personal and financial information.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing hotel search and booking modules.
Development of a secure and efficient rating module.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing booking and payment modules.
Assumptions:

Users value the opinions and experiences of other users when making booking decisions.
Users are willing to share their experiences and opinions on the platform.
Users are willing to participate in a rating and review system.
References:

Existing rating and review systems in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Implement a rating and review functionality for hotels.
Provide a moderation system to ensure the quality and relevance of reviews.
Ensure a seamless user experience throughout the rating module.
Implement a secure rating module that protects users' personal and financial information.




[UTMA20-317]  [Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 21/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	UserProfileModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Issue Links:	
Blocks
is blocked by	UTMA20-340	Forgot Your Password Feature Not Func...	To Do
Epic Name:	 [Razvan Darasteanu]_[Unboxing] User Profile Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

As a team, we aim to develop a user profile module for the Wantsome Booking Application that allows users to register an account, log in to it, and manage their account details. The user profile module will have two sections: My Account Details, with Login Information and Personal Information (optional), and Favorites, where users can view the history of the hotels they have visited on the website and the favorite hotels they have added. We need to create an epic to develop a user profile module that meets our customer's needs and expectations and provides them with a personalized and efficient booking experience when booking hotels in Romania.
Desired Outcome and/or Benefits:

Provide users with a personalized and efficient booking experience when booking hotels in Romania.
Increase customer satisfaction and loyalty by providing a user-friendly and easy-to-use user profile module.
Enable users to manage their account details, including login information and personal information, in one place.
Enable users to view their booking history and favorite hotels in one place, making it easier to manage their bookings and preferences.
Business Value:

Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
Increased revenue from repeat bookings.
In Scope:

Develop a new and improved user profile module for the Wantsome Booking Application.
Implement a user registration and login functionality.
Implement a My Account Details section with Login Information and Personal Information (optional).
Implement a Favorites section where users can view the history of the hotels they have visited on the website and the favorite hotels they have added.
Provide a user-friendly interface that is optimized for desktop and mobile devices.
Ensure the security and privacy of users' personal and financial information.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing booking and payment modules.
Development of a secure and efficient user profile module.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing booking and payment modules.
Assumptions:

Users prefer a personalized and efficient booking experience when booking hotels in Romania.
Users prefer a mobile-optimized interface for managing their account details and favorites.
Users are willing to register an account to access personalized features.
References:

Existing user profile modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Implement a user registration and login functionality.
Provide a My Account Details section with Login Information and Personal Information (optional).
Provide a Favorites section where users can view the history of the hotels they have visited on the website and the favorite hotels they have added.
Ensure a seamless user experience throughout the user profile module.
Implement a secure user profile module that protects users' personal and financial information.




[UTMA20-316]  [Razvan Darasteanu]_[Unboxing] Payment Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	PaymentModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Name:	 [Razvan Darasteanu]_[Unboxing] Payment Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

As a team, we aim to develop a payment module for the Wantsome Booking Application that allows users to pay for their bookings directly from the application. The payment module will offer various payment options, including bank transfer, credit card, and pay at the property. Additionally, the payment module will allow users to enter coupon codes during the payment process. We need to create an epic to develop a new and improved payment module that meets our customer's needs and expectations and provides them with a seamless payment experience when booking hotels in Romania.
Desired Outcome and/or Benefits:

Provide users with a seamless and secure payment experience when booking hotels in Romania.
Increase customer satisfaction and loyalty by providing a reliable and efficient payment processing functionality.
Enable users to easily pay for their hotel bookings in Romania, resulting in a more streamlined payment experience.
Attract more customers and increase revenue by providing a flexible and efficient payment processing platform for Romanian hotels.
Business Value:

Increased revenue from hotel bookings.
Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
In Scope:

Develop a new and improved payment module for the Wantsome Booking Application.
Implement a payment processing functionality that accepts various payment methods such as bank transfer, credit card, and pay at the property.
Implement a coupon code functionality that allows users to enter coupon codes during the payment process.
Provide a secure payment processing functionality that protects users' personal and financial information.
Implement a user-friendly interface that is optimized for desktop and mobile devices.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing payment gateways and systems in Romania.
Development of a secure and efficient payment processing system.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing payment gateways and systems.
Assumptions:

Users prefer a seamless and secure payment experience when booking hotels in Romania.
Integration with existing payment gateways and systems in Romania is feasible.
Users prefer a mobile-optimized interface for payment processing.
References:

Existing payment modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Implement a payment processing functionality that accepts various payment methods such as bank transfer, credit card, and pay at the property.
Provide a coupon code functionality that allows users to enter coupon codes during the payment process.
Ensure a seamless user experience throughout the payment process.
Implement a secure payment processing functionality that protects users' personal and financial information.




[UTMA20-315]  [Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	BookingModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Issue Links:	
Blocks
is blocked by	UTMA20-344	No image displayed for Hotel of the d...	To Do
Epic Name:	 [Razvan Darasteanu]_[Unboxing] Hotel Booking Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description:

As a team, we aim to develop a hotel booking module for the Wantsome Booking Application that allows users to book hotels directly from the application. Currently, the application lacks this functionality, which can significantly improve the user experience and increase business value. Therefore, we need to create an epic to develop a new and improved hotel booking module that can meet our customer's needs and expectations and provide them with a seamless experience when booking hotels in Romania.
Desired Outcome and/or Benefits:

Increase customer satisfaction and loyalty by providing a seamless and secure hotel booking experience.
Attract more customers and increase revenue by providing a reliable and efficient hotel booking platform for Romanian hotels.
Improve the hotel booking process by providing users with more accurate and up-to-date information about hotels in Romania.
Enable users to easily book hotels in Romania, resulting in a more streamlined booking experience.
Business Value:

Increased revenue from hotel bookings.
Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
In Scope:

Develop a new and improved hotel booking module for the Wantsome Booking Application.
Implement a hotel booking function that allows users to select the dates of stay and the number of guests.
Implement a secure payment processing functionality that accepts various payment methods such as credit cards.
Provide accurate and up-to-date information about the hotels in Romania, including availability, prices, and booking terms.
Implement a user-friendly interface that is optimized for desktop and mobile devices.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing hotel databases in Romania.
Development of a secure and efficient payment processing system.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing hotel databases.
Assumptions:

Users prefer a seamless and secure hotel booking experience.
Integration with existing hotel databases in Romania is feasible.
Users prefer a mobile-optimized interface for hotel booking.
References:

Existing hotel booking modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Use high-quality images and descriptions of the hotels available to help users make an informed decision.
Implement a hotel booking function that allows users to select the dates of stay and the number of guests.
Ensure a seamless user experience throughout the hotel booking process.
Implement a secure payment processing functionality that accepts various payment methods such as credit cards.




[UTMA20-314]  [Razvan Darasteanu]_[Unboxing] Hotel Search Module for the Wantsome Booking Application Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	HotelSearchModule
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Issue Links:	
Blocks
is blocked by	UTMA20-337	Random hotel Information appearing be...	To Do
Epic Name:	 [Razvan Darasteanu]_[Unboxing] Hotel Search Module for the Wantsome Booking Application
Severity:	Minor

 Description 	 
Description: 

As a team, we aim to develop a hotel search module for the Wantsome Booking Application that enables users to search and filter hotels based on various criteria, including location, price, rating, and amenities. The current application lacks this essential functionality, which can significantly improve the user experience and increase business value. Therefore, we need to create an epic to develop a new and improved hotel search module that can meet our customer's needs and expectations and provide them with a seamless experience when searching for hotels in Romania.
Desired Outcome and/or Benefits:

Increase customer satisfaction and loyalty by providing a comprehensive and user-friendly hotel search module.
Attract more customers and increase revenue by providing a reliable and efficient hotel search platform for Romanian hotels.
Improve the hotel search process by providing users with more accurate and up-to-date information about hotels in Romania.
Enable users to easily search and filter hotels in Romania, resulting in a more streamlined hotel search experience.
Business Value:

Increased revenue from hotel bookings.
Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
In Scope:

Develop a new and improved hotel search module for the Wantsome Booking Application.
Implement a hotel search function that allows users to filter hotels by room type, price per room, maximum number of guests per room, traveling reason, rating and breakfast included option.
Implement a real-time search functionality that displays search results as users type.
Provide accurate and up-to-date information about the hotels in Romania, including images, descriptions, and reviews.
Implement a user-friendly interface that is optimized for desktop and mobile devices.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing hotel databases in Romania.
Development of a secure and efficient search algorithm.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing hotel databases.
Assumptions:

Users prefer a comprehensive and user-friendly hotel search module.
Integration with existing hotel databases in Romania is feasible.
Users prefer a mobile-optimized interface for hotel search.
References:

Existing hotel search modules in other booking applications.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for desktop and mobile devices.
Use high-quality images and descriptions of the hotels available to help users make an informed decision.
Implement a real-time search functionality that displays search results as users type.
Implement a hotel search function that allows users to filter hotels by location, price, rating, and amenities.
Ensure a seamless user experience throughout the hotel search process.




[UTMA20-313]  [Razvan Darasteanu]_[Unboxing] Booking Application for Romanian Hotels, for the client Wantsome Created: 05/Apr/23  Updated: 20/Apr/23
Status:	To Do
Project:	Unboxing - TM+TA 20
Component/s:	None
Affects Version/s:	None
Fix Version/s:	None

Type:	Epic	Priority:	Medium
Reporter:	Razvan Darasteanu	Assignee:	Razvan Darasteanu
Resolution:	Unresolved	Votes:	0
Labels:	ApplicationDevelopment
Remaining Estimate:	Not Specified
Time Spent:	Not Specified
Original Estimate:	Not Specified

Epic Name:	 [Razvan Darasteanu]_[Unboxing] Booking Application for Romanian Hotels, for the client Wantsome
Severity:	Minor

 Description 	 
Description:

As a team, we aim to create a comprehensive booking application for Romanian hotels that allows users to search, compare, and book hotels in Romania. The current application lacks essential features and functionality that can improve the user experience and increase business value. Therefore, we need to create an epic to develop a new and improved booking application that can meet our customer's needs and expectations and provide them with a seamless experience when booking a hotel in Romania.
Desired Outcome and/or Benefits:

Increase customer satisfaction and loyalty by providing a user-friendly and comprehensive booking application.
Attract more customers and increase revenue by providing a reliable and efficient booking platform for Romanian hotels.
Improve the booking process by providing users with more accurate and up-to-date information about hotels in Romania.
Enable users to easily search, compare, and book hotels in Romania, resulting in a more streamlined booking experience.
Business Value:

Increased revenue from hotel bookings.
Increased customer satisfaction and loyalty.
Competitive advantage over other booking platforms.
In Scope:

Develop a new and improved booking application for Romanian hotels.
Develop a hotel search function that allows users to filter hotels by price, location, and amenities.
Implement a booking feature that enables users to book hotels directly from the application.
Implement a customer support feature that enables users to contact customer support if they have any questions or concerns.
Develop a user-friendly interface that is optimized for mobile devices.
Implement a secure payment gateway for hotel bookings.
Precondition:

User research and analysis to identify user needs and expectations.
Integration with existing hotel databases in Romania.
Development of a secure payment gateway.
Constraints:

Time constraints for development and testing.
Budget constraints for development and integration.
Technical constraints for integration with existing hotel databases.
Assumptions:

Users prefer a comprehensive and user-friendly booking application.
Integration with existing hotel databases in Romania is feasible.
Users prefer a mobile-optimized interface for booking hotels.
References:

Existing booking applications for Romanian hotels.
User research and analysis.
UX/UI:

Develop a user-friendly interface that is optimized for mobile devices.
Use high-quality images and descriptions of the hotels available to help users make an informed decision.
Implement a hotel search function that allows users to filter by room type, price per room, maximum number of guests per room, traveling reason, rating and breakfast included option.
Implement a booking feature that enables users to book hotels directly from the application.
Implement a customer support feature that enables users to contact customer support if they have any questions or concerns.
Ensure a seamless user experience throughout the booking process.




Generated at Thu Jan 18 00:30:13 CET 2024 by Razvan Darasteanu using Jira 8.11.1#811002-sha1:94cd71673c1ee8e9bd5252bb36412489f4133687.
