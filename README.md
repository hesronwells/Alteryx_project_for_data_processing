# Alteryx_project_for_data_processing

ASSIGNMENT

1. Update the Existing Data Warehouse Orders table with the latest POS orders, placed in August 2021.

2. Update the POS and Existing Data Warehouse Orders table with the returns information. That is, set the RETURNED column, to the right value.

 3. Update the Data Warehouse Customers table with the latest customer information from the POS input. That is, a customer may have changed their details, like address (anything that s not the customer ID) during their latest order. We want the Data Warehouse to be updated with the most recent customer details. Note that the POS system has the US State name in full. Ensure you change that to the State code prior to loading it into the Data Warehouse Customers table. For example, “Florida” should become “FL”. The State Lookup file provides a mapping you may use.
 
 
Inputs from data file (Excel and CSV). Same process works for fetching or processing data from database server

![](Store%20data/Inputs.png)

Data Model for assignment 1 and 2

Update Existing and New orders with Return Indicator

![](Store%20data/Assignment1.png)

Update customer details

![](Store%20data/Assignment2.png)

PFB entire data model for wholesale store data processing

![](Store%20data/Final.png)

Outputs:

1)Updated Existing and New orders with Return Indicator

![](Store%20data/Order_details.png)

2)Updated customer details


![](Store%20data/Customer_details.png)

