# Bank_Functional
This is a small banking app that allows the user to log in, view their account balance, transaction history, transfer money, request a loan, and close their account.

The app is built using JavaScript and is based on the concept of object-oriented programming. It uses the module pattern to encapsulate the data and methods related to the app, which makes it easier to manage the app and keep the code organized.

Functionality
Upon loading, the user is prompted to log in using a username and a PIN code. If the login is successful, the user is greeted with a welcome message that displays their name and the current date and time. The app also displays the user's account balance, a summary of their recent transactions, and a list of their transaction history.

The user can perform the following actions:

Transfer money: The user can transfer money to another account by entering the recipient's username and the amount they wish to transfer. The app will verify that the user has sufficient funds in their account before processing the transfer.

Request a loan: The user can request a loan by entering the amount they wish to borrow. The app will approve the loan if the user has a positive balance and the requested loan amount is less than 10% of their account balance.

Close account: The user can close their account by entering their username and PIN. The app will delete the user's account data and log them out of the app.
