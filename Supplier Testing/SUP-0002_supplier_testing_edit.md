## **SUP-0002:** Supplier testing - Edit  

> **Summary:** Verify that supplier is modified and displayed successfully.  <br>

**Preconditions:**  

 - User is logged in.
 - At least one supplier already exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                | Product page loads and displays available products.s   | 
 |  2 | Click the "Filter" button.                                      | Filter sidebar appears on the left/right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Supplier" section.       | "Supplier" sidebar overlaps the filter sidebar, "Add Supplier" is the default view.   |
 |  4 | Switch to the "Edit Supplier" option in the sidebar.            | The form updates to allow selecting and editing existing suppliers.   |  
 |  5 | Select a supplier from the dropdown menu.                       | The selected supplier's current details populate the form fields.   |  
 |  6 | Apply changes to supplier details.                              | Changes are reflected in the form inputs.   |  
 |  7 | Click the "Save Supplier" button.                               | A success notification appears and the updated supplier is saved.   |  
 |  8 | (Optional) Click the refresh button.                            | The form resets and closes if the user chooses to cancel.   |    

**Post-conditions:**  

 - The selected supplier is updated with new details.    
 - The updated supplier is usable for product filtering and assignment.  
