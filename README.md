# P.A.S.S.
Parking Availability Surveillance System for Software Engineering Class. This repository will hold the code to showcase 3 functional requirements.

4.1 Account Creation

4.1.3 ​Functional Requirements
ACC-1:​System will require users to create a username with a 5 character minimum and 12 character max that must use a variation of letters and numbers.
ACC-2:​System will require users to create a password with a 5 character minimum and a 15 characters max with at least 1 symbol, 1 uppercase letter, and 1 lowercase letter.
ACC-3:​System will require users to indicate yes or no to having a reserved parking pass.
ACC-4:​System will require users to indicate yes or no to having a handicap parking pass.
ACC-5:​System will require users to indicate if they are staff, faculty, student, or visitor.
ACC-6:​ If the system see’s that the user is a student, the system will require the user to indicate whether they are a commuter or on-campus student.
ACC-7: System will require users to share their location.
ACC-8:​ System will require students to enter their student ID number.
ACC-9:​​ If the system see’s an on-campus student, it will require the user to indicate which dormitory they live in.
ACC-10: System will require users to enter their decal number.
ACC-11:​​ System will require all fields to be completed according to the constraints for an account to be successfully created.
ACC-12: System will display error messages when constraints are not followed.
ACC-13: System will save all account information to the system account database.

4.2 User Can View Available Parking
4.2.1 ​Description and Priority
P.A.S.S. will allow each user with an account to select a building/area they want to go to and view the available parking for them based on their account information and parking pertaining to the selected building. Viewing available parking will be a high priority because that is the main function of the application.
4.2.2​ Stimulus/Response Sequences
A map of Norfolk State University’s campus will be displayed along with various options for users' destinations. Users will indicate which building or area they want to go to and the application will use the user’s account information,  location, and data from parking sensors to display available parking to the user. 
4.2.3 ​Functional Requirements
AV-1:​System will read account information and use the information to indicate which parking lots and spots are available for the user to park in.
AV-2:​System will use data from parking sensors to indicate which spots are occupied or empty.
AV-3:​System will use the user's location to determine which parking lot they have parked in.



4.3 User Can Indicate When Parked
4.3.1 ​Description and Priority
P.A.S.S. will allow each user with an account to indicate when they have parked. Users indicating when they have parked is low priority because it isn’t necessary for the application to service its purpose but it helps determine exactly where and when the user has parked and if it is a good or bad parking space.
4.3.2​ Stimulus/Response Sequences

P.A.S.S. will display a button for a user to indicate if they are parked. If the user presses the button the application will use the account data and user location to display if they are in a good or bad park. If the park is indicated to be a lot the user is not eligible to park in by the system, the user has an option to agree or disagree with the system’s conclusion.
4.3.3​ Functional Requirements
 
IND-1:​System will display a slider to indicate if the user has parked, or moved from a parking space
IND-2:​System will use the user's location and parking indication to conclude if the park is good or bad and display the conclusion. 
4.4 P.A.S.S. Will Track User Location
4.2.1 ​Description and Priority
P.A.S.S. will allow each user with an account to select a building/area they want to go to and view the available parking for them based on their account information and parking pertaining to the selected building. Viewing available parking will be a high priority because that is the main function of the application.
4.2.2​ Stimulus/Response Sequences

A map of the campus will be displayed along with various options for users destinations. Users will indicate which building or area they want to go to and the application will use the user’s account information,  location, and data from parking sensors to display available parking to the user. 
4.2.3​ Functional Requirements
 
 
LOC-1:​System will read account information and use the information to indicate which parking lots and spots are available for the user to park in.
LOC-2:​System will use data from parking sensors to indicate which spots are occupied or empty.
LOC-3:​System will use the user's location to determine which parking lot they have parked in.

4.5 The Application Should Display Messages to the Users’ Screens
4.5.1 ​Description and Priority
P.A.S.S. will have various situations where it will alert a user of certain things. This is a medium priority feature as it is not necessary for the functionality of the application, but it will help users have a smoother process.
4.5.2​ Stimulus/Response Sequences

A message trigger will occur and the system will have a pop-up to alert the user. The pop-up will have an ‘X’ button for the user to move the message after they have read it. 
4.5.3 ​Functional Requirements
 
 
REQ-1: If the user has been inactive for 2 minutes and 30 seconds a message will pop up alerting the user that they will be signed out soon.
REQ-2:​ The system will also have a pop up if the user attempts to submit their account creation form with fields be improperly filled
REQ-3: The system will have a pop up if the user attempts to login to their account and their username is not found or their password is incorrect.



