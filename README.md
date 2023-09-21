# InventoryManagementSystem
A software developed using Java SE which provides as easy way to track the products, suppliers, customers as well as purchase and
sales information. It also records the stock currently available in the store. 
  There are basically two users, Administrator and Normal User. Both the users can manage suppliers, products, customers and purchase and sell products.
  The only difference between the two users is that the administrator can also view sales report and can also manage other users.

Required third party plugins: JCalender, JTattoo and SQLConnector

Credentials:

After importing the sql file and adding the plugins, try using the credential username: `user4` and password: `test123`

Also make sure your mysql is username: `root` and password: `root`. If not change the credential in `../ims/src/com/inventory/database/ConnectionFactory.java` line no. 36 and 44.
