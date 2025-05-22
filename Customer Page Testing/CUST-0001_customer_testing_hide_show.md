## **CUST-0001:** Customer testing - Hide/Show  

> **Summary:** Verify that customer Page hide/show feature is working successfully.  <br>

**Preconditions:**

 - Public customer page is accessible
 - Some products have stock, some have zero stock

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Visit the public customer page.                         | Verify that the product list displays only products with stock greater than zero.  | 
 |  2 | Verify that products with 0 stock are not visible.      | Verify that no out-of-stock products appear on the page.   | 
 |  3 |	Add stock to a previously out-of-stock product.         | Verify that the product becomes visible on the customer page.   |  
 |  4 |	Remove all stock from a product.                        | Verify that that product is no longer visible on the customer page.   |  

**Post-conditions:**  

 - Customer can only view in-stock products.  
 - Product visibility dynamically updates based on stock status.  
