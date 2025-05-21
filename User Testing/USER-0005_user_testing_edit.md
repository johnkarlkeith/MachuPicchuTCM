## **USER-0005:** User testing - Edit  

> **Summary:** Verify that user is modified and displayed successfully.  <br>

**Preconditions:**  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.          | Verify that a page appears for creating a new users.   | 
 |  2 | Click the "Edit User" button.                       | Verify that edit user page appears with "Select user to edit" settng. | 
 |  3 | Click "Select User" drop down button.               | Verify that list of users will apper with search bar. |  
 |  4 | Click a user to edit.                               | Verify that edit form will apper with details. |  
 |  5 | Modify user details (e.g., name, role, email).      | Fields are editable and validated. |  
 |  5 | Click "Save Changes".                               | Success message is shown, and updated user is saved. |  
 |  6 | Click "Cancel".                                     | Edit form will be closed. | 

**Post-conditions:**  

 - Changes are saved and reflected in the user details.