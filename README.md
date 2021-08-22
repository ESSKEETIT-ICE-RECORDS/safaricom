# DarajaSTK
A simple implementation of "Lipa na Mpesa Online using STK Push offerd by the Daraja api

NB : All callback info is logged 

## What is Mpesa Express ?
This is a service where you launch the user M-pesa menu directy from your application by calling the mpesa sim tool kit,and prefill with the amount to pay, the user just inserts the PIN and money automatically deducted from their Mpesa and sent to your Paybill. The merchant simply pushes the transaction details of a payment to customer's phone. After transaction initiation, the customer receives a push notification.Customer enters their M-Pesa pin and presses ‘OK’. The transaction is now complete, and a real-time payment confirmation will be sent. The details are sent to the callback set and further processing such as subscription can be carried out.
Accepted Number format is only 07.....

## SCREENSHOT
![Form ScreenShot](https://raw.githubusercontent.com/CreamyMilk/DarajaSTK/master/Form%20For%20STK%20PUSH.png "Screenshot")


To install the dependencies and run 


```python
# You must configure environment variables in an (.env) file

$ cp .env.sample .env
```

```shell
# To install dependencies and to run the server

$ npm install 
$ npm start 
```
