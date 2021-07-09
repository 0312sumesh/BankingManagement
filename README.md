# BankingManagement
Here, you can create a new account, update information of an existing account, view and manage transactions, check the details of an existing account, 
remove existing account and view customers’ list.

All in all, with this C program, you can perform banking activities like in a REAL bank. this program is a graphic-less console application.

The source code for this program is around 600 lines, This banking program can't be accessed without a password.
("password protected, password=Bank"===>password is||case-sensitive||)

Methods(Functions()) used in Banking management system are:

Customer Account Bank Management System is relatively short and easy to understand. The Functions are generally has their own instance of process, mostly related to banking activities.

the Functions are listed below:
1.menu() – This function displays the menu or welcome screen to perform different banking activities.

2.new_acc() – This function creates a new customer account. It asks for some  personal and banking details of the customer such as name, date of birth, citizenship number, address and phone number. 
You can enter the amount to deposit and choose one type of deposit account – saving, current, fixed for 1 year, fixed for 2 years or fixed for 3 years. 

3.view list() – With this function, you can view the customer’s banking information such as account number, name, address and phone number provided while creating the account.

4.edit() – This function has been used for changing the address and phone number of a particular customer account.

5.transact() – With this function, you can deposit and withdraw money to and from a particular customer account.

6.erase() – This function is for deleting a customer account.

7.see() – This function shows account number, name, date of birth, citizenship number, age, address, phone number, type of account, amount deposited and date of deposit. 
It also displays the amount of interest corresponding to a particular account type.

In this bank management program, File management has been used for overall functions. File has been used to store the data related to accounts, transactions, editing of account informartion and viewing the account inforamtion.
