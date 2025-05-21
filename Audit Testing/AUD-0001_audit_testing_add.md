## **AUD-0001:** Audit testing - Add  

> **Summary:** Verify that inventory item is saved and displayed successfully.  <br>

**Preconditions:**

 - At least one product with inventory exists.
 - User has access to the Audit module.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Audit" page.                           | Verify that a list of items with current stock levels is displayed.  | 
 |  2 | Input new stock quantity for a specific item.           | Verify that the input value is reflected in the textbox of the item row.   | 
 |  3 | Click the "Confirm Audit" button.                       | Verify that a modal will pop up displaying the updated stock item and audit confirmation summary.   |  
 |  3 | Click the "Confirm Audit" button inside the modal.      | Verify that a success message is shown, and the audit entry is saved.   |  
 |  3 | (Optional) Click the "Cancel" button instead.           | Verify that the modal closes without saving any changes.   |  

**Post-conditions:**  

 - The audit entry is saved with correct updated stock information (refresh page).
 - The audit log reflects the action with user, timestamp, and item details.
 - No changes are saved if the confirmation modal is canceled.
