## Domain Model
![Class Diagram](https://github.com/judek10/crime-admin-and-user-portal/blob/895adf355a9813420d15aea5a16e26a3e2451502/Auxiliary%20files/CrimeAdminPortal_ClassDiagram.vpd.jpg)

## Explanations
* User - User is any user of this portal.
* Admin - Admin has all permissions of user, and they have additional permissions which allow for them to add/remove users and assign admins.
* Super Admin - Super Admin has all the permissions of admin and user, and they have additional permissions which allow for them to create organizations.
* Organization - An organization is a grouping of users using the portal usually used for companies.
* UserUsageMetrics - User usage metrics are analytics any user can view about their activities on CrimeMiner like number of cases, number of files, most searched terms, etc.
* AdminUsageMetrics - Admin usage metrics are analytics admins and super admins can view about the activities of users in the organization.
* License - Organizations have a pool of licenses which is distributed and associated with admins and users.
