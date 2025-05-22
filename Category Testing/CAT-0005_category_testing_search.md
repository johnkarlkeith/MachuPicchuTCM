## **CAT-0005:** Category testing - Search  

> **Summary:** Verify that the category search feature in the "Edit Category" form works successfully.  <br>

**Preconditions:**

 - User is logged in.
 - At least two or more categories exist.
 - The user is on the "Products" page and has accessed the "Edit Category" form.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                            | Product page appears successfully.   | 
 |  2 | Click the "Filter" button.                                                  | Filter sidebar appears on the right side of the page.   | 
 |  3 | Click the three-dotted icon under the "Category" section.                   | Category sidebar overlaps with the filter sidebar and defaults to "Add Category."   |  
 |  4 | Switch to the "Edit Category" tab.                                          | Edit Category form is displayed with a dropdown button for list of existing categories.   | 
 |  5 | Type a keyword in the search field after clicking the dropdown button.      | Category list is filtered based on the entered keyword.   |
 |  6 | (Optional) Clear the search input.                                          | Full category list is shown again.   | 
    

**Post-conditions:**  

 - The matching categories are displayed based on the search term.  
 - Non-matching categories are hidden from the dropdown list.
 - The user can select a category from the filtered result for editing.  
