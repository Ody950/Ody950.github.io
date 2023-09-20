
# Payment Processing



## why this topic matters as it relates to what Iam studying in this module?

 It is crucial for us as .NET developers to understand the importance of payment processing in enabling businesses to accept and process payments securely and efficiently. .NET developers are able to automate payment-related tasks, ensure secure transactions, and provide a seamless payment experience for their users by utilizing these systems. Payment processing systems provide efficient, secure, and scalable solutions for handling payment transactions.


## Summary


The payment gateway is the interface through which credit cards are entered into an online store. The payment gateway is an e-commerce software that authorizes payments for online merchants. It is consumer-facing interfaces used to collect payments. The payment gateway is the checkout portal through which credit card information is entered into the online stores.



Prerequisites

Assuming you are familiar with .NET Core concepts, particularly the MVC pattern, I assume you have knowledge of object-oriented programming concepts in C#.

To code along with me, you will have to install the .NET Core 2.2, as well as Visual Studio. You can also use another IDE instead of a visual studio.

Braintree Implementation:

    Set up Braintree account

    Set up the development environment

    Generate client tokens

    Card payments

    In order to set up a Braintree account, first we must sign up for the account at Braintreepayment.com. We will receive a sandbox account from Braintree so we can test the API and decide whether or not to push the app into production. Upon successful completion of all of these steps, we must login to sandbox.braintreegatway.com.



How Does Online Credit Card Processing Work?

Merchant Accounts

    Using a Merchant Account, you can connect to the credit card processing network.

    Merchant Accounts accept (or decline) credit cards and ultimately transfer the funds into your bank account.

Payment Gateway

    A responsible party is responsible for sending a credit card over a secure channel to the appropriate Internet Merchant Account.

    The gateway acts as a router that sends credit card information to the appropriate account.

Your Application

    Several different methods can be used to interact with the Payment Gateway. In simple applications, such as shopping carts, the user may be transferred to a web page through the Gateway to process credit card information. Upon completion of the transaction, the user will be returned to the application.



