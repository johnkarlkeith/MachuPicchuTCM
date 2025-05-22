## **CAT-0003:** Category testing - Delete  

> **Summary:** Verify that category is deleted successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least one category exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                            | Product page loads and displays available products.   | 
 |  2 | Click the "Filter" button.                                                  | Filter sidebar appears on the right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Category" section.                   | "Category" sidebar overlaps the filter sidebar, "Add Category" is the default view.   |
 |  4 | Switch to the "Edit Category" tab or view.                                  | The form updates to allow selecting and editing existing categories.   |
 |  5 | Select a category from the dropdown list.                                   | The selected category's current details populate the form fields.  |
 |  6 | Click the "Delete" (trash bin icon) button.                                 | Changes are reflected in the form inputs.   |
 |  7 | Confirm deletion in the modal.                                              | A success notification appears and the updated category is saved.   |
 |  8 | (Optional) Click the "Cancel" button.                                       | The form resets and closes if the user chooses to cancel.  |

**Post-conditions:**  

 - The selected category is permanently removed from the system.  
 - The deleted category no longer appears in the filter or category lists.
 - Products previously assigned to that category become uncategorized.  
