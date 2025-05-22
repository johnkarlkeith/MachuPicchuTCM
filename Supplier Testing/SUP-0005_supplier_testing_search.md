## **SUP-0005:** Supplier testing - Search  

> **Summary:** Verify that the supplier search feature in the "Edit Supplier" form works successfully.  <br>

**Preconditions:** _None_  

 - User is logged in.
 - At least two or more suppliers exist.
 - The user is on the "Products" page and has accessed the "Edit supplier" form.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                            | Product page appears successfully.   | 
 |  2 | Click the "Filter" button.                                                  | Filter sidebar appears on the right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Supplier" section.                   | Supplier sidebar overlaps with the filter sidebar and defaults to "Add Supplier."   |  
 |  4 | Switch to the "Edit Supplier" tab.                                          | Edit supplier form is displayed with a dropdown button for list of existing suppliers.   | 
 |  5 | Type a keyword in the search field after clicking the dropdown button.      | Supplier list is filtered based on the entered keyword.   |
 |  6 | (Optional) Clear the search input.                                          | Full supplier list is shown again.   | 
    

**Post-conditions:**  

 - The matching suppliers are displayed based on the search term.  
 - Non-matching suppliers are hidden from the dropdown list.
 - The user can select a supplier from the filtered result for editing.  
