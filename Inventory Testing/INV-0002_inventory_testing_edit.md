## **INV-0002:** Inventory testing - Edit  

> **Summary:** Verify that inventory item is modified and displayed successfully.  <br>

**Preconditions:** 
  
 - At least one product exists
 - At least one inventory record has been added for that product
Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the products page and select a product                                  | Existing products with details are displayed. | 
 |  2 | Inside a product card, click on the "Add Inventory" button (box icon with a "+")    | A form-side bar for adding inventory details opens. | 
 |  3 | Click "Browse Inventories"                                                          | A list of inventories made with corresponding dates is displayed. |  
 |  4 | Click on the inventory entry you want to edit                                       | Inventory details for the selected entry are displayed. |  
 |  5 | Modify the necessary fields (e.g., quantity, remarks) and click "Save Inventory"    | Success message is shown and upon refreshing the page, changes are saved, and updated details are visible. | 

**Post-conditions:**  

 - The inventory record reflects the updated details.  
 - Changes are displayed immediately in the inventory list.   
 - Inventory logs/history (if available) capture the modification.   
