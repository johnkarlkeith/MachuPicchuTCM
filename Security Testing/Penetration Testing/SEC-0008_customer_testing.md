## **SEC-0008:** Customer testing  

> **Summary:** Verify all inputs can handle Cross-Site Scripting (XSS) attacks.  <br>

**Preconditions:**   

 - WepApp is online
 - Customer module is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Customer management module is accessible.                        | Input fields are visible.   | 
 |  2 | Enter a malicious script: <script>alert('XSS')</script>       | Script is neutralized or displayed as plain text. No alert shown.  | 
 |  3 | Submit the form.                                              | Entry is saved safely or validation error is triggered.   |  
 |  3 | Revisit or refresh the Customer module.                          | No script execution occurs.   |

**Post-conditions:**  
  
 - Customer module does not allow or execute XSS scripts.