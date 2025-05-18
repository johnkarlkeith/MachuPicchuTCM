## **REP-0003:** Transaction Reports testing - View  

> **Summary:** Verify that reports made is viewable successfully.  <br>

**Preconditions:**

 - At least one transaction report has been added.
 - User has access to the Reports module and the linked Google Sheets. 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Reports" page.                         | Reports page loads and list of reports is displayed. | 
 |  2 | Click the "Google Sheets" button.                       | Google Sheets containing transaction data/Financial Report opens in a new tab or embedded view. | 
 |  3 |	Locate the sheet or tab according to the report date.   | The correct sheet/tab is shown with data matching the selected report's date. |  
 |  4 | Scroll through the sheet to review details.             | Financial Report are clearly presented and accurate. |  

**Post-conditions:**  

 - Google Sheet reflects the correct data based on selected report.  
 - User can view, scroll, and confirm the recorded values.  
 - Report dates align with saved transaction entries.  
