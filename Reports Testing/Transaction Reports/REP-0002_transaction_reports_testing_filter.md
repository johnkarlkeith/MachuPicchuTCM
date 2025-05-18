## **REP-0002:** Transaction Reports testing - Filter  

> **Summary:** Verify that search filters work successfully.  <br>

**Preconditions:**

 - At least one transaction exists across different dates (e.g., today, this week, past month, etc.).

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Navigate to the Transaction Reports page.           | The report page loads, and "All Dates" is selected by default; all transactions are displayed. | 
 |  2 | Click the date filter dropdown and select "Today".  | Only transactions created today are displayed in the list. | 
 |  3 |	Select "This Week" from the filter options.         | Only transactions from the current week are shown. |  
 |  4 | Select "This Month" from the filter options.        | Only transactions from the current month are shown. |  
 |  4 | Select "This Quarter" from the filter options.      | Only transactions from the current quarter are shown. |  
 |  4 | Re-select "All Dates".                              | All available transactions are displayed again |  

**Post-conditions:**  

 - Filtered report is correctly displayed based on selected date range.  
 - Filter selection persists during session or until changed. 
 - System accurately retrieves data corresponding to each filter.    
