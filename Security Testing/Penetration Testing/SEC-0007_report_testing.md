## **SEC-0007:** Report testing  

> **Summary:** Verify all inputs can handle Cross-Site Scripting (XSS) attacks.  <br>

**Preconditions:**   

 - User is logged in as Admin.
 - Report module is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Report management module is accessible.                        | Input fields are visible.   | 
 |  2 | Enter a malicious script: <script>alert('XSS')</script>       | Script is neutralized or displayed as plain text. No alert shown.  | 
 |  3 | Submit the form.                                              | Entry is saved safely or validation error is triggered.   |  
 |  3 | Revisit or refresh the Report module.                          | No script execution occurs.   |

**Post-conditions:**  
  
 - Report module does not allow or execute XSS scripts.