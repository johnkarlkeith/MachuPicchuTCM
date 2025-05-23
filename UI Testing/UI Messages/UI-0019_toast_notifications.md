## **UI-0019:** Toast notifications  

> **Summary:** Verify that toast notifications are working successfully.  <br>

**Preconditions:**

 - User is logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Save a product, user, or category successfully.             | A toast appears at the bottom/top corner of the screen with success message.   | 
 |  2 | Wait without interaction.                                   | Toast disappears automatically after a few seconds.   | 
 |  3 | Perform another valid action (e.g., delete item).           | Another toast appears indicating success.   | 
 |  4 | Trigger multiple toasts consecutively (if possible).                      | Toasts are stacked or queued correctly without overlap or freezing.   |  

**Post-conditions:**  

 - Toast notifications provide short, effective feedback for actions.  

