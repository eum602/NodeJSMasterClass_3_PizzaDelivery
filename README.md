# NodeJSMasterClass_3_PizzaDelivery
## Steps:

1.**clone the repository**

2.**Start the server**
```
NODE_DEBUG=server NODE_ENV=staging node index.js
```
3.**Test the app (Go to the broowser and open http://localhost:3000/)**

    3.1. Create a new user:
    ```
    You can create a new user by clicking Get Started and following the steps, a new token will be automatically created
    which will allow you to navigate and make some operations on the page
    ```  
    ```
    3.2. Create a new pizza delivery Order:
    By clicking on create order (in the upper menu) you will be able to choose over all the items (drinks and pizzas)
    After choosing you will be redirected to a new page where you should enter a visa card number (only for testing
    purposes use 4242 4242 4242 4242)
    
    An total charge will be showed accordingly to the prices of the selected items and the respective amounts
    
    If all goes well you will receive a message from the server that your payment has been successfully submitted
    also you will receive an email about your order.
    
    
    Results: Result is limited because it is only using the sandBox of Mailgun (and not an own domain), but you can adapt this with your own data.
