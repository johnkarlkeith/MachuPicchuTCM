## **SUP-0003:** Supplier testing - Delete  

> **Summary:** Verify that supplier is deleted successfully.  <br>

**Preconditions:** _None_  

 - User is logged in.
 - At least one category exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                            | Product page loads and displays available products.   | 
 |  2 | Click the "Filter" button.                                                  | Filter sidebar appears on the right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Supplier" section.                   | "Supplier" sidebar overlaps the filter sidebar, "Add Supplier" is the default view.   |
 |  4 | Switch to the "Edit Supplier" tab or view.                                  | The form updates to allow selecting and editing existing suppliers.   |
 |  5 | Select a supplier from the dropdown list.                                   | The selected supplier's current details populate the form fields.  |
 |  6 | Click the "Delete" (trash bin icon) button.                                 | Changes are reflected in the form inputs.   |
 |  7 | Confirm deletion in the modal.                                              | A success notification appears and the updated supplier is saved.   |
 |  8 | (Optional) Click the "Cancel" button.                                       | The form resets and closes if the user chooses to cancel.  |

**Post-conditions:**  

 - The selected supplier is permanently removed from the system.  
 - The deleted supplier no longer appears in the filter or supplier lists.
 - Products previously assigned to that supplier become uncategorized.  
