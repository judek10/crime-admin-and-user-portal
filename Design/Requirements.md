## Requirements

## Functional Requirements

* FR1 - The software shall allow the super admin be able to manage over the software with unlimited restraints.  (HIGH) (BR1)

* FR2 - The software shall allow the super admin to log in with authorization check. (HIGH) (BR1)

* FR3 - The software shall allow the super admin to create organizations for subscribed businesses. (HIGH) (BR1)

* FR4 - The software shall allow the super admin to assign admin to the organization. (HIGH) (BR2)

* FR5 - The software shall allow admin the ability to add/remove users. (HIGH) (BR3)

* FR6 - The software shall allow the admin to have all privileges of the user. (HIGH) (BR4)

* FR7 - The software shall allow the user to reset their password. (HIGH) (BR5)

* FR8 - The software shall allow the user to view their usage metrics. (MEDIUM) (BR6)

* FR9 - The software usage should include: (MEDIUM) (BR6)
    * number of cases
    * number of files
    * amount of minutes transcribed by user AND organization
    * most searched terms 
    * most hit terms

* FR10 - Super admins can edit all user information after they've been created (HIGH) (BR2)
* FR11 - Super admins can edit all organization information after they've been created (HIGH) (BR2)
* FR12 - The software shall allow super admin the ability to add/remove users. (HIGH) (BR3)
* FR13 - Admins can edit a user's username, email, and admin status after they've been created (HIGH) (BR2)
* FR14 - Implement AWS Cognito (HIGH) (BR2)
* FR15 - Add user metrics page for users (HIGH) (BR2)
* FR16 - Add login functionality for users (HIGH) (BR2)
* FR17 - Implement licensing for Admins (HIGH) (BR1)
* FR18 - Display allocated minutes vs minutes left in metrics as pie chart (HIGH) (BR1)
* FR19 - Deleting an organization displays modal with warning that users a part of organization will also be deleted (HIGH) (BR1)
* FR20 - Implement pagination for user manager, organizations, and user metrics (HIGH) (BR1)

## Non-functional Requirements

* NR1 - The software’s design should have simplistic pathing for administrators to perform functions. (HIGH) (BR1)
<?Such as going from one file, or section, to another without much problem?>

* NR2 - Administrators may select whether they are adding or removing a user. (High) (BR3)
   * When adding a user, their role can be assigned at their creation. 
   * Super administrators shall be able to remove both administrators and users.
   * However, administrators may only remove users, never super administrators or other administrators.
   <?Both can be a drop down, if adding a user is specified, the role assignment can appear or gain interactability?>

* NR3 - The user login page shall require verification in order to change or reset a password. (HIGH) (BR5)

* NR4 - The software shall be available as both a desktop, and a mobile page. (LOW) (BR6)

* NR5 - The software should have a response time <?process and load a page and its assets?> of 1 second or less. (MEDIUM) (BR6)
<?Arbitrary second count, this requirement more or less means that a function should be performed in a timely manner (page load, administrative action etc.)?>

* NR6 - Usage statistics shall automatically be updated upon their usage. (HIGH) (BR6)

* NR7 - The software should be available 99% of the time. (HIGH) (BR6)

* NR8 - Users may only view items within the organization(s) they are in. (HIGH) (BR6)

* NR9 - Pages should be stylistically consistent. (MEDIUM) (BR6)
