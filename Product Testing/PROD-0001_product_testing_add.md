## **PROD-0001:** Product testing - Add  

> **Summary:** Verify that product is saved and displayed successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least one category exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                                | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the "Add Product" button.                                                 | A side panel form for adding a product appears.   | 
 |  3 | Fill in product details such as upload image, category, and product name.       | Input values are correctly reflected and validated (e.g., required fields, numeric fields for price/stock).   |
 |  4 | Click the "Save Product" button.                                                | A success notification appears, modal closes, and the new product is added to the product list.   |  
 |  5 | (Optional) Refresh the page                                                     | The newly added product remains visible in the product list with details.   |    

**Post-conditions:**  

 - A new product is saved in the system.   
 - The product appears in the product list page.  
 - The product is now available for viewing, editing, deletion, and filtering by category.  
