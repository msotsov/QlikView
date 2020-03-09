# QlikView

Here is workshop on QlikView from Business Intelligence course. I have been using the sample data (3 different data files, but actually only 2) from Microsoft Dynamics NAV 365 ERP system. The requirements for this workshop were following:

  - extract the data from NAV 365
  - create basic data model
  - display inventory balance
  - display top 5 products 

2 files (customers and items) were extracted directly from NAV as an excel files and one (item ledger) was created in a qvd format in QlikView environment. 

<b>General steps that I have followed:</b>

Step 1: 
Extract files from ERP system

Step 2:
Create empty QlikView file, import sample data, edit script (make necessary modifications, check and modify relations, add time dimensions)

Step 3:
Data visualisation

Inventory balance sheet:
 - First visual - display inventory balance (item number, amount in stock, sort in descending order by amount in stock) 
 - Second visual - display inventory balance using cyclic group (item number/item description, amount in stock, sort by amount in stock) 

Product balance sheet:
 - Display top 5 products by total price (quantity * unit price). Same grouping was used as on the Inventory balance sheet (second visual).


