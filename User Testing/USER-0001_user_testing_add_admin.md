## **USER-0001:** User testing - Add Admin  

> **Summary:** Verify that admin user is saved and displayed successfully.  <br>

**Preconditions:**  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.                                  | Verify that a page appears for creating a new users.   | 
 |  2 | Fill out the form with admin credentials and select "Admin" as the role.    | Fields are validated; role is set to Admin.   | 
 |  3 | Click "Create Account".                                                     | Verify that success message is displayed; new Admin user appears in the list.   |  

**Post-conditions:**  

 - Admin user is created with full access. 
 - Admin appears in the user list (edit user page > select user) with the correct details(upon clicking the user in the list).
