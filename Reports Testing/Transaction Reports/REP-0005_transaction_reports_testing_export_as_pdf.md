## **REP-0005:** Transaction Reports testing - Export as PDF  

> **Summary:** Verify that a transaction report can be exported as PDF successfully.  <br>

**Preconditions:**

 - At least one transaction report exists
 - User has access to the Reports module   

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Reports" page.                     | Reports page loads with a list of existing transaction reports. |
 |  2 | Locate the transaction report you want to delete.   | The report is listed with visible action icons (e.g., delete/trash icon). |  
 |  3 | Click the "Download" button.                        | A PDF file is generated based on the currently displayed report data. | 
 |  4 | Save or open the downloaded PDF file.               | PDF downloads successfully showing the transaction report with correct details. |  

**Post-conditions:**  

 - A PDF file containing the selected report data is downloaded.  
 - Report includes necessary Financial Report (e.g. data, inventory, audit, and etc.).
 - PDF is formatted clearly and can be opened or shared without issue.  
