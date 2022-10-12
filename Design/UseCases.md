# Actors
- Super Admin - Can create organizations and assign admins.
- Admin - Can add or remove users (bound by seat/license limit).
- User - Can reset password and view usage metrics.

# Use Cases
* UC1
  *  Create Organizations
  *  Actor: Super Admin
  *  The Super Admin can create organizations for the portal.
  *  Business requirement - BR2
  *  This use case corresponds with the second business requirement. UC1 is important for the functionality of the Super Admin, as it gives them the ability to create organizations on the portal. Organizations are made for the different companies/customers using this application such as call centers, attorneys, and insurance companies. The functionality to create organizations is important when first setting up the application for companies.

* UC2
  * Assign Admins
  * Actor: Super Admin and Admin
  * The Super Admin and Admin can assign admin permissions to users.
  * Business requirement - BR2
  * This use case also corresponds with the second business requirement. UC2 is another important part of what the Super Admin and Admin can do since it lets them assign Admins. Admins have special permissions that allow them to add and remove users. This functionality is important when first setting up the application's admin and user accounts.

* UC3
  * Add and remove users
  * Actor: Super Admin and Admin
  * Admins have the ability to add and remove users from the portal. They are bound by the seat/license limit.
  * Business requirement - BR3
  * This use case corresponds with the third business requirement. UC3 describes the permissions of the Admins, which allows them add and remove users from the portal. Admins are needed for users to be created, so this is important when setting up user accounts. The admins are bound by the seat/license limit. 

* UC4
  * Reset Password
  * Actor: User, Admin, and Super Admin
  * Users can reset their password.
  * Business requirement - BR5
  * This use case corresponds with the fifth business requirement. UC4 describes the first permission of users, which allows users to reset their password. Users log in with a username and password when first launching the application, so giving users the ability to change their password is helpful for the users in case they forget their password. It also saves time, as an admin or account creator doesn't have to reconfigure the password for users or anything.

* UC5
  * View Usage Metrics
  * Actor: User, Admin, and Super Admin
  * Users can view their usage metrics/analytics.
  * Business requirement - BR6
  * This use case corresponds with the sixth business requirement. UC5 describes the other permission that users are given, which is the ability to view usage metrics. Any user should be able to view the metrics. When users are viewing usage metrics, they should find information about number of cases, number of files, amount of minutes transcribed, most searched terms, and most hit terms. 

* UC6
  * Usage Metrics displays information about user's usage.
  * Actor: Super Admin and Admin.
  * Super Admins and Admins can view information about user activity.
  * Business requirement - BR4
  * This use case corresponds with the fourth business requirement. UC6 describes the information that Admin usage metrics provide. The metrics/analytics measures the activites of the users and provides statistics about them. These bits of information are important for measuring the activities of users and organizations. 
