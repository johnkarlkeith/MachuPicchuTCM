## **USER-0004:** User Testing - Add Secretary  

> **Summary:** Verify that standard user is saved and displayed successfully.  <br>

**Preconditions:**  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.                                      | Verify that a page appears for creating a new users.   | 
 |  2 | Fill out the form with admin credentials and select "Secretary" as the role.    | Fields are validated; role is set to Secretary.   | 
 |  3 | Click "Create Account".                                                         | Verify that success message is displayed; new Secretary user appears in the list.   |  

**Post-conditions:**  

 - Secretary user is created with full access. 
 - Secretary appears in the user list (edit user page > select user) with the correct details (upon clicking the user in the list).
