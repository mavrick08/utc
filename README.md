Live Project


Date:  23rd November 2021

SD : Punit K.



The below requirement is for one of our clients who’s want a web interface application for its company (CMS Portal).

There will be 2 modules in this 

1) Employee Module

2) Admin Module


1) Employee Module : Here there will be a web interface where there will  be option of logging in to the system as well as forget password.

Please keep it in mind NO account creation (create new account) options is to  be given.

Only for the employees who’s account is created by admin can log in, into the system

Please note employees who’s status is active are allowed to login in (refer admin module)


2) Main Page (Dashboard) : Here in dashboard we will have the following menus.

1) Add Product

2) View All Products

3) Add Doctor

4) Schedule doctor Appointment

5) Today’s Schedule

6) Deals Detail

For add products page make the form using the below field.

    • Product Name
    • Product Company Name
    • Product Image
    • Product Price 
    • Enterd By (Employee Name used for login.)




For view all product page show the data in tabular format below

Sr no
Product Name
Company Name
Product Price
Entred By



For Add doctor page create the form design using the fields below:

    • Doctor Name

    • Doctor Specialisation (Chest, Heart, General,Orthopaedic,etc..)

    • Doctor Contact Number

    • Doctor Location

    • Entered by (employee name)


For Schedule doctor Appointment Page use the below field

    • Drop Down (list of doctor name)
    • Date of Schedule
    • Time of Schedule
    • Entered by (employee name)



For Today’s Schedule Details


    • Date Selector 
    • Submit button

output will be List of Doctors Schedule for that particular day in tabular format

Sr no
Doctor Name
Date of Meeting
Time








Deals Detail

    • Name of doctor (drop down)
    • Product Name
    • Quantity ordered
    • Entered by (employee name)


Admin Module:

1) Employee Creation : Here the admin will need to create the employee accounts, use the fields below.

    • Employee first name
    • employee last name
    • employee email
    • employee password
    • employee date of joining
    • employee status

Please note employee who’s status is acttive are allowed to login,  rest are not allowed.



2) List of all Employee

Here list of all the employee registered by the admin in tabular format with all these data

    • Employee first name
    • employee last name
    • employee email
    • employee date of joining
    • employee status


3) List of all Products

Here the list of all products needs to be shown based on the employee name

so the filed will be 

    • Drop down of list of all employee name 
    • Submit button 

Once we click on submit button the products details table should be viewed.

Sr no
Product Name
Company Name
Product Image
Product Price
Entered By










4) Deals Details

Here the list of all deals done will be shown based on the employee name and month selected.

so the filed will be 

    • Drop down of list of all employee name 
    • Drop Down for Months
    • submit button

On clicking submit button a table should be shown 

Sr no
Total Deals Done
Employee Name



4) Doctos Visits Details

Here the list of all doctors visits done will be shown based on the employee name and month selected.

so the filled will be 

    • Drop down of list of all employee name 
    • Drop Down for Months
    • submit button

On clicking submit button a table should be shown 

Sr no
Total Appointments Done
Employee Name



For user panel you can use the below link for the UI

https://startbootstrap.com/theme/sb-admin-2


DB: SQLite3
