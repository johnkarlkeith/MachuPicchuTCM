## **CAT-0004:** Category testing - Filter  

> **Summary:** Verify that selecting categories from the filter only shows corresponding products and hides unselected ones..  <br>

**Preconditions:**

 - User is logged in.
 - At least two or more categories exist.
 - Products are already assigned to at least one category.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Products" page.                                    | Product page loads with all products visible.   | 
 |  2 | Click the "Filter" button.                                          | Filter sidebar appears on the right side of the page.   | 
 |  3 | Under the "Category" section, select a category.                    | Radio button selection is activated for selected category.   |
 |  4 | Wait for automatic filtering.                                       | Only products belonging to the selected categories are displayed; others are hidden.   |
 |  5 | (Optional) Unclick the selected categories.                         | All products become visible again regardless of category.   |  

**Post-conditions:**  

 - Only products from selected category are shown in the product view.  
 - Unselected category products are hidden from view.  
 - Filtered view can be cleared to reset visibility.  
