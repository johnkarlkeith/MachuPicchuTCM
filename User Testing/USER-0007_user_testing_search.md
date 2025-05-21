## **USER-0007:** User testing - Search  

> **Summary:** Verify that search feature is working successfully.  <br>

**Preconditions:** _None_  

 - Admin user must be logged-in.
 - User has access to the Account Management module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Account Management" page.          | Verify that a page appears for creating a new users.   | 
 |  2 | Click the "Edit User" button.                       | Verify that edit user page appears with "Select user to edit" settng. | 
 |  3 | Click "Select User" drop down button.               | Verify that list of users will appear with search bar. |  
 |  4 | Enter a name in the search bar                      | List dynamically filters based on the search input. |   
 |  5 | Clear the search bar.                               | Full user list is restored. | 

**Post-conditions:**  

 - Relevant users are shown based on the keyword input.
 - Search is responsive and resets correctly. 
