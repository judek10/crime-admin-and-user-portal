# Application Step-by-Step Guide

## First step
In order to run the application correctly, both the back-end and front-end projects must be running at the same time. 

## Login Page
When first starting the application the login page will appear: ![image](https://user-images.githubusercontent.com/77819572/206339809-4883e89a-f5d6-4198-abec-1ee52a569995.png)

Type the following information to login:
-For admin privileges
  - Email: ballstateadmin@bsu.edu 
  - Password: password

-For super admin privileges
  - Email: ballstateuser1@bsu.edu 
  - Password: password

## Super-Admin page
After logging in, the web app will redirect the user to super-admin page. This is where the super-admin can create organizations and add/remove/edit users.

![image](https://user-images.githubusercontent.com/77819572/206339999-91a995ab-4475-42fd-aa20-960035b79fa7.png)


- Clicking on "Add Organizations" will redirect the user to the Organization page.
- Clicking on "User Manager" will redirect the user to the User page.
- Clicking on "Log Out" will redirect the user back to the login page.

## Organization Page
Upon loading the Organization Page, there's an area to input a new organization. Underneath the input area is where all organizations are listed with their ID and name. The "back to main" button will redirect the user back to the god-mode page.
![image](https://user-images.githubusercontent.com/77819572/206340140-0379a0c0-8970-4ca7-a630-198e49fac8c6.png)

## User Page
Upon loading the User Page, there's an area to input a new user. Underneath the input area is where all users are listed with their ID, email, if they're an admin, and organization. The "back to main" button will redirect the user back to the super-admin page. Clicking the delete button allows the user to confirm if he wants to delete them or not. The edit button pops up a modal that allows the user to edit information and submit.
<img width="960" alt="2023-02-06 (1)" src="https://user-images.githubusercontent.com/97480348/217129743-b77d53bb-22b4-4922-b76e-0a586f645cc2.png">
<img width="960" alt="2023-02-06 (2)" src="https://user-images.githubusercontent.com/97480348/217130033-01fd9652-0105-46e9-bdf3-ca5c7edaa209.png">

<img width="948" alt="2023-02-06 (3)" src="https://user-images.githubusercontent.com/97480348/217130201-acfcadd2-a38c-4e9c-a007-38228c1794b0.png">

## Admin page
After logging in with the correct information, the web app will redirect the user to admin page. This is where the admin of an organization can choose to add/remove/edit users as well as see their user metrics. 
<img width="960" alt="2023-02-06 (4)" src="https://user-images.githubusercontent.com/97480348/217132142-bd57abc4-879b-4008-b4b8-695ec53592f9.png">


## Admin User Manager 

Upon loading the User Page, there's an area to input a new user. Underneath the input area is where all users are listed with their ID, email, if they're an admin, and it automatically assigns them the organization associated with the logged in admin. The "back to main" button will redirect the user back to the super-admin page. Clicking the delete button allows the user to confirm if he wants to delete them or not. The edit button pops up a modal that allows the user to edit information and submit.
<img width="960" alt="2023-02-06 (5)" src="https://user-images.githubusercontent.com/97480348/217131263-72e5fb16-2ebe-405a-9759-cc4cc5a97fa8.png">
<img width="960" alt="2023-02-06 (2)" src="https://user-images.githubusercontent.com/97480348/217130033-01fd9652-0105-46e9-bdf3-ca5c7edaa209.png">

<img width="948" alt="2023-02-06 (3)" src="https://user-images.githubusercontent.com/97480348/217130201-acfcadd2-a38c-4e9c-a007-38228c1794b0.png">
