## **USER-0006:** User testing - Delete  

> **Summary:** Verify that user is deleted successfully.  <br>

**Preconditions:** _None_  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.          | Verify that a page appears for creating a new users.   | 
 |  2 | Click the "Edit User" button.                       | Verify that edit user page appears with "Select user to edit" settng. | 
 |  3 | Click "Select User" drop down button.               | Verify that list of users will apper with search bar. |  
 |  4 | Click a user to edit.                               | Verify that edit form will apper with details. |   
 |  5 | Click "Delete User".                                | Deletion modal will pop-up. | 
 |  6 | Click "Delete".                                     | Loading will be seen; user will be deleted; you will be back to edit user page. |  

**Post-conditions:**  

 - Deleted user no longer appears in the list.
