## **PERF-0001:** Performance testing - Maximum Categories  

> **Summary:** Verify that the app can add and view maximum categories.  <br>

**Preconditions:**

 - User is logged in as Admin.
 - Access to the Product Filter > Category Management is available.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Use a script or manually add categories up to the allowed/system limit (e.g., 500+).    | Categories are added successfully without crashing or lag. | 
 |  2 | Navigate to the Filter > Category section.                                              | All categories are listed and scrollable with no visual glitches.   | 
 |  3 |	Select multiple categories to filter products.                                          | Filtering works as expected with no performance drop.  |  
 |  4 |	Attempt to add one more category beyond the system limit.                               | Application either gracefully prevents or handles the overflow.   | 

**Post-conditions:**  

 - Categories are accessible, scrollable, and manageable even at maximum capacity.  
