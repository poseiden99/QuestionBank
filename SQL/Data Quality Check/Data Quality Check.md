### Find orders where Amount does not match the sum of (Price * Quantity) in OrderDetails.

Orders 
| OrderID | CustomerID | OrderDate  | Amount | Status    |
| ------- | ---------- | ---------- | ------ | --------- |
| 101     | 1          | 2023-03-01 | 200    | Completed |
| 102     | 2          | 2023-03-03 | 150    | Pending   |
| 103     | 1          | 2023-03-10 | 350    | Completed |
| 104     | 3          | 2023-03-15 | 400    | Cancelled |

OrderDetails 
| OrderDetailID | OrderID | ProductID | Quantity |
| ------------- | ------- | --------- | -------- |
| 1             | 101     | 1         | 2        |
| 2             | 101     | 3         | 1        |
| 3             | 103     | 2         | 1        |
| 4             | 104     | 1         | 4        |

products
| ProductID | ProductName | Category  | Price |
| --------- | ----------- | --------- | ----- |
| 1         | Chair       | Furniture | 100   |
| 2         | Table       | Furniture | 200   |
| 3         | Lamp        | Lighting  | 50    |

