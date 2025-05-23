## **UI-0018:** Notification Drawer  

> **Summary:** Verify that notifications are working successfully.  <br>

**Preconditions:**

 - User is logged in.
 - Notification triggers (e.g., stock alerts, system messages) are active.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Perform an action that triggers a notification (e.g., low inventory).       | A notification badge with a number appears on the notification bell/icon.   | 
 |  2 | Click on the notification icon.                                             | 	The notification drawer slides in or opens, showing a list of recent notifications.   | 
 |  3 | Hover over or click a notification item.                                    | The item is highlighted or reacts to interaction (e.g., hover effect).   |  
 |  4 | Click on a specific notification.                                           | Dsiplay related modal (e.g., Inventory tab for low stock alert).   |
 |  5 | Clear all notifications (if feature is available).                          | Notification drawer is emptied; badge count resets to zero.   |


**Post-conditions:**  

 - Notification drawer accurately displays and manages real-time alerts.   
