## **PERF-0003:** Performance testing - Maximum Inventory Items  

> **Summary:** Verify that the app can add and view maximum inventory items.  <br>

**Preconditions:**

 - Products are already created.
 - Admin access to Inventory Management.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Add numerous inventory entries per product (e.g., batches/transactions, 500+ entries).    | Entries are saved and tracked successfully. | 
 |  2 | View inventory for a product with large volume of entries.                                | Inventory sidebar/list loads within acceptable time.   | 
 |  3 |	Perform operations like sorting, searching, or editing inventory.                         | Actions are executed without significant delay or timeout.  |  
 |  4 |	Check system resource usage or app responsiveness during load.                            | Memory and performance remain stable.   | 

**Post-conditions:**  

 - Inventory data remains responsive and manageable at large scale. 