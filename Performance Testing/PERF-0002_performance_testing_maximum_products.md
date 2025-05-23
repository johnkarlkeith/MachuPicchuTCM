## **PERF-0002:** Performance testing - Maximum Products  

> **Summary:** Verify that the app can add and view maximum products.  <br>

**Preconditions:**

 - User is logged in as Admin.
 - Product module is accessible.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Add multiple products until the system/database reaches a high-load threshold (e.g., 1,000+).   | Products are added successfully and saved properly. | 
 |  2 | Navigate to the Products page.                                                                  | Product list loads with acceptable speed (<2s), even with large volume.  | 
 |  3 |	Scroll and search through the product list                                                      | All operations respond efficiently without lag or UI glitches. |  
 |  4 |	Apply filters (by category, supplier).                                                          | Filtering executes within an acceptable response time.  | 

**Post-conditions:**  

 - System can handle viewing and filtering of high-volume products smoothly. 