# EKOVIT APP
* Offline (Mobile) App
* Online (Website) App

## Offline (Mobile) App

### 1. Selling Point
* Protective password will be gotten from the online app craeted by the supper amdin
* Admin must be logged in to perform any transaction
* Products can be posted (saved) as point of sell services as they customers buy
    - name
    - amount
    - amount_paid
    - balance
    - comment
* Admin can view all products sold
* Admin can search through the sold products
* Admin can filter by date/time/name/amounts/amount_paid
* Admin can click to view a product sold
    - Can edit (the name, amount, amount_paid, balance and comment) and password must be required
    - Cannot delete
* Admin can upload the sold product to the online database (online sold_product database table) and have to be online and authourized to do this
* All the uploaded products will be removed from the offline app (offline sold_product database table)

### 2. Product price
* This will be configured on the online app and get downloaded in the offline app
* Can search through


## 3. Online (Website) App
* The app will only have a user which will be the supper admin with basic authenticated and authorization
    - The developer will create the supper admin with a and working email defualt password
    - The supper admin can login with the email and the deafault passowrd (The UI will not have register page)
    - The supper admin can login to reset the password
    - The password can be resetted if forgotten
* Supper admin can create a password to protect the offilne app, this password can be updated incase forgotten or when there is a need to reset
* An api should created where the offline mobile app will download the passowrd 
* The supper admin can create product categories
* Can view all the categories with edit and delete buttons (functional)
* An api should created where the offline mobile app will download the categories
* An api should be created where the sold products will be saved in the databse from the mobile app
* Supper admin can edit the sold products (only the amount, amount_paid, balance, comment, name cannot be edited) and deleted them
* 