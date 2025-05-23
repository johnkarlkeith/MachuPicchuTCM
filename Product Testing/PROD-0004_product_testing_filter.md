## **PROD-0004:** Product testing - Filter  

> **Summary:** Verify that search filters work successfully.  <br>

**Preconditions:** _None_  

 - User is logged in.
 - At least one product exists in the system.
 - Products are already assigned to at least one category and one supplier.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                    | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the "Filter" button.                                          | Filter sidebar appears.   | 
 |  3 | Select a category or/and supplier under the respective section.     | Only products belonging to the selected category or/and supplier are shown..   |
 |  4 | (Optional) Unselect the category.                                   | All products are shown again.   |  
 |  5 | (Optional) Click the "Cancel" button on the prompt.                 | The deletion process is aborted and the product remains in the product list.   |
 |  6 | (Optional) Refresh the page.                                        | Deleted product remains removed if deletion was confirmed; otherwise, the product stays.   |    

**Post-conditions:**  

 - Products displayed match the selected category or supplier.  
 - Filters can be reset to display all products.  
 - Filtering works dynamically without needing a page refresh.  
