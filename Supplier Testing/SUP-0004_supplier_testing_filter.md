## **SUP-0004:** Supplier testing - Filter  

> **Summary:** Verify that selecting suppliers from the filter only shows corresponding products and hides unselected ones..  <br>

**Preconditions:** _None_  

 - User is logged in.
 - At least two or more supplier exist.
 - Products are already assigned to at least one supplier.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                    | Product page loads with all products visible.   | 
 |  2 | Click the "Filter" button.                                          | Filter sidebar appears on the right side of the page.   | 
 |  3 | Under the "Supplier" section, select a supplier.                    | Radio button selection is activated for selected supplier.   |
 |  4 | Wait for automatic filtering.                                       | Only products belonging to the selected supplier are displayed; others are hidden.   |
 |  5 | (Optional) Unclick the selected supplier.                           | All products become visible again regardless of supplier.   |  

**Post-conditions:**  

 - Only products from selected supplier are shown in the product view.  
 - Unselected supplier products are hidden from view.  
 - Filtered view can be cleared to reset visibility.  