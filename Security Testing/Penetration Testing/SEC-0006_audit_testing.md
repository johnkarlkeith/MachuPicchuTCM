## **SEC-0006:** Audit testing  

> **Summary:** Verify all inputs can handle Cross-Site Scripting (XSS) attacks.  <br>

**Preconditions:**   

 - User is logged in as Admin.
 - Audit module is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Audit management module is accessible.                        | Input fields are visible.   | 
 |  2 | Enter a malicious script: <script>alert('XSS')</script>       | Script is neutralized or displayed as plain text. No alert shown.  | 
 |  3 | Submit the form.                                              | Entry is saved safely or validation error is triggered.   |  
 |  3 | Revisit or refresh the Audit module.                          | No script execution occurs.   |

**Post-conditions:**  
  
 - Audit module does not allow or execute XSS scripts.