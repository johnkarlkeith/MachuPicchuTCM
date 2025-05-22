## **CUST-0002:** Customer testing - Search  

> **Summary:** Verify that search feature is working successfully.  <br>

**Preconditions:** _None_   

 - Public customer page is accessible
 - At least one product with stock exists

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Visit the public customer page.                             | Verify that the product list displays only products with stock greater than zero.  | 
 |  2 | Type a product name or keyword into the search bar.         | Product list filters to show only items matching the query.  | 
 |  3 | Clear the search field.                                     | Full list of in-stock products is shown again.  | 

**Post-conditions:**  

 - Search results dynamically update without page reload. 
 - Search only applies to products that are in stock.  

