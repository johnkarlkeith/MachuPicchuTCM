## **UI-0013:** Product testing  

> **Summary:** Verify that DBCS inputs are saved and displayed properly.  <br>

**Preconditions:**  

 - User is logged in (if required).
 - Appropriate form or input field exists in the module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the module page.                                        | Page loads with relevant input fields visible.   | 
 |  2 | Enter DBCS characters (e.g., 日本語, 中文) in the input fields.      | Characters are accepted and displayed correctly.   | 
 |  3 | Click the 'Save' or equivalent action button.                       | Data is saved with DBCS characters intact.   |  
 |  3 | Reload or revisit the page where the data is displayed.             | Previously saved DBCS inputs are displayed properly without corruption.   |  


**Post-conditions:**  

 - DBCS inputs are stored correctly in the database.  
 - DBCS inputs are rendered correctly in the UI.  
 - No encoding or display issues occur with DBCS data.  

