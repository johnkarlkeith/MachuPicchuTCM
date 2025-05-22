## **AUTH-0001:** Authentication Testing - Log-in  

> **Summary:** Verify that user can log-in successfully.   <br>

**Preconditions:**

 - Valid user account exists (e.g., Admin, Treasurer, Auditor, Secretary).
 - Login page is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Login page                      | Login form with email and password fields is displayed.   | 
 |  2 | Enter valid email and password credentials      | Input is accepted and validated.   | 
 |  3 | Click the “Log In” button                       | User is redirected to the appropriate dashboard with a success notification (if applicable).   |  

**Post-conditions:**  

 - User is authenticated and granted access to the system.  
 - Session is initialized and maintained.  
 - User role (e.g., Admin, Treasurer) determines accessible features. 
