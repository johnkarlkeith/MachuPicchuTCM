## **INV-0001:** Inventory testing - Add  

> **Summary:** Verify that inventory item is saved and displayed successfully.  <br>

**Preconditions:** At least one product exists in the system

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the products page and select a product                                  | Existing products with details are displayed. | 
 |  2 | Inside a product card, click on the "Add Inventory" button (box icon with a "+")    | A form-side bar for adding inventory details opens. | 
 |  3 | Fill up the form and click "Save Inventory"                                         | Success message is shown. Upon refreshing the page, inventory is increased, other details are updated, and updated stock is visible. |  
 |  4 | Inside a product card, click the 3 dots icon                                        | A side bar with product details is displayed. |  
 |  5 | Click the "Browse Inventories" button                                               | A list of inventories made with corresponding dates is displayed. |  
 |  6 | Click the latest date inventory                                                     | The latest/recent inventory details made will be shown. | 

**Post-conditions:**  

 - Inventory quantity of the selected product is successfully updated.  
 - Inventory log reflects the new entry with accurate date and details.  
 - Updated stock is visible in both product and inventory views.  
