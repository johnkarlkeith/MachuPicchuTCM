## **USER-0003:** User testing - Add Auditor  

> **Summary:** Verify that Auditor is saved and displayed successfully.  <br>

**Preconditions:**  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.                                  | Verify that a page appears for creating a new users.   | 
 |  2 | Fill out the form with admin credentials and select "Auditor" as the role.  | Fields are validated; role is set to Auditor.   | 
 |  3 | Click "Create Account".                                                     | Verify that success message is displayed; new Auditor user appears in the list.   |  

**Post-conditions:**  

 - Auditor user is created with full access. 
 - Auditor appears in the user list (edit user page > select user) with the correct details (upon clicking the user in the list).
