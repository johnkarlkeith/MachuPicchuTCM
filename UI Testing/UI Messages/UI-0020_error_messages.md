## **UI-0020:** Error Messages  

> **Summary:** Verify that error messages are displayed successfully.  <br>

**Preconditions:**  

 - User is logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Submit a form with required fields empty.                               | Inline error message is shown near the empty input field.   | 
 |  2 | Enter invalid data in a form (e.g., letters in numeric field).          | Specific validation error appears, highlighting the problematic input.   | 
 |  3 | Attempt to save a product without required fields.                      | General error message appears above the form or as a toast.   | 
 |  4 | Simulate backend failure (e.g., disconnect network).                    | A system-level error is shown as a toast or modal popup.  |
 |  5 | Retry after correcting input.                                           | Error message disappears; form is submitted successfully.   |  

**Post-conditions:**  

 - Error messages provide clear feedback and guide user correction behavior. 
