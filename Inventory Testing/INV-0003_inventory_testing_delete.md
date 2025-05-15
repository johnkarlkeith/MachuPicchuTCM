## **INV-0003:** Inventory testing - Delete  

> **Summary:** Verify that inventory item is deleted successfully.  <br>

**Preconditions:**
 - At least one product exists
 - At least one inventory record has been added for that product  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the products page and select a product.                                | Existing products with details are displayed. | 
 |  2 | Inside a product card, click on the "Add Inventory" button (box icon with a "+").  | A form-side bar for adding inventory details opens. | 
 |  3 | Click "Browse Inventories".                                                        | A list of inventories made with corresponding dates is displayed. |  
 |  4 | Click on the inventory entry you want to delet.                                    | Inventory details for the selected entry are displayed. |  
 |  5 | Click the "Delete" icon/button and confirm the action.                             | Success message is shown and upon refreshing the page, changes are saved, and updated details are visible. |
 |  5 | Refresh the page or return to the inventory list.                                  | Deleted inventory record no longer appears in the list; inventory stock is adjusted accordingly (if applicable). |

**Post-conditions:**  

 - The selected inventory record is permanently removed.  
 - The inventory list no longer includes the deleted record. 
 - Product stock is adjusted if the system recalculates totals after deletion.
