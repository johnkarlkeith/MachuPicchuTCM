## **REP-0001:** Transaction Reports testing - Add  

> **Summary:** Verify that transaction is saved successfully.  <br>

**Preconditions:**

 - User has access to the Reports module 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Reports" page.                  | Reports page loads and existing reports (if any) are displayed. | 
 |  2 | Click the "Create Report" button.                | A modal form pops up with fields for Cash Inflow and Cash Outflow. | 
 |  3 | Enter values for Cash Inflow and Cash Outflow.   | Values are accepted and validated (e.g., numeric only, required fields) |  
 |  4 | Click "Submit Report".                           | Success message is displayed, modal closes, and the new report appears in the list. |  
 |  5 | (Optional) Refresh the page.                     | The newly added report remains visible with correct inflow/outflow values. | 

**Post-conditions:**  

 - A new report with the specified cash inflow and outflow is saved.  
 - The report appears in the transaction report list.  
 - The data is available for filtering, deleting, downloading, and whole calculations.  
