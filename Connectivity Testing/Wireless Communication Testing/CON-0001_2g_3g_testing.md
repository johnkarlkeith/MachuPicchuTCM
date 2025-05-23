## **CON-0001:** 2G/3G testing  

> **Summary:** Verify the app is working on 2G/3G network.  <br>

**Preconditions:** 

 - Device is switched to a 2G/3G network.
 - User is logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Log-in to the WebApp.                              | WebApp launches, though loading may be slower.   | 
 |  2 | Navigate to key features (e.g., Product page).     | Page loads eventually; performance may degrade.   | 
 |  3 | Submit a form or update data.                      | Data is sent and saved with delay.   | 
 |  4 | Receive notification (toast or drawer).            | Notification may be delayed but should arrive.   |  
 |  5 | Observe app responsiveness.                        | UI should remain responsive, even if data is loading slowly.   |   

**Post-conditions:**  

 - All critical functions work with acceptable delay on 2G/3G.  
 
