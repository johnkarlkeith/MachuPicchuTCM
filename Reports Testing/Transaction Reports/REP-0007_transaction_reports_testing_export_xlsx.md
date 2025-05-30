## **REP-0007:** Transaction Reports testing - Export XLSX  

> **Summary:** Verify that a transaction report can be exported as XLSX successfully.  <br>

**Preconditions:**

 - At least one transaction report exists
 - User has access to the Reports module and the linked Google Sheet

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the "Reports" page.                                             | Reports page loads with a list of existing transaction reports. | 
 |  2 | Click the "Google Sheets" button.                                           | Linked Google Sheet opens in a new tab or embedded view. | 
 |  3 | In Google Sheets, click File > Download > Microsoft Excel (.xlsx).          | A .xlsx file is generated and downloaded with the transaction datas from the sheet. |  

**Post-conditions:**  

 - A .xlsx file is downloaded containing the financial reports data.  
 - All relevant fields (e.g., date, inventories, audit, and etc.) are included and correctly formatted.  
 - File is readable in spreadsheet applications (e.g., Excel, LibreOffice, Google Sheets)  
