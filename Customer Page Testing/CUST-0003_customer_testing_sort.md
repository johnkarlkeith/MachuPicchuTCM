## **CUST-0003:** Customer testing - Sort  

> **Summary:** Verify that sorting feature is working successfully.  <br>

**Preconditions:** _None_  

 - Public customer page is accessible
 - Multiple in-stock products with varying prices exist

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Visit the public customer page.                         | Verify that the product list displays only products with stock greater than zero.  | 
 |  2 | Select Peso with arrow button.                          | Verify that products are reordered either highest (arrow points app) to lowest (arrow points down) price.  | 
 |  3 | Refresh Page.                                           | Verify that products are reordered randomly.  | 

**Post-conditions:**  

 - Product list is dynamically reordered based on selected price sort  
 - Product visibility dynamically updates based on stock status.  
