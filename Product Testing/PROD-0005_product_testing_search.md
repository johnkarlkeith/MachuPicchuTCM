## **PROD-0005:** Product testing - Search  

> **Summary:** Verify that search feature is working successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least one product exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                                | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click on the search bar at the top of the page.                                 | Cursor is placed inside the search bar.   | 
 |  3 | Type the name (or partial name) of an existing product  and click "Search".     | Products matching the keyword are dynamically filtered and displayed.   |

 Scenario 2 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                               | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Type a keyword that does not match any product and click "Search".             | A “No products found” message is displayed.   |  

**Post-conditions:**  

 - Only products matching the search term are displayed.  
 - The search bar remains accessible for new searches.  
 - Clearing the search input resets the product list.  
