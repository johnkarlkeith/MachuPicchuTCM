## **SUP-0001:** Supplier testing - Add  

> **Summary:** Verify that category is saved and displayed successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least one product exists in the system.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                              | Product page loads and displays available products.   | 
 |  2 | Click the "Filter" button.                                    | Filter sidebar appears on the right side of the page.  | 
 |  3 | Click the three-dotted icon under the "Supplier" section.     | "Supplier" sidebar overlaps the filter sidebar, "Add Supplier" form is the default option.   |  
 |  4 | Enter category name and other details in the form.            | Input values are correctly reflected in the text fields.   |
 |  5 | Click the "Save Supplier" button.                             | A success notification appears and the new Supplier is added to the list.   |

**Post-conditions:**  

 - A new inventory supplier is created and saved in the system.  
 - The supplier is now available in the filter options.  
 - Products can now be assigned or filtered using the newly added supplier. 
