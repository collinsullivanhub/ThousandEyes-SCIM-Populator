# ThousandEyes-SCIM-Populator
SCIM User Creation for ThousandEyes Platform

ThousandEyes is now able to add, update and delete users from identity providers who support the SCIM 2.0 and 1.1 standards, dramatically decreasing time to provision users into ThousandEyes and perform ongoing user management.

This script can be used to pull user's information from a CSV file in standard format and populate them into a user role within the ThousandEyes platform.

# Instructions:
1. Make sure you are running at least Python >3.0 (https://www.python.org/download/releases/3.0/)
2. In terminal, run: python3 te_scim.py
3. Enter CSV file name (format x.csv)

# Results:
By default, users added through SCIM to ThousandEyes will be assigned the "Regular User" role in all Account Groups of the organization where they are created.

Please see the following document for more information: 
https://docs.thousandeyes.com/product-documentation/user-management/thousandeyes-support-for-scim 

# Sample Output:

![alt text](https://github.com/collinsullivanhub/ThousandEyes-SCIM-Populator/blob/main/Screen%20Shot%202021-02-18%20at%201.47.45%20PM.png)

