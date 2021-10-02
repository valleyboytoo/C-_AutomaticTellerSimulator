# Csharp-_AutomaticTellerSimulator

# SPECIFICATIONS 

Key Functions

The main functions of the ATM simulator may be summarized as follows:

• Before performing any transaction, the user must enter his or her name and PIN (personal identification number) on an input screen. Since the operation of this input screen should simulate the normal operation of an ATM, the PIN should not appear on the screen.

• In addition to the message which appears after every unsuccessful attempt, if after three tries the PIN matching the name has not been entered, the application should display a message requesting the user to try using the ATM again later. The names and PINs of users must be validated using data contained in the Customers data source having the following

structure:

 name (String)

 PIN (String – 4 characters)

Note: For the purposes of this project, the data source can be either of two types, a SQL database whereby you will require to connect your application to the database tables and access the content accordingly using LINQ. Alternatively, you can use the provided CustomerInfo.txt text file as a source of the data. In this case you will need to use the handling files and streams information found in the content for Session 7 of your Student Learning Guide. It is your choice on how you store and access the data.

# Flowcharts

