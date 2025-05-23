## **PROD-0002:** Product testing - Edit  

> **Summary:** Verify that product is modified and displayed successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least one category exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                                | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the three-dotted button on a product card.                                | Product details sidebar appears with "Edit Product" as the default option.   | 
 |  3 | Modify the product details (e.g., category, name, and reorder point).           | Updated values are reflected in the corresponding fields.   |
 |  4 | Click the "Save Product" button.                                                | A success notification appears and the updated product is saved and shown in the product list.   |  
 |  5 | (Optional) Refresh the page                                                     | Edited product remains visible with the updated details.   |    

**Post-conditions:**  

 - Product details are updated in the system.   
 - The product appears with the new values in the product list.  
 - Updated information is now used in filtering, display, and calculations.  
 
