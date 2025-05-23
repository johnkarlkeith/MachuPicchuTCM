## **PROD-0003:** Product testing - Delete  

> **Summary:** Verify that product is deleted successfully.  <br>

**Preconditions:** _None_  

 - User is logged in.
 - At least one category exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                    | Product page loads successfully with existing product listings (if any).   | 
 |  2 | Click the three-dotted button on a product card.                    | Product details sidebar appears with "Edit Product" as the default option.   | 
 |  3 | Click the "Delete Product" button in the sidebar.                   | A confirmation prompt appears.   |
 |  4 | Confirm deletion.                                                   | A success notification appears, the sidebar closes, and the product is removed from the product list.   |  
 |  5 | (Optional) Click the "Cancel" button on the prompt.                 | The deletion process is aborted and the product remains in the product list.   |
 |  6 | (Optional) Refresh the page.                                        | Deleted product remains removed if deletion was confirmed; otherwise, the product stays.   |    

**Post-conditions:**  

 - If confirmed, product is permanently removed from the system.  
 - Product no longer appears in lists, filters, or reports.  
 -  Inventory count is updated accordingly.  
