## **CON-0003:** 5G testing  

> **Summary:** Verify the app is working on 5G network.  <br>

**Preconditions:**

 - Device is connected to 5G.
 - User is logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open the Webapp, Log-in, and navigate between modules.    | Pages and transitions load instantly.  | 
 |  2 | Pages and transitions load instantly.                     | Heavy data loads should complete with minimal latency.   | 
 |  3 | Generate, update, or delete a record.                     | Instant confirmation and toast response.   | 


**Post-conditions:**  

 - App takes full advantage of 5G bandwidth and responds instantly.