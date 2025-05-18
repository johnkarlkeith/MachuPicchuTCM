## **REP-0004:** Transaction testing - Delete  

> **Summary:** Verify that inventory item is deleted successfully.  <br>

**Preconditions:**

 - At least one transaction report exists
 - User has access to the Reports module 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Reports" page.                         | Reports page loads and existing reports are displayed. | 
 |  2 | Locate the transaction report you want to delete.       | The report is listed with visible action icons (e.g., delete/trash icon). | 
 |  3 | Click the Delete icon/button on the selected report.    | A confirmation prompt appears asking for delete confirmation. |
 |  4 | Confirm the deletion.                                   | Success message is shown, and the selected report is removed from the list. | 
 |  5 | (Optional) Refresh the page.                            | The deleted report does not reappear and is permanently removed. |    

**Post-conditions:**  

 - The selected report is permanently deleted from the system.  
 - The report no longer appears and cannont be filtered, downloaded, or calculated.  
