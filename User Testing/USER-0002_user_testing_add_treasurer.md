## **USER-0002:** User testing - Add Treasurer  

> **Summary:** Verify that standard user is saved and displayed successfully.  <br>

**Preconditions:**  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.                                       | Verify that a page appears for creating a new users.   | 
 |  2 | Fill out the form with admin credentials and select "Treasurer" as the role.     | Fields are validated; role is set to Treasurer.   | 
 |  3 | Click "Create Account".                                                          | Verify that success message is displayed; new Treasurer user appears in the list.   |  

**Post-conditions:**  

 - Treasurer user is created with full access. 
 - Treasurer appears in the user list (edit user page > select user) with the correct details (upon clicking the user in the list).

