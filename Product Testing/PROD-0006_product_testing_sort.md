## **PROD-0006:** Product testing - Sort  

> **Summary:** Verify that sorting feature is working successfully.  <br>

**Preconditions:**

 - User is logged in.
 - Multiple products exist with varying prices and stock quantities.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                                | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the "Filter" button.                                                      | The filter sidebar appears on the side of the page.   | 
 |  3 | Select sort by price (Peso icon button) option (ascending or descending).            | Products are sorted based on their price as selected.   |

 Scenario 2

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                                        | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the "Filter" button.                                                              | The filter sidebar appears on the side of the page.   | 
 |  3 | Select sort by inventory/stock (Cube icon button) option (ascending or descending).     | Products are sorted based on their stock count.   |

**Post-conditions:**  

 - Product list is rearranged based on the selected sorting criteria.  
 - Sorting state remains until manually reset or changed by the user.  
 - zUser can change sorting preference anytime through the filter sidebar. 
