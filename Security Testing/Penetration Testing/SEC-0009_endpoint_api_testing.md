## **SEC-0009:** Endpoint/API testing  

> **Summary:** Verify that API is accessible and is secure.  <br>

**Preconditions:**

 - Valid authentication token or user login is available.
 - Tools like Postman or curl are ready.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Send API request with valid token to an endpoint (e.g., GET /users)     | Valid response with data is returned (status 200).   | 
 |  2 | Send request without authentication.                                    | Response status is 401 Unauthorized or 403 Forbidden.   | 
 |  3 | Try to send a script inside a POST/PUT payload.                         | API returns 400 Bad Request or sanitizes input.   |
 |  4 | Test rate-limiting or excessive requests.                               | API limits or blocks after a threshold.   |
 |  5 | Attempt access to restricted endpoints.                                 | API limits or blocks after a threshold.   |   

**Post-conditions:**  

 - APIs enforce authentication, sanitize inputs, and protect sensitive data.
