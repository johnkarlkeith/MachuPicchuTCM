## **SEC-0002:** Authentication testing  

> **Summary:** Verify all inputs can handle Cross-Site Scripting (XSS) attacks.  <br>

**Preconditions:**   

 - WepApp is accessible.
 - Authentication module is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Authentication management module is accessible.             | Input fields (e.g., name, email) are visible.   | 
 |  2 | Enter a malicious script: <script>alert('XSS')</script>     | Script is neutralized or displayed as plain text. No alert shown.  | 
 |  3 | Submit the form.                                            | Entry is saved safely or validation error is triggered.   |  
 |  3 | Revisit or refresh the Authentication module.               | No script execution occurs.   |

**Post-conditions:**  
  
 - Authentication module does not allow or execute XSS scripts.