## **CAT-0002:** Category testing - Edit  

> **Summary:** Verify that category is modified and displayed successfully.  <br>

**Preconditions:** 

 - User is logged in.
 - At least one category already exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                | Product page loads and displays available products.s   | 
 |  2 | Click the "Filter" button.                                      | Filter sidebar appears on the left/right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Category" section.       | "Category" sidebar overlaps the filter sidebar, "Add Category" is the default view.   |
 |  4 | Switch to the "Edit Category" option in the sidebar.            | The form updates to allow selecting and editing existing categories.   |  
 |  5 | Select a category from the dropdown menu.                       | The selected category's current details populate the form fields.   |  
 |  6 | Apply changes to category details.                              | Changes are reflected in the form inputs.   |  
 |  7 | Click the "Save Category" button.                               | A success notification appears and the updated category is saved.   |  
 |  8 | (Optional) Click the refresh button.                            | The form resets and closes if the user chooses to cancel.   |    

**Post-conditions:**  

 - The selected category is updated with new details.    
 - The updated category is usable for product filtering and assignment.  
